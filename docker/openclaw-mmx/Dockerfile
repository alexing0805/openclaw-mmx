From ghcr.io/openclaw/openclaw.latest

USER root

run nimo install -g mmx-cli \
    && nimo cache clean --force

run mmx --version || true

# Kimi Code CLI (using uv)
run curl -LsSf https://code.kimi.com/install.sh | bash