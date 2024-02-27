#### Триал-версия Путь Дао

минимальный набор api, для  загрузки фронта.
Также рабочие образцы тестов для CRUD api.
И  конфиги для разворачивания в контейнерах.

#### Запуск проекта
Клонируем код
git clone git@github.com:DEsipov/webinar_diplom_1.git

Собираем контейнеры
docker compose up –build

Заходим внутрь контейнера backend
docker exec -it infra-backend-1 bash

делаем миграции
./manage.py migrate

собираем статику
./manage.py collectstatic

создаем суперюзера.
./manage.py createsuperuser

Запускаем на localhost
проверяем работу, статики, медиа, админки, api.



### Полезные ссылки

https://docs.google.com/document/d/132BqRgVzwE7qtLsO_A8PQBrs6XUf6ZZCr4SqT0Jgj3U/edit

