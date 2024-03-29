
# Инструкция для работы с Git и удалёнными репозиториями
![pam pam](gitSomaliProgrammers.jpg)
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

Для того чтобы дабавить ветку в текущую ветку используется команда *git merge  <name branch>*

## Удаление веток
Для удаления ветки ввести команду "git branch -d 'name branch'"

## Для создание ветки и сразу перейти на неё нужно ввести команду **git checkout -b**
## Визуализация всех веток
Ключ -graf в связке с командой log позволяет отобразить коммиты в виде дерева.*git log --graph*
# Синтаксис языка Markdown
![paam](maxresdefault.jpg)
# #заголовок-выделение заголовков.
(Поддерживается 6 уровней).
= или - -подчёркиванием этими символами (не менее 3 подряд) выделяют заголовки первого ("=")и второго ("-") уровней.
** **Полужироное начертание** ** или _ __Полужирное начертание__ __
* *курсивное начертание* * или _ _курсивное начертание_ _
*** ***полужирное курсивное начертание*** ***
~~ ~~Зачёркнутый текст~~ ~~
* Строка-ненумерованные списки,символ"*" в начале строки.


git push

