# Nginx Docker Demo

A minimal Docker Compose setup running Nginx as a static web server.

## 🚀 Quick Start

```bash
# Start the server
docker-compose up -d

# View the web page
open http://localhost:8080

# Stop the server
docker-compose down
```

## 📦 Stack

| Service | Image | Port |
|---------|-------|------|
| **Nginx** | `nginx:alpine` | 8080 |

## 📁 Project Structure

```
.
├── docker-compose.yml    # Docker Compose configuration
├── html/
│   └── index.html        # Static web page
└── README.md             # This file
```

## 🐳 Image

- `nginx:alpine` - Lightweight Nginx web server (~7MB)

## 📝 License

MIT
