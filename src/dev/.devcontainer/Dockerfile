FROM mcr.microsoft.com/devcontainers/base:debian13

# helix
RUN apt-get update \
  && apt-get install -y --no-install-recommends hx \
  && rm -rf /var/lib/apt/lists/*

# opencode
USER vscode
RUN curl -fsSL https://opencode.ai/install | bash