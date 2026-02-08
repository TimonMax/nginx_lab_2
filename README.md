# Nginx в Docker

## 👩‍💻 Автор
**ФИО:** Фаткин Артем Александрович  
**Группа:** 2ПМ-1  

---

## 📌 Описание задания
Настройка Nginx + PHP-FPM. Основы HTML-форм и обработка на JavaScript.
👉 http://localhost:8080

---

## ⚙️ Как запустить проект

### 1. Клонировать репозиторий
```bash
git clone git@github.com:TimonMax/nginx_lab_2.git
cd nginx-lab
```
### 2. Запустить контейнеры Docker
```bash
docker-compose up -d --build
```
### 3. Открыть в браузере
```bash
http://localhost:8080
```

## Содержимое проекта
docker-compose.yml — описание сервиса Nginx

code/index.html — главная HTML-страница

code/about.html — дополнительная HTML-страница