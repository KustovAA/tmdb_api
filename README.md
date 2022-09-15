# TMDB API
Библиотека, для работы с API сервиса [themoviedb.org](https://www.themoviedb.org/).

### tmbd_helpers.py
Файл со вспомогательными функциями для работы с api
* ```make_tmdb_api_request``` - функция для запроса к api сервиса themoviedb.
* ```load_json_data_from_url``` - функция для выполнения http запроса.
* ```get_user_api_key``` - функция для получения ключа пользователя для api сервиса themoviedb.

### hello_api_TMDB.py
Код выводит в консоль информацию о бюджете фильма с id 215.

### make_own_db.py
Код запрашивает информацию о 1000 фильмах и сохраняющий полученные данные в файл MyFilmDB.json.

### find_similar.py
Код по названию ищет фильм в локальной базе данных и показывает все фильмы из базы, отсортированные по тому, на сколько они похожи на фильм, введенный пользователем, по жанру, бюджету, языку оригинала, коллекции.

### search_in_db.py
Код по названию ищет фильм в локальной базе данных и показывает список фильмов с похожими названиями.

### own_db_helpers.py
Код для получения содержимого локальной базы данных.
