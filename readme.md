# Регистрация/Авторизация

||Метод |Описание  |
|--|--|--|
|**post**|  /register|  Регистрация нового пользователя|
|**post**|  /login| Авторизация 
 
### /register
#### Пример запроса

#### Ответ
{
"response": {
"count": 690,
"items": [{
"id": 172823,
"first_name": "Andrey",
"last_name": "Melnik",
"domain": "a.melnik",
"city": {
"id": 2,
"title": "Sankt-Peterburg"
},
"online": 0
}, {
"id": 66559,
"first_name": "Andrey",
"last_name": "Mima",
"domain": "amima",
"city": {
"id": 2,
"title": "Sankt-Peterburg"
},
"online": 1
}, {
"id": 15915916,
"first_name": "Andrey",
"last_name": "Minchukov",
"domain": "starr",
"city": {
"id": 244,
"title": "Vitebsk"
},
"online": 0
}]
}
}
#### Коды ошибок

### /login
#### Пример запроса

#### Ответ

#### Коды ошибок

# Работа с документом
||Метод |Описание  |
|--|--|--|
|**post**|  /upload| Загрузка документа для заверение|
|**post**|  /check| Проверка документа на валидность 

### /upload
#### Пример запроса

#### Ответ

#### Коды ошибок

### /check
#### Пример запроса

#### Ответ

#### Коды ошибок
