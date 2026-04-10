FROM ghcr.io/openclaw/openclaw:latest

USER root

RUN npm install -g mmx-cli \
    && npm cache clean --force

RUN mmx --version || true
