# PSK Montag

Full-stack project with Rails 8 API and Vue 3 frontend.

## Tech Stack

- **Backend**: Ruby 3.4.1, Rails 8.0, PostgreSQL, Puma, Redis, Sidekiq
- **Frontend**: Vue 3, TypeScript, Vue Router

## Getting Started

### Prerequisites

- Docker and Docker Compose

### Run with Docker

```bash
docker compose up -d
```

- **Frontend**: http://localhost:8080
- **API**: http://localhost:3001
- **API Health**: http://localhost:3001/up

### Useful Commands

```bash
# View logs
docker compose logs -f psk_api
docker compose logs -f psk_vue

# Run Rails commands
docker compose exec psk_api rails db:migrate
docker compose exec psk_api rails console
```

## Project Structure

```
apps/
├── psk_api/    # Rails 8 API (Ruby 3.4.1)
└── psk_vue/    # Vue 3 frontend
```
