## Установка и запуск

Клонируйте репозиторий и перейдите в рабочую директорию

```
git clone https://github.com/Anafema-Forge1096/bewise-quiz-api-test.git
cd bewise-quiz-api-test
```

Запустите docker-compose:

```
docker-compose build
docker-compose up
```

## Документация

После запуска сервера документация доступна по адресу:

```
http://127.0.0.1:8000/docs
http://127.0.0.1:8000/redoc
```

или

```
http://0.0.0.0:8000/docs
http://0.0.0.0:8000/redoc
```

## Реализация

Для выполнения данной задачи был использован фреймворк FastAPI в комбинации с
alembic, SQLAlchemy, Pydantic, PostgreSQL(psycopg2-binary)

<P>База данных: <b>PostgreSQL</b> - для хранения вопросов для викторин</p>

**Пример POST-запроса:**
<br>
URL: `https://localhost/questions/bulk`
<br>
Request body: `{question_num: 100}`
<br>
Response: "Question Example"
