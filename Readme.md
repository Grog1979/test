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

## удаление веток
Для удаления ветки ввести команду "git branch -d 'name branch'"

# Редактирование текста

## Выделение текста

Чтобы выделить текст курсивом необходимо обрамить его звездочками (*) или знаом нижнего подчеркивания (_). *Пример1* или _Пример2_

Чтобы выделить текст полужирным, необходимо обрамить его двойными звездочками (**). **Пример**

Альтернативные способы выделения текста жирным или курсивом нужны для того, чтобы могли совмещать оба этих способа. Например _текст может быть выделен курсивом и при этом быть **полужирным**_.

## Списки

тобы добавить ненумерованные списки, необходимо пункты выделить (*) или знаком +.
например:
* элемент 1
* элемент 2
* элемент 3
+ элемент 4

Чтобы добавить нумерованные списки, необходимо пункты пронумеровать.
например:

1. элемент 1
2. элемент 2
3. элемент 3

## Добавление изображений

Чтобы вставить изображение в текст, достатосно написать следующее:
![природа](nature.jpg)
![кошка](cat.jpg)
также необходимо создать файл gitignore для игнорирования git неизменяемых файлов

## Ссылки

## Работа с таблицами

## Цитаты

## заключение