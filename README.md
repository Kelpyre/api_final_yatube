# api_final

Данный проект является финальной домашней работой в рамках обучения в Яндекс.Практикум, модуль знакомства с API. В функционал входит макет учебного проекта yatube, а так же полноценно работающий CRUD.

Создатель проекта - студент Яндекс.Практикума Дмитрий Филимонов, telegram: @kelpyre

В проекте использованы технологии Django REST Framework, Swagger, ReDoc, JWT, Djoser.

Для того, чтобы развернуть копию проекта, клонируйте его из репозитория, установите виртуальную среду (venv), и установите зависимости из файла requirements.txt

В рамках API доступен следующий функционал:
- POST запросы к эндпоинту аутентификации (реализована при помощи TokenAuthentication);
- GET, POST, PUT, PATCH, DELETE запросы к эндпоинтам модели Post;
- GET запросы к эндпоинтам модели Group;
- GET, POST, PUT, PATCH, DELETE запросы к эндпоинтам модели Comments;
- GET, POST к эндпоинтам модели Follow.

Примеры запросов и ответов API можно посмотреть в документации Swagger: http://127.0.0.1:8000/swagger/
