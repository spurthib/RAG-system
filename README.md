# RAG Model with LLaMA 3.2

## Project Overview

This project builds a Retrieval-Augmented Generation (RAG) pipeline using the LLaMA3.2:3b (8B) language model accessed via Ollama running in Docker. We will integrate this with Python tools like LangChain and LangGraph to query custom documents intelligently.

---

## Prerequisites

- **Windows** machine
- VSCode
- Python 3.10+
- Docker
- Git
- Ollama Docker image (pulled and running)

---

## Setup Steps

### 1. Docker & Ollama Container Setup

- Pulled Ollama Docker image:
  ```bash
  docker pull ollama/ollama

Started Ollama container:

- Started Ollama container:
  ```bash
  docker run -d -p 11434:11434 --name ollama ollama/ollama

- Verified running container:
  ```bash
  docker ps

## Pulled LLaMA 3.2 Model (8B) in Container

### Pulled model inside container:

```bash
docker exec -it ollama ollama pull llama3:8b
