# DZ_May

git **init**  — создание репозитория.

Команда clear стирает строки в терминале

Открыть терминал “ctrl + ~”

git **status** — узнать где находимся.

git **add** — добавить файл.
   git **add** (+ Tab) — возможность выбрать название файла.
   git **add .**  — добавить измененный файл ( “ . “ точка означает, что будут добавлены все файлы).

git **commit**  *-m* ‘’*сообщение*’’— зафиксировать изменение сообщением ( ‘‘-m’’ означает Message).
   git **commit**  *- - amend -m “*Сообщение*”* — возможность изменить коммит.

git **version** — узнать версию GIT.

git **log** — увидеть все коммиты .

Клавиша Q позволяет завершить команду git log.

git **checkout  36e4** — возвращение к коммиту ( “36e4” - первые символы коммита).
   git **checkout master** — возвращение к последнему коммиту (“master” ветка где находимся).
   git **checkout creatin**g  — перейти в ветку ‘’creating’’.

git **diff**  —  позволяет узнать разницу между сохраненным файлом и добавленным.

git **branch**  —  выводит все ветки, которые созданы.
   git **branch creating** — создать ветку “creating”.
   git **branch -d branch_name**  — удалить ветку ( “branch_name” название ветки), только в случаях, если информация в ветке внесена в ветку **master.**
   git **branch -D branch_name**  — удалить ветку полностью( “branch_name” название ветки).
   git **branch -M master**  —  позволяет выбрать главную ветку (в данном случае “master”).

git **merge** **branch_name**  —  слить указанную ветку с той в которой находишься ( “branch_name” название ветки).

git **remote add origin** *протокол*  — сделать привязку удаленного и локального репозитория (”remote” - определяет удаленный источник; “origin” - тип связи).

git **push** — отправить изменения в удаленный репозиторий с которой установлена связь.
   git **push -u origin** *master* — отправить изменения из локального в удаленный репозиторий. (“origin” - тип связи, “master” - ветка).

git **pull** — принять изменения из удаленного репозитория