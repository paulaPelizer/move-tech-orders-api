# move-tech-lab-docker

Repositório starter para o **Lab H2 · Empacotar com Docker** do curso Move Tech (Magalu × Prósper Digital Skills).

## O que tem aqui

| Arquivo | O que é |
|---------|---------|
| `app/main.py` | API de Pedidos em FastAPI (in-memory) |
| `pyproject.toml` | Dependências gerenciadas com Poetry |

## O que você vai adicionar

No lab, você vai criar:
- `Dockerfile` — empacota a API em uma imagem Docker
- `docker-compose.yml` — sobe a aplicação com um único comando

## Endpoints da API

| Método | Rota | Descrição |
|--------|------|-----------|
| GET | `/health` | Status da aplicação |
| POST | `/orders` | Criar pedido |
| GET | `/orders` | Listar pedidos |
| GET | `/orders/{id}` | Buscar pedido |
| DELETE | `/orders/{id}` | Cancelar pedido |
| POST | `/orders/{id}/items` | Adicionar item |
| GET | `/orders/{id}/items` | Listar itens |

Documentação interativa disponível em `http://localhost:8000/docs` após subir o container.
