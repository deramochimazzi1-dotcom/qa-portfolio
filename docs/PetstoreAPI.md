# Проект: Тестирование Petstore REST API

## Описание проекта
Проект выполнен в Postman с использованием открытого API [Swagger Petstore](https://petstore.swagger.io/).  
Цель — продемонстрировать навыки тестирования REST API: создание, получение, обновление и удаление данных о питомцах.  

## Используемые инструменты
- **Postman** — для отправки запросов и анализа ответов.  
- **JSON** — формат запросов и ответов.  
- **Swagger** — документация к API.  

## Что было протестировано
- GET /pet/{petId} — получение информации о питомце  
- POST /pet — добавление нового питомца  
- PUT /pet — обновление данных о питомце  
- DELETE /pet/{petId} — удаление питомца  

## Результаты
- Все основные эндпоинты проверены.  
- Реализованы тесты на позитивные и негативные сценарии.  
- Проверены коды ответов (200, 400, 404, 500).  
- Настроены pre-request и test-скрипты.  

## Файлы проекта

<a href="files/petStore.postman_collection.json" download class="download-btn">
 Скачать коллекцию Postman
</a>

## Дополнительно
- [Документация Swagger Petstore](https://petstore.swagger.io/)


[files/petStore.postman_collection.json]: files/petStore.postman_collection.json