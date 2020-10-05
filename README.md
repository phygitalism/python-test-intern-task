# Тестовое задание для Стажера  

Используя один из framework ([Flask](https://flask.palletsprojects.com/en/1.1.x/), [Django](https://www.djangoproject.com/), [FastApi](https://fastapi.tiangolo.com/))  
Создать Микросвервис:  
    Задача сервиса на запрос GET /api/meta/<path> вернуть список файлов с датой  
Пример ответа:  
```javascript  
{
    “data”:[
        {
            “name”: ”name”,
            “type”: “file”,
            “time”: “time”
        },
        {
            “name”: ”name”,
            “type”: “file”,
            “time”: “time”
        },
    ]
} 
```  
Корневая директория ставится в config.py  

## Плюс  
наличие Dockerfile  
наличие virtualenv  
использование poetry или аналогов  