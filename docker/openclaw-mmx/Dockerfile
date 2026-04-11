FROM ghcr.io/openclaw/openclaw:latest

USER root

RUN npm install -g mmx-cli \
    && npm cache clean --force

RUN mmx --version || true

# Kimi Code CLI (using uv)
RUN export PATH="/root/.local/bin:$PATH" \
    && curl -LsSf https://code.kimi.com/install.sh | bash
