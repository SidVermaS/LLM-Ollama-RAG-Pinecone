# LLM POC
## Overview
Choose one of three setup options to run this project:
1. [Local Jupyter Setup](#1-local-jupyter-setup)
2. [Local Application Setup with Ollama](#2-local-application-setup-with-ollama)
3. [Local Application Setup with AWS Bedrock](#3-local-application-setup-with-aws-bedrock)

## 1. Local Jupyter Setup
```bash
docker compose -f docker-compose-notebook.yml up
```

## 2. Local Application Setup with Ollama
```bash
docker compose -f docker-compose-ollama-local.yml up
```

## 3. Local Application Setup with AWS Bedrock
```bash
docker compose -f docker-compose-aws-local.yml up
```