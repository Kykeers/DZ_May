# DZ_May

# GIT Руководство

## Начало работы

- _git init_ - инициализировать репозиторий
- _git version_ - проверка, что ГИТ и VS Code подружились
- _git config --global user.name "Name"_ - ввод имени пользователя
- _git config --global user.email "email"_ - ввод электронной почты

Можно установить любые расширения с помошью значка приложения (он находится слева)
![Это скрин, но я не указала путь и не добавила в отслеживаемые, тысячи извинений](2.jpg)

## Основные команды

- _git status_ - посмотреть статус репозитория
- _git add_ **имя файла** - начать отслеживать файл. Имя файла можно выбрать через клавишу _Tab_. Если нужно добавить несколько файлов, то указать их через пробел.
- _git commit -m "Сообщение"_ - добавить комментарий к коммиту
- _git commit -a - m "Сообщение"_ - сохранить коммит и добавить комментарий. "- a - m" можно заменить на "-am"

## Работа с коммитами

- _git log_ - показывает все коммиты в хронологическом порядке от самого последнего
- _git checkout "первые 4 символа ключа"_ - возвращает к определенному коммиту
- _git checkout_ **имя ветки** - возвращает к последнему коммиту в ветке
- _git reset HEAD~_ - удаление последнего коммита (но изменения, связанные с ним, останутся)
- _git reset --hard HEAD_ - удаление последнего коммита и изменений, с ним связанных.
- _git diff_ - показывает изменения между коммитами

## Работа с ветками

- _git branch_ - показывает все ветки
- _git branch_ **имя новой ветки** - создать новую ветку
- _git merge_ **имя ветки** - слияние веток
- _git branch -d_ **имя ветки** - удалить ветку
- _git log -graph_ - вывести дерево веток
- _git checkout -b_ **имя ветки** - создать ветку и сразу переключиться на него

## Работа с удаленным репозиториев

- _git clone_ - копирует из GitHub
- _cd имя папки_ - перемещение в конкретную папку
- _git push_ - выгрузить коммиты в Github
- _git pull_ - выгрузить коммиты из GitHub

## Другие комманды

- _clear_ - очищает терминал
- _Q_ - выход

## Заключение

![тут должна быть картинка с желчным пузырем, который сделал камни, но его нет](1.jpg)
Это основные команды, которые я знаю, их, конечно, больше, но я их пока не знаю. Многие другие команды представлены на сайте https://github.com/cyberspacedk/Git-commands
