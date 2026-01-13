# Docker Compose Demo

A simple demonstration of Docker Compose with multiple services working together.

## 🚀 Services

| Service    | Description                  | Port  |
|------------|------------------------------|-------|
| **Nginx**  | Static web server            | 8080  |
| **PostgreSQL** | Database server          | 5432  |
| **Adminer** | Database management UI      | 8081  |

## 📦 Prerequisites

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## 🛠️ Usage

### Start the services

```bash
docker-compose up -d
```

### View the web page

Open your browser and navigate to: [http://localhost:8080](http://localhost:8080)

### Access database admin

Open [http://localhost:8081](http://localhost:8081) and use:
- **System**: PostgreSQL
- **Server**: db
- **Username**: demo
- **Password**: demo123
- **Database**: demodb

### Stop the services

```bash
docker-compose down
```

### Stop and remove volumes

```bash
docker-compose down -v
```

## 📁 Project Structure

```
.
├── docker-compose.yml    # Docker Compose configuration
├── html/
│   └── index.html        # Static web page
└── README.md             # This file
```

## 🐳 Images Used

- `nginx:alpine` - Lightweight Nginx web server
- `postgres:16-alpine` - PostgreSQL 16 database
- `adminer:latest` - Database management interface

## 📝 License

MIT
