# Инструкция по командам Git

## Настройка Git

Для начала работы с Git необходимо настроить его:

1. Установить Git на компьютер.
2. Открыть терминал или командную строку.
3. Настроить имя пользователя и адрес электронной почты:


git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"


## Создание репозитория

Для создания нового репозитория нужно выполнить следующие команды:

1. Создать папку для проекта.
2. Открыть терминал или командную строку в этой папке.
3. Инициализировать репозиторий:


git init


## Работа с файлами

После создания репозитория можно начать работу с файлами:

1. Создать новый файл или изменить существующий.
2. Добавить файл в индекс:


git add <filename>


3. Закоммитить изменения:


git commit -m "Commit message"


## Работа с ветками

Ветки позволяют работать над разными версиями проекта одновременно.

1. Создать новую ветку:


git branch <branchname>


2. Переключиться на другую ветку:


git checkout <branchname>


3. Слияние веток:


git merge <branchname>


## Работа с удаленным репозиторием

Git позволяет работать с удаленными репозиториями, например, на GitHub.

1. Добавить удаленный репозиторий:


git remote add origin <remote repository URL>


2. Отправить изменения на удаленный репозиторий:


git push origin <branchname>


3. Получить изменения с удаленного репозитория:


git pull origin <branchname>


## Дополнительные команды

Некоторые дополнительные команды Git:

- Просмотреть историю коммитов:


git log


- Отменить последний коммит:


git reset HEAD~1


- Отменить изменения в файле:


git checkout -- <filename>
