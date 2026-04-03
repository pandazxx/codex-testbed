FROM ghcr.io/pandazxx/codex-slack-agent-minimal:latest

USER root
RUN apt-get update && apt-get install -y --no-install-recommends \
    cowsay \
    && rm -rf /var/lib/apt/lists/*
USER appuser
