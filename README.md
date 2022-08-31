# Проект лабораторной работы по GIT!

* ## справка по всем командам
git help

* ## Добавим все файлы проекта в нам будующий commit
git add .

* ## Если хотим добавить конкретный файл то можно так
git add *<имя_файла>*

* ## Теперь создаем commit. Обязательно указываем комментарий.
**И не забываем про кавычки**

git commit -m "__<_комментарий_>__"

+ **Остальные комнады:**

* Просомтр истории: git log --oneline


git clone
git status

* абота с ветакми:
git branch
git branch -d
git branch -M <name> _ветка которая будет улетать на удалРепо_

?
git stash
?

*Передвинуть ветку на комит*
**git checkout -f <имя ветки> <имя комита>**

*Создать ветку и перейти к ней branch+checkot*
**git checkout -b <name>**

* 
git revert

* Просмотр изменений комитов/файлов ...
git diff <name> <name>

git merge

**Удаленый репозиторий под именем origin
git remote add origin https...

git fetch

* Отправка на удал. репо
git push

* Получить с репо. Кроме того мёрджит ту ветку с текущей!
git pull

git restore <file>

* Копирует коммит из одной ветки в другую

*Берёт изменения, вносимые одним коммитом, и пытается повторно применить их в виде нового коммита в текущей ветке*

git cherry-pick <ветка источник> <ветка приёмник>

pull request
1. fork проекта репозитория в репо
1. 1.2. clone на лок 
git clone http...
2. branch
git branch <name>
3. working
4. git commit
5. git push свою ветку в свой проект на репо
6. pull request в репо


![images](Снимок.png))