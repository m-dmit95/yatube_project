# yatube_project
Социальная сеть для блогеров.

## Описание

В данном проекте можно публиковать записи в блоге, и читать блоги других авторов.

## Технологии

- Python 3.9
- Django 2.2.19

## Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

``` bash
$ git clone https://github.com/m-dmit95/api_final_yatube.git
$ cd api_final_yatube
```

Cоздать и активировать виртуальное окружение:

``` bash
python3 -m venv env
source env/bin/activate
```

Установить зависимости из файла `requirements.txt`:

``` bash
python3 -m pip install --upgrade pip
pip install -r requirements.txt
```

Выполнить миграции:

``` bash
python3 manage.py migrate
```

Запустить проект:

``` bash
python3 manage.py runserver
```

Проект буден доступен по адресу *http://127.0.0.1:8000/*
