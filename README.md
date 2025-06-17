# Multi-Container DevOps Stack

🧱 Стек:
- Tomcat (8080)
- MySQL (3307)
- RabbitMQ (15672, 5672)
- Memcached (11211)
- Nginx (8081)

## 🚀 Запуск

```bash
docker compose up --build
```

## 📦 Структура
- `docker-compose.yml`
- `tomcat/webapps/ROOT.war` — сервлет додаток
