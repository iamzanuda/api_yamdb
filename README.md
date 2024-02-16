# Yatube

## Сервис собирает отзывы на произведения различных категорий (например: книги, песни, фильмы). Произведению может быть присвоен жанр. Каждое произведение получает рейтинг на основе оценок пользователей (от 1 до 10).

### Авторы:
- Игорь Клементьев
- Yaroslav Baramykov
- Арина Пестова

### Технологии:
- Python 3.9
- Django 3.2
- Django REST framework 3.12
- библиотека Simple JWT

С помощью этого проекта можно:
* Читать отзывы на произведения различных категорий и жанров, а также ставить им оценки
* Добавлять, изменять и удалять собственные отзывы
* Оставлять комментарии к отзывам


#### Документация доступна после запуска сервера по адресу:
```
http://localhost:8000/redoc/
```
### Как запустить проект:

Клонировать репозиторий и перейти в него в командной строке:

```
git clone git@github.com:pestovaarina/api_yamdb.git
```

```
cd api_yamdb
```

Cоздать и активировать виртуальное окружение:

```
python -m venv venv
```

```
source venv/Scripts/activate
```

Установить зависимости из файла requirements.txt:

```
python -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Создать миграции:

```
python manage.py makemigrations reviews
```

Выполнить миграции:

```
python3 manage.py migrate
```


Запустить проект:

```
python3 manage.py runserver
```
