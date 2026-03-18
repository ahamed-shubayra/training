# 🌙 Moon Quiz

A beautiful cosmic quiz app with a moon background, featuring 3 categories and 7 questions each.

## Categories
- ⚽ **Sport** — 7 questions about sports
- 🎨 **Art** — 7 questions about art history & techniques
- 💻 **IT** — 7 questions about technology & programming

Each game picks 5 random questions from the category.

---

## Run with Docker

### Option 1 — Docker Compose (recommended)
```bash
docker-compose up --build
```
Then open: **http://localhost:8080**

### Option 2 — Docker only
```bash
docker build -t moonquiz .
docker run -p 8080:80 moonquiz
```
Then open: **http://localhost:8080**

---

## Stop the app
```bash
docker-compose down
```
