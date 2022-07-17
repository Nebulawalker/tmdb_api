# tmdb_api
Упражнение на чтение кода. Фильмы с TMDB.

С помощью следующих скриптов можно скачать базу данных фильмов на свой компьютер. Искать в этой базе фильмы по ключевому слову. Получать рекомендации.

Чтобы воспользоваться скриптами необходимо пройти регистацию на сайте: https://www.themoviedb.org
api key можно получить по ссылке: https://www.themoviedb.org/settings/api/request

## Скрипт make_own_db.py
Создает локальную базу данных фильмов в файле ```MyFilmDB.json``` в каталоге проекта.
Запуск:
```python make_own_db.py```

Потребуется ввести Ваш api key сервиса TMDB.

## own_db_helpers.py
Содержит функцию для загрузки данных из локальной базы данных.

## Скрипт search_in_db.py
Осуществляет поиск фильмов в локальной базе данных* по ключевому слову и выводит список фильмов в консоль.
Запуск:
```python search_in_db.py```

Необходимо указать имя файла с локальной базой: ```MyFilmDB.json```
___
*перед использованием необходимо создать локальную базу данных с помощью скрипта ```make_own_db.py```

## hello_api_TMDB.py
Выводит бюджет фильма с id 215.
Запуск:
```python hello_api_TMDB.py```
Потребуется ввести Ваш api key сервиса TMDB.

## Скрипт find_similar.py
Выводит 8 рекомендаций по названию фильма.
Название фильма должно быть точным. 

## Скрипт tmdb_helpers.py
Содержит набор впомогательных функций для работы с api сервиса https://www.themoviedb.org/. 
- Для проверки api key
- Для выполнения запросов к api https://www.themoviedb.org/
- Для выгрузки данных в формате JSON.

## Лицензия

This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

In jurisdictions that recognize copyright laws, the author or authors
of this software dedicate any and all copyright interest in the
software to the public domain. We make this dedication for the benefit
of the public at large and to the detriment of our heirs and
successors. We intend this dedication to be an overt act of
relinquishment in perpetuity of all present and future rights to this
software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to <http://unlicense.org>
