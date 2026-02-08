# Лабораторная работа №2:  Nginx + PHP-FPM

## 👩‍💻 Автор
**ФИО:** Фаткин Артем Александрович  
**Группа:** 2ПМ-1  

---

## 📌 Описание задания
1. Настроить Nginx для работы с PHP через PHP-FPM.
2. Показать работу PHP на примере phpinfo().
3. Повторить основы HTML: формы и разные типы полей.
4. Обработать форму на JavaScript без перезагрузки страницы.
http://localhost:8080

---

## ⚙️ Как запустить проект

### 1. Клонировать репозиторий
```bash
git clone https://github.com/TimonMax/nginx_lab_2.git
cd nginx-lab-2
```
### 2. Запустить контейнеры Docker
```bash
docker-compose up -d --build
```
### 3. Открыть в браузере
```bash
http://localhost:8080
```
### 4. Проверка работы PHP
```bash
http://localhost:8080/phpinfo.php
```
## Содержимое проекта
```docker-compose.yml``` — описание сервиса Nginx

```www/form.html``` — главная HTML-страница с формой

```www/index.php``` — подключает form.html

```www/phpinfo.php``` — файл с phpinfo() для проверки

```nginx/default.conf`` — файл для обработки PHP