# GB_Git_Homework

#  Инструкция для работы с Git и удалёнными репозиториями
**Что такое Git?**

Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.

**Подготовка репозитория**

Для создание репозитория необходимо выполнить команду git init в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

**Создание коммитов
Git add**

Для добавления измений в коммит используется команда git add. Чтобы использовать команду git add напишите git add <имя файла>

**Просмотр состояния репозитория**

Для того, чтобы посмотреть состояние репозитория используется команда git status. Для этого необходимо в папке с репозиторием написать git status, и Вы увидите были ли измения в файлах, или их не было.

**Создание коммитов**

Для того, чтобы создать коммит(сохранение) необходимо выполнить команду git commit. Выполняется она так: git commit -m "<сообщение к коммиту>. Все файлы для коммита должны быть ДОБАВЛЕНЫ и сообщение к коммиту писать ОБЯЗАТЕЛЬНО.

**Перемещение между сохранениями**

Для того, чтобы перемещаться между коммитами, используется команда git checkout. Используется она в папке с пепозиторием следующим образом: git checkout <номер коммита>

**Журнал изменений**

Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда git log. Для этого достаточно выполнить команду git log в папке с репозиторием

**Ветки в Git**

*Создание ветки*

Для того, чтобы создать ветку, используется команда git branch. Делается это следующим образом в папке с репозиторием: git branch <название новой ветки>

*Слияние веток*

Для того чтобы дабавить ветку в текущую ветку используется команда git merge

*Удаление веток*

Для удаления ветки ввести команду "git branch -d 'name branch'"

*Работа с удаленным репозиторием*

1. Создать аккаунт на сервисе Github
2. Создать локальный репозиторий
3. "Подружить" локальный и удаленный репозиторий, Github подскажет как.
4. Отправить коммандой Git push локальный репозиторий в удаленный на сервис Github. При этом, возможна, авторизация на удаленном репозитории
5. Актуальное сохранение удаленного репозитория можно вытянуть в локальный репозиторий при помощи комманды pull
6. Делаем fork интересующего нас репозитория на сервисе Giyhub 
7. Делаем git clone для этого репозитория
8. Создаем ветку с предлагаемыми изменениями локально, перед этим меняем директорию в папке при помощи комманды cd
9. Отправляем эти изменения на свой аккаунткомандой push на сервис Github
10. На сервисе Github появляется возможность отправит репозиторий с веткой наших изменений пользователю репозитория при помощи команды pull request

