# Инструкцию по работе с Git, используя возможности Markdown.

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

### Просмотр различий между редактируемым файлом и коммитом
Чтобы посмотреть различие между редактируемым файлом и коммитом небоходимо выполнить команду *git diff*

### Перемещение между сохранениями
Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с пепозиторием следующим образом: *git checkout <номер коммита>*

### Журнал изменений
Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием

## Ветки в Git

### Создание ветки

Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*

### Слияние веток

Для того чтобы дабавить ветку в текущую ветку используется команда *git merge <name branch>*

### Удаление веток
Для удаления ветки ввести команду "git branch -d 'name branch'"

### Просмотр существующих сохранений (коммитов) с учетом создания новых веток
Чтобы посмотреть историю комитов с учетом созданных веток необходимо выполнить команду *git log --graph*

### Пометить файл не подлежащий сохраниению
Чтобы пометить файл не подлежащий сохранению необходимо в репозитории создать новый файл с названием *.gitignore*, после чего, в созданный файл добавить наименование файлов не подлежащих сохранению.

## Работа с текстом

### Выделение текста

Чтобы выделить текст курсивом, необходимо обрамить его звездочками (*) или знаком нижнего подчеркивания (_). Например, *вот так* или _вот так_.

Чтобы выделить текст полужирным, необходимо обрамить его двойными звездачками (**) или двойным знаком нижнего подчеркивания (__). Например, **вот так** или __вот так__

Альтернативные способы выделения текста жирным или курсивом нужны для того, чтобы мы могли совмещать оба этих способа. Например, 
_текст может быть выделен курсивом и при этом быть **полужирным**_.

### Списки

Чтобы добавить ненумерованные списки необходимо пункты выделить (*) или знаком (+). Например,
* Элемент 1
* Элемент 2
* Элемент 3
+ Элемент 4

Чтобы добавить нумерованные списки, необходимо пункты просто пронумеровать (1,2,3).
Например,
1. Элемент 1
2. Элемент 2
3. Элемент 3

### Работа с изображением

Чтобы вставить изображения в текст, достаточно написать следующее:
![Привет, это IT](IT.jpg)

### Ссылки 

Чтобы вставить ссылку в текст необходимо добавить  [пример](http://example.com/ "Необязательная подсказка")

### Таблици

Чтобы создать в тексте таблицу необходиом добавить (|) и (-)
Например,
| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

### Цитаты

Чтобы вставить цитату в текст необходимо добавить знак (>) Например, 
> Вот так

Чтобы вставить двух и более уровневую цитату в текст, необходимо добавить знак (>>) или (>>>).
Например,
> Первый уровень
>> Второй уровень
>>> Третий уровень 

Вношу изменения в файл

Изменения сделанные в GIT GUB

Семинар 2 - ДЗ 
Добавляю 4 ветки


<<<<<<< HEAD
Вношу отличающуюся информацию для конфликта 1
Вторая строка информация 



Вношу информацию для слияния с веткой номер 3 (third branch)
Вторая строка информации для слияния 


Вношу информацию для слияния ветки 4 с main
вторая строчка информации

