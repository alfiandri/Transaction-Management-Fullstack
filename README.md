# Transaction Management Fullstack (monorepo)

A production-ready fullstack system:

- ⚡ Fastify backend
- 🐘 TimescaleDB
- 🐳 Docker + Docker Compose
- 🧪 Jest + Supertest
- 🎨 Next.js + Tailwind Dashboard
- 🔐 JWT Authentication

## Prereqs
- Docker & Docker Compose
- Node (optional for local dev)

## Build & run (production, docker-compose)
### build images
docker compose build --no-cache

### bring up
docker compose up -d

### logs
docker compose logs -f

### stop
docker compose down

### running migration
```docker exec -it {container_name} npx knex migrate:latest```

### running seeder
```docker exec -it {container_name} npx knex seed:run```

## 📜 License

MIT License © 2025 Alfiandri Putra Perdana, S.Kom., M.Kom.
