# GB_Git_Homework

# Инструкция для работы с Git и удалёнными репозиториями

## Что такое Git?
Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.
## Подготовка репозитория
Для создание репозитория необходимо выполнить команду *git init*  в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

## Создание коммитов

### Git add
Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*

### Просмотр состояния репозитория
Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

### Создание коммитов
Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

## Перемещение между сохранениями
Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с пепозиторием следующим образом: *git checkout <номер коммита>*

## Журнал изменений
Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием

## Ветки в Git

### Создание ветки

Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*

## Слияние веток

Для того чтобы дабавить ветку в текущую ветку используется команда *git merge <name branch>*

## Удаление веток
Для удаления ветки ввести команду "git branch -d 'name branch'"

## Выделение текста
Чтобы выделить текст курсивом необходимо обрамить его звездочками (*) или знаком подчеркивания (_). 
*Пример*

Чтобы выделить текст полужирным шрифотом необходимо обрамить его звездочками (**) или знаком подчеркивания (__). 
**Пример**

Чтобы выделить текст и полужирным шрифотом и курсивом необходимо обрамить его звездочками (**) а в конце знаком подчеркивания (__). 
_**Пример**_

## Списки

Ненумерованные пункты списка выделяются (*).

* Пример 1
* Пример 2

Нумерованные пункты списка выделяются ( <номер пункта>. )

1. Пример 1
2. Пример 2

## Картинки

Чтобы вставить изображение:

![picture](GB.png)

## Цитаты

Для обозначения цитат в языке Markdown используется знак «больше» («>»). Его можно вставлять как перед каждой строкой цитаты, так и только перед первой строкой параграфа. Также синтаксис Markdown позволяет создавать вложенные цитаты (цитаты внутри цитат). Для их разметки используются дополнительные уровни знаков цитирования («>»). Цитаты в Markdown могут содержать всевозможные элементы разметки. Цитаты в языке Markdown выглядят следующим образом:

>Это пример цитаты,
>в которой перед каждой строкой
>ставится угловая скобка.

>Это пример цитаты,
в которой угловая скобка
ставится только перед началом нового параграфа.
>Второй параграф.

Вложение цитаты в цитату выглядит следующим образом:
> Первый уровень цитирования
>> Второй уровень цитирования
>>> Третий уровень цитирования
>
>Первый уровень цитирования

***Уровень цитирования не может превышать 15-й.***

## Блоки кода

Отформатированные блоки кода используются в случае необходимости процитировать исходный код программ или разметки. Для создания блока кода в языке Markdown необходимо каждую строку параграфа начинать с отступа, состоящего из четырех пробелов или одного символа табуляции. Блок кода продолжается до тех пор, пока не встретится строка без отступа (или конец текста). Внутри блока кода амперсанды («&») и угловые скобки («<» и «>») автоматически преобразуются в элементы HTML разметки. Кроме того, следует отметить, что внутри блоков кода обычный синтаксис Markdown не обрабатывается. Блок кода в Markdown выглядит следующим образом:

Это обычный параграф:
  
    Это блок кода

## Горизонтальные линии (разделители)

Для того чтобы создать горизонтальную линию с использованием синтаксиса языка Markdown, необходимо поместить три (или более)дефиса или звездочки на отдельной строке текста. Между ними возможно располагать пробелы. Горизонтальные линии в Markdown выглядят следующим образом:

Первая часть текста, который необходимо разделить
***
Вторая часть текста, который необходимо разделить
Или

Первая часть текста, который необходимо разделить

---

Вторая часть текста, который необходимо разделить

## Дополнительные элементы

### Обратный слеш

Обратный слесш может употребляться в Markdown перед специальными символами для того, чтобы они воспринимались в их буквальном (а не служебном) значении. Полный список данных символов приводится ниже:

«\» - слеш;

«`» - обратный апостроф;

«*» - звездочка;

«_» - символ подчеркивания;

«{}» - фигурные скобки;

«[]» - квадратные скобки;

«()» - круглые скобки;

«#» - символ решетки;

«+» - плюс;

«-» - минус (дефис);

«.» – точка;

«!» - восклицательный знак.

### Автоматические ссылки

Markdown поддерживает упрощённый порядок автоматического создания ссылок для URL-адресов и адресов электронной почты. Для этого достаточно поместить URL-адрес или почтовый адрес в угловые скобки, и Markdown сделает его гиперссылкой. В отличие от вышеописанных стилей, в данном случае сам же URL-адрес или почтовый адрес становится и текстом гиперссылки. Автоматические ссылки на адреса электронной почты работают аналогично. Автоматические ссылки в языке Markdown выглядят следующим образом

<http://conflict.com/> - **адрес изменен для создания конфликта**

Автоматическая ссылка на адрес электронной почты в Markdown выглядит следующим образом

<conflict@example.com> - **адрес изменен для создания конфликта**


# Работа с удаленными репозиториями

## Работа с готовыми репозиториями

Для того, чтобы скачать репозиторий с серивиза Github и сделать его локальным на данном компьютере используется команда
git clone <ссылка на репозиторий>

Поменять местотположение работы VSC используется команда cd <имя репозитория>

## Выгрузка репозитория

Чтобы выгрузить собственный репозиторий требуется регистрация на Github

При создании собственного репозитория Git hub предоставляет возможные команды

__Создание нового репозитория__

* git branch -M main
* git remote add origin https://github.com/vnadvornyak/dz3.git
* git push -u origin main

__Работа с готовым репозиторием__ 

* git remote add origin https://github.com/vnadvornyak/dz3.git
* git branch -M main
* git push -u origin main

Компанда push выгружает действующий репозиторий на сайт