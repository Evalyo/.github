# Evalyo

**Evalyo** is a modern, lightweight fork of [DMOJ](https://github.com/DMOJ/judge), designed to be fast, developer-friendly, and easy to deploy.

> Built for modern judging needs. No bloat, just power.

---

## 🚀 Features

- ⚡ Fast & scalable submission judging
- 🐳 Dockerized development + deployment
- 📜 Pythonic backend with Django
- 🌐 REST API & real-time submission updates
- ✨ Cleaned up UI (WIP)
- 🔧 Configurable grading environments
- 🛠️ Pluggable problem formats + languages

---

## 📦 Tech Stack

- Python 3.12+
- Django 4+
- PostgreSQL
- Redis
- RabbitMQ
- Docker & Docker Compose

---

## 🛠️ Getting Started

```bash
git clone https://github.com/YOUR-ORG/evalyo.git
cd evalyo
cp config/settings/local.py.example config/settings/local.py
docker compose up --build
````

Then visit: `http://localhost:8000`

---

## 📁 Project Structure

* `judge/` – Backend Django app (core logic)
* `site/` – Frontend (templates, static)
* `config/` – Django settings & environment configs
* `docker/` – Docker setup and service definitions

---

## 🧪 Testing

```bash
docker compose exec judge python manage.py test
```

---

## 📄 License

MIT – feel free to use, fork, and contribute.

---

## 🙌 Credits

Based on the solid foundation of [DMOJ](https://github.com/DMOJ/judge).
Props to their team for years of groundwork.

---

**Evalyo** is under active development. Stay tuned.
