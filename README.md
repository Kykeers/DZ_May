# DZ_May

## Команды

_1._ git init -- иициация комитов
_2._ git add 'имя файла' -- добавлить файл на контроль версий
_3._ git commit -m "описание коммита" -- описание комита
_4._ git version -- узнать текущую версию гита
_5._ git log -- посмотреть историю коммитов
_6._ git checkout -- возврат к желаемому коммиту
_7._ git diff -- разница между сохраненной и закоммиченой информацией
_8._ git status -- проверка статуса текущего коммита
_9._ git commit --amend -m "новое описание коммита" -- позволяет отредактировать текст последнего коммита
_10._ git log --graph -- визуализирование дерева коммитов
_11._ git chechout main^ -- поднятся на коммит выше по первому родителю
_12._ git chechout main^2 -- поднятся на коммит выше по второму родителю
_13._ git chechout main~ или git chechout main~N -- поднятся на N-коммитов выше 
_14._ git rebase -i ИМЯВЕТКИ1(или коммита1) ИМЯВЕТКИ2(или коммита2) -- переносит изменения ИМЯВЕТКИ1(или коммита1) в ИМЯВЕТКУ2(или коммит2)
_15._ git cheery-picking коммита1 коммита2 коммита3 -- переносит указанные коммиты, в указанном порядке в HEAD


## Совместная работа с удаленным репозиторием

* Переходим по ссылке(https://github.com/Kykeers/DZ_May) в репозиторий
* Можно нажать на зеленую кнопку **Code** и там скопировать ссылку -- это будет локальная версия удаленного репозитрия
* Чтобы создать свою вилку(для групповой работы с удаленным репозиторием), нужно нажать **Fork** и там **Create a new fork**
* В создавшемся, форк-репозитории, нажимаем на зеленую кнопку **Code** и там копируем ссылку
* Переходим в **VS**, открываем папку созданную для работы с форк-репозиторием и св консоли прописываем **git clone ССЫЛКАНАФОРК**
* Переходим в нужную рабочую папку -- **cd ИМЯПАПКИ**
* Вносим своим изменения в файлах, все сохраняем(**CTRL+S**) и делаем своей коммит -- **git commit -m "ТЕКСТКОММИТА"**
* Для отправки в **master** удаленного репозитория, прописываем в консоли -- **git push set-upstream origin АВТОПУША**
* Переходим, в браузере, в форк-репозитории и там нажимаем **Compare & pull request**, в новом окне нажимаем **Create pull request**