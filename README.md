# Техническое задание рассылка
# Документация:
## Документация по api указана в файле api_docs.txt. Сервис спроектирован при помощи фреймворка django REST. Когда пользователь отправляет запрос на эндпоинт по созданию рассылки, celery и django_celery_bean (брокер - redis) автоматически принимают эту задачу и выполняют по заданной логике. Функции api доступны. Админка и просмотр с редактированием исполняемых запросов сделаны с помощью flower.
## Доп задачи: 3, 5-10, 12
# Запуск
## sudo docker-compose up --build 




