# Flask Store API 🛒

A simple REST API developed with Flask for managing stores and items.
This project was created for learning purposes, focusing on Flask fundamentals and Docker usage.

## 🚀 Technologies

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flask/flask-original.svg" width="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="40"/>
</p>

## ▶️ How to run the project

### With Docker
```bash
docker-compose up --build
```

## Without Docker
```bash
pip install -r requirements.txt
python app.py
```

## 📍 API Endpoints

| Method | Endpoint        | Description           |
|--------|-----------------|-----------------------|
| GET    | /store          | List all stores       |
| POST   | /store          | Create a new store    |
| GET    | /store/{id}     | Get store by ID       |
| POST   | /item           | Create a new item     |
| GET    | /item           | List all items        |
| GET    | /item/{id}      | Get item by ID        |

> ⚠️ Project under active development!
