FROM node:20

RUN apt update && \
  apt install -y redis-server python3 python3-pip && \
  npm install -g @mermaid-js/mermaid-cli

WORKDIR /workspace
COPY . .
