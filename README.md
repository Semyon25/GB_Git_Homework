# GB_Git_Homework

# Что такое Git
Git  — распределённая система управления версиями. Проект был создан Линусом Торвальдсом для управления разработкой ядра Linux, первая версия выпущена 7 апреля 2005 года. На сегодняшний день его поддерживает Джунио Хамано.

# Подготовка репозитория
Для создания репозитория нужно открыть папку, в которой планируется создать репозиторий, в терминале и ввести команду *git init*

# Создание "сохранений"
Для создания "сохранения" нужно сначала добавить файл к "сохранению" путем введения команды *git add <имя файла>* (или *git add .*). Сохранение затем создается командой *git commit -m'<описание "сохранения">'.
Альтернативным способом является команда *git commit -a -m'<описание сохранения>'*

# Переключение между "сохранениями"
Для переключения между сохранениями используется команда *git checkout <первые четыре или более символов названия "сохранения">*

# Журнал изменений
Для просмотра журнала изменений используется команда *git log*
Для просмотра журнала с визуализацией нужно ввести команду *git log --graph*

# Ветки в Git
Для проcмотра списка веток в Git используется команда *git branch*
Для создания новых веток нужно ввести *git branch <имя ветки>*

# Слияние веток и разрешение конфликтов
Для слияния веток нужно сначала перейти в ветку, к которой планируется присоединение, с помощью команды *git checkout <имя ветки>*. Затем нужно ввести команду *git merge <имя ветки, которую нужно присоединить>*
В случае, если между данными в одних и тех же строках сливаемых веток есть расхождения, автоматическое слияние не пройдет и система предложит сделать выбор из четырех вариантов решений конфликта:
* оставить исходные данные
* принять входящие данные
* оставить исходные и принять входящие данные
* произвести сверку изменений

# Удаление веток
Для удаления ненужных веток используется команда *git branch -d <название ветки>*