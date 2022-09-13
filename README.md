# TMDB API
Библиотека, для работы с API сервиса [themoviedb.org](https://www.themoviedb.org/).

### tmbd_helpers.py
Файл со вспомогательными функциями для работы с api
* ```make_tmdb_api_request``` - функция для запроса к api
* ```load_json_data_from_url``` - функция для выполнения http запроса
* ```get_user_api_key``` - функция для получения ключа для api пользователя

### hello_api_TMDB.py
Файл для запуска из консоли, пользователь вводит api ключ, в случае успеха получает информацию о бюджете фильма с id 215

### make_own_db.py
Файл содержит код, запрашивающий информацию о 1000 фильмах и сохраняющий полученные данные в файл MyFilmDB.json

### find_similar.py
Файл содержит код, который по названию ищет фильм в локальной базе данных и показывает список похожих фильмов по параметрам

### search_in_db.py
Файл содержит код, который по названию ищет фильм в локальной базе данных и показывает список фильмов с похожими названиями

### own_db_helpers.py
Файл содержит функцию получения содержимого локальной базы данных