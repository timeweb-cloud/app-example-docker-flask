![Docker Logo](https://st.timeweb.com/cloud-static/apps-logo/docker.svg)

# Dockerfile + Flask

Пример приложения Flask, которое можно развернуть в **Timeweb Cloud Apps** с помощью Dockerfile без настройки.

:tada: [Демо]()

:rocket: [Создать свой Apps](https://timeweb.cloud/my/apps/create)

:books: [Документация Timeweb Cloud Apps](https://timeweb.cloud/docs/apps)

## <a name="dev"></a>Локальный запуск проекта

```bash
# сборка docker образа
docker build -t twc-dockerfile-flask-app:latest .

# запуск контейнера на порту 3478
docker run -d -p 3478:3478 twc-dockerfile-flask-app
```
