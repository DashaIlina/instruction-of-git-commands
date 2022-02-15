# Начало работы с репозиторием

Создаем репозиторий:

> git init

Если работаем впервые , задаем имя и почту:

> git config --global user.name some_name

> git config --global user.email some_email

# Основные команды

Присоединяем файл:

> git add file_name

Присоединяем все файлы в папке:

> git add. or add --all

## Изменяем файл

Добавить комментарий к изменениям:

> git commit -m "Some text"

Проверка изменений:

> git status

Просмотр всех изменений:

> git log

Просмотр отличий от предидущей версий:

> git diff