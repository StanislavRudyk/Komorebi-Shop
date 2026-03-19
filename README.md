# 🌿 Komorebi-Shop

[![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)](https://fastapi.tiangolo.com/)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)

**Komorebi-Shop** — це естетична та потужна Fullstack-платформа для електронної комерції, побудована на поєднанні **FastAPI** (Python), **React** та **PostgreSQL**. Назва походить від японського слова *Komorebi* (木漏れ日), що означає сонячне світло, яке пробивається крізь листя дерев, символізуючи чистоту та якість нашого коду.

---

## ✨ Основні можливості

- 🛡️ **Безпека**: Автентифікація користувачів та адмін-панель.
- 🛍️ **Керування продуктами**: Гнучкий каталог товарів.
- 🐳 **Docker-Ready**: Весь стек (бекенд, фронтенд, база даних) запускається однією командою.
- 📊 **Моніторинг БД**: Інтегрований pgAdmin для зручного керування базою даних PostgreSQL.

---

## 🛠️ Технологічний стек

- **Бекенд**: FastAPI (Python)
- **Фронтенд**: React (с заздалегідь налаштованим оточенням)
- **База даних**: PostgreSQL
- **Оркестрація**: Docker Compose

---

## 🚀 Швидкий запуск

### 1. Клонування репозиторію
```bash
git clone https://github.com/StanislavRudyk/Komorebi-Shop.git
cd Komorebi-Shop
```

### 2. Запуск через Docker
```bash
docker-compose up -d --build
```
*Ця команда змонтує та запустить усі сервіси автоматично.*

---

## 🔑 Доступ та облікові дані

### 🌍 Доступ до додатку
- **Фронтенд**: [http://localhost:3000](http://localhost:3000)
- **Бекенд (API Docs)**: [http://localhost:8000/docs](http://localhost:8000/docs)
- **pgAdmin (БД)**: [http://localhost:5050](http://localhost:5050)

### 👤 Користувачі (За замовчуванням)
| Роль        | Email               | Пароль     |
| ----------- | ------------------- | ---------- |
| **Admin**   | `admin@example.com` | `admin123` |
| **User**    | `user@example.com`  | `user123`  |

### 🐘 Доступ до pgAdmin
- **Email**: `admin@admin.com`
- **Пароль**: `admin`

---

## ⚙️ Налаштування з'єднання з БД (pgAdmin)

Для підключення до бази даних у pgAdmin використовуйте наступні параметри:
- **Host**: `db`
- **Port**: `5432`
- **Maintenance Database**: `ecommerce`
- **Username**: `postgres`
- **Password**: `password`

---

## 🏗️ Керування проєктом

- **Зупинка**: `docker-compose down`
- **Повна очистка даних**: `docker-compose down -v`
- **Логи бекенду**: `docker logs ecommerce_backend -f`
- **Оновлення фронтенду**: `docker-compose up --build frontend`

---
