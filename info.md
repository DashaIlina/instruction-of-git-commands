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

> git add . or add --all

## Изменяем файл

Добавить комментарий к добавленным в индекс файлам:

> git commit -m "Some text"

Добавить комментарий к файлам с сообщением:

> git commit -am "сообщение"

Проверка изменений:

> git status

## Отслеживание состояния файла

Просмотр всех изменений:

> git log

Выйти из просмотров изменений и продолжить работу с репозиторием:

> Клавиша Q

Просмотр изменений еще не добавленных в индекс файла:

> git diff

Просмотр сохраненых отличий от предидущей версии:

> git diff --cached

## Переход по версиям

Перейти к определенной версии:

> git chekout commit_code (the first four digits of code)
the code of commit can be found through the log command/

Вернуться в последнюю версию и продолжить изменение:

> git checkout master

**Убрать отображение неиспользованных файлов:**

**создаем файл .gitignore и открываем его в репозитории и записываем все имена нежелательных файлов.**



Помощь:

> git {имя команды} --help

![pic](9a3e15.jpg)

## Работа с ветками

Команнда для вывода всех веток

> git branch

Создает ветку с именем name_branch

> git branch name_branch

> git checkout name_branch

> git branch -d name_branch

> git merge name_branch

