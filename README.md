# Лабораторна робота №1: "Налаштування шаблону проекту"

### Виконала: Фесун Анна Валеріївна ІМ-21
 
## Інструкції для запуску проекту: 

1. Переконайтеся, що у вас встановлено Docker та Docker Compose.
2. Клонуйте репозиторій на локальний комп'ютер:
   ```bash
   git clone https://github.com/AnyaFesun/Back-end-1.git
   ```
3. Використайте наступну команду для побудови Docker образів:
   ```bash
   docker-compose build
   ```
4. Запустіть контейнери:
   ```bash
   docker-compose up
   ```
5. Після запуску контейнерів перевірте роботу вашого застосунку, відкривши веб-браузер і перейшовши за адресою: http://localhost:8080/healthcheck
6. Щоб зупинити запущені контейнери, використайте:
   ```bash
   docker-compose down
   ```
   
## Деплоймент
Застосунок успішно деплойнуто на платформі Render. 
Ви можете отримати доступ до сервісу за наступним посиланням:
https://back-end-1-spba.onrender.com/healthcheck