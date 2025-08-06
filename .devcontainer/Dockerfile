FROM mcr.microsoft.com/devcontainers/python:3.11

# Install Node.js
RUN curl -fsSL https://deb.nodesource.com/setup_20.x | bash - && \
    apt-get install -y nodejs

# Install Python tools
RUN pip install --no-cache-dir pre-commit yamllint

# Install markdownlint-cli2 (Node-based)
RUN npm install -g markdownlint-cli2

WORKDIR /workspace
