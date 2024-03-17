FROM mcr.microsoft.com/devcontainers/go:1-1.22-bookworm

RUN useradd \
        -d /var/lib/docker \
        -u 1001 \
        -m \
        -U \
        -s /bin/bash \
        docker \
    && gpasswd -a vscode docker
