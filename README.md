# Pull request

1. Сделать clone/fork репозитория https://github.com/rover131/geekbrains
2. Создать новую ветку
3. Изменяем данные в README
4. Делаем комит
5. Пушим на гитхаб
6. В название реквеста указываем ФИО
7. Делаем скрин и прикладываем на платформу.

# Работа с GitHub

1. Создание аккаунта на Github.com 
2. Создать локальный репозиторий
3. "Подружить" ваш локальный и удаленный репозитории. Github при создании нового репозитория подскажет как это можно сделать).
4. Отправить (push) ваш локальный репозиторий в удаленный (на Git hub), при этом вам, возможно, нужно будет авторизоваться на удаленном репозитории.
5. Провести изменения "с другого компьютера".
6. Выкачать (pull) актуальное состояние из удаленного репозитория.


# create a new repository on the command line
echo "# -3" >> README.md

  git init
  
  git add README.md
  
  git commit -m "first commit"
  
  git branch -M main
  
  git remote add origin https://github.com/GainaOksana/-3.git
  
  git push -u origin main

# …or push an existing repository from the command line
git remote add origin https://github.com/GainaOksana/-3.git

  git branch -M main
  
  git push -u origin main

# …or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

git push - выгрузка изменений в Git Hub

## совместная работа 

1. Делаем форк (fork) интересующего нас репозитория.
2. Мы делаем git clone для нашей версии этого репозитория.
3. Создаем ветку с предлагаемыми изменениями.
4. Производим все изменения только в этой ветке.
5. Отправляем эти изменения на свой аккаунт (push).
6. В окне на Github появляется возможность отправить pull request.
