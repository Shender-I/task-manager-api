# To-Do List REST API (Java/Spring Boot)

Простое REST API для управления задачами, созданное с использованием Spring Boot.

## Функционал
- **GET /tasks** — получить все задачи
- **GET /tasks/{id}** — получить задачу по ID
- **POST /tasks** — создать новую задачу
- **PUT /tasks/{id}** — обновить задачу
- **DELETE /tasks/{id}** — удалить задачу

## Установка
1. Клонируйте репозиторий:
git clone <ваш-репозиторий>
cd todo-api

text

Свернуть

Перенос

Копировать
2. Сборка и запуск:
mvn spring-boot:run

text

Свернуть

Перенос

Копировать

## Примеры использования
### Создать задачу
```bash
curl -X POST http://localhost:8080/tasks -H "Content-Type: application/json" -d "{\"title\": \"Купить продукты\", \"description\": \"Молоко, хлеб, яйца\", \"completed\": false}"
Получить все задачи
bash

Свернуть

Перенос

Копировать
curl http://localhost:8080/tasks
Технологии
Java 17
Spring Boot 3.2.3
Maven
Лицензия
MIT