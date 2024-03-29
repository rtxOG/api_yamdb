Проект YaMDb собирает отзывы пользователей на произведения. Сами произведения в YaMDb не хранятся, здесь нельзя посмотреть фильм или послушать музыку.
Произведения делятся на категории, такие как «Книги», «Фильмы», «Музыка». Например, в категории «Книги» могут быть произведения «Винни-Пух и все-все-все» и «Марсианские хроники», а в категории «Музыка» — песня «Давеча» группы «Жуки» и вторая сюита Баха. Список категорий может быть расширен (например, можно добавить категорию «изобразительное искусство» или «Ювелирка»).
Произведению может быть присвоен жанр из списка предустановленных (например, «Сказка», «Рок» или «Артхаус»).
Добавлять произведения, категории и жанры может только администратор.
Благодарные или возмущённые пользователи оставляют к произведениям текстовые отзывы и ставят произведению оценку в диапазоне от одного до десяти (целое число); из пользовательских оценок формируется усреднённая оценка произведения — рейтинг (целое число). На одно произведение пользователь может оставить только один отзыв.
Пользователи могут оставлять комментарии к отзывам.
Добавлять отзывы, комментарии и ставить оценки могут только аутентифицированные пользователи.


Стек технологий использованный в проекте:
```
Python
Django
Django REST Framework
REST API
SQLite
Аутентификация по JWT-токену
```
# Как запустить проект
```
1. Клонирование репозитория 
git clone https://github.com/Reznikov89/api_yamdb.git

2.Установить виртуальное окружение 
python -m venv venv

3. Активировать виртуальное окружение 
source venv/Scripts/activate

4. Установить зависимости
pip install -r requirements.txt

5. Выполнить миграции 
python manage.py migrate

6. Запустить проект 
python manage.py runserver
```

## Авторы

- 1й разработчик Андрей Виноградов(https://github.com/AVinAnd)
- 2й разработчик Семен Черняев (https://github.com/rtxOG)
- 3й разработчик Александр Резников (https://github.com/Reznikov89)
