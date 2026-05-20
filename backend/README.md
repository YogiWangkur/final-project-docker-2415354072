# Final Project Docker

## Deskripsi
Aplikasi CRUD User menggunakan Node.js, MySQL, Docker Compose, dan Redis.

---

## Fitur
- GET User
- POST User
- PUT User
- DELETE User
- Docker Compose
- MySQL
- Redis
- phpMyAdmin

---

## Struktur Project

```bash
docker-praktikum/
│
├── backend/
│   ├── app.js
│   ├── Dockerfile
│   ├── Dockerfile.bad
│   ├── .dockerignore
│   ├── .env
│   └── package.json
│
└── docker-compose.yml
```

---

## Menjalankan Project

```bash
docker compose up --build
```

---

## Endpoint API

### GET Users

```bash
GET /users
```

### POST User

```bash
POST /users
```

### PUT User

```bash
PUT /users/:id
```

### DELETE User

```bash
DELETE /users/:id
```

---

## Docker Hub

Image tersedia di:

```bash
eugenius24/app-good
```

---

## Author

- Nama: Yog
- Praktikum Docker Container