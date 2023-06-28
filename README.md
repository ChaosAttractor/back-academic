## создайте `.env` в корне проекта
```
POSTGRES_HOST=postgres (название контейнера)
POSTGRES_USER (стандартное значение =postgres)
POSTGRES_DB (как пример =academic)
POSTGRES_PASSWORD
POSTGRES_PORT=5432 (порт бд)
PORT (порт на котором работает бэк)
```

## запуск через `Docker`
```
docker-compose up
```