# Docker GitHub Actions

Aplicação simples desenvolvida em Python com FastAPI para exercício de Docker, GitHub Actions e Container Registry.

## Endpoint

GET /hello

Resposta da versão 1.0:

Hello World

## Executar localmente

```bash
docker build -t minha-aplicacao:1.0 .
docker run -p 8080:8080 minha-aplicacao:1.0
