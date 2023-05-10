### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:syberflea/kittygram_backend.git
```

```
cd kittygram_backend
```

Cоздать и активировать виртуальное окружение:

```
python -m venv env
```

* Если у вас Linux/macOS

    ```
    source env/bin/activate
    ```

* Если у вас windows git bash

    ```
    source env/scripts/activate
    ```

```
python -m pip install --upgrade pip
```

Установить зависимости из файла requirements.txt:

```
pip install -r requirements.txt
```

Выполнить миграции:

```
python manage.py migrate
```

Запустить проект:

```
python manage.py runserver
```
