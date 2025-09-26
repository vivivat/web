Лабораторная работа №1: Nginx + Docker
👩‍💻 Автор
ФИО: Вахрушева Виктория Вадимовна
Группа: 3МО-РБД2

📌 Описание задания
Создать веб-сервер в Docker с использованием Nginx и подключить HTML-страницу.
Результат доступен по адресу http://localhost:3000.

⚙️ Как запустить проект
Клонировать репозиторий:
git clone [<ссылка на репозиторий>](https://github.com/vivivat/web/lab1)
cd nginx-lab
Запустить контейнеры:

docker-compose up -d --build
Открыть в браузере: http://localhost:8080 📂 Содержимое проекта

docker-compose.yml — описание сервиса Nginx

code/index.html — главная HTML-страница

code/abiut.html — dnjhfz HTML-страница (4 step)

screenshots/ — все скриншоты

✅ Результат Сервер в Docker успешно запущен, Nginx отдаёт мою HTML-страницу.

