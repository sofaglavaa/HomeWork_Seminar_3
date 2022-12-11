# Инструкция для работы с Git и удалёнными репозиториями

## Что такое Git?
Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.

## Подготовка репозитория
Для создание репозитория необходимо выполнить команду **git init**  в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

---
## Создание коммитов

* ### Git add
Для добавления измений в коммит используется команда **git add**. Чтобы использовать команду **git add** напишите *git add <имя файла>*

### Просмотр состояния репозитория
Для того, чтобы посмотреть состояние репозитория используется команда **git status**. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

* ### Создание коммитов
Для того, чтобы создать коммит(сохранение) необходимо выполнить команду **git commit**. Выполняется она так: *git commit -m "<сообщение к коммиту>*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

* ### Перемещение между сохранениями
Для того, чтобы перемещаться между коммитами, используется команда **git checkout**. Используется она в папке с пепозиторием следующим образом: *git checkout <номер коммита>*

* ### Журнал изменений
Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда **git log**. Для этого достаточно выполнить команду *git log* в папке с репозиторием

---
## Ветки в Git

* ### Создание ветки

Для того, чтобы создать ветку, используется команда **git branch**. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*

* ### Слияние веток

Для того чтобы дабавить ветку в текущую ветку используется команда **git merge <name branch>**

* ### Удаление веток
Для удаления ветки ввести команду **"git branch -d 'name branch'"**

---
## Добавление картинок
Для того, чтобы добавить **картинку**, надо:
![картинка](https://s1.1zoom.ru/big3/984/Canada_Parks_Lake_Mountains_Forests_Scenery_Rocky_567540_3840x2400.jpg)
![картинка](https://yandex-images.clstorage.net/5om61vM30/9937bcI0c9/5DHzIbDPmjRCYIfM6DDfkA978Ze-27CFnJapFsZdqUVFfgO-GezJxJC2jKVXUMYCbYLaRxSeauh3MG8NyDgOafFktG30hYdrEiedmOAz2pISJrKGooG02IbU9UzXVaQdQ3oV7UH_wZfQ_9OhOj6we0nqpnFouBOQbWc0W5R0Ri7nD9hgj8rbNFJU4_DbOdedJyLVs5-yoO-dtd1JyBmLUh4QaehE96qj-eeZ_gAAs3xZz69URK4pklhcDlGQQg8f1jjJA6rT5RNoQ-TQzCjthQ8W84upoZX5nqTucdA3rEo9M0nCSOCCnuTVl-cRDZ98YvKjUWamDLFFSSxeoGkaFd8X8yij3uMLRV_z480a0YM1J-Wqo466-7i4xWroJYVDAQ9k_07hlKft_pfaMDGISVjEu0lqqwqqc3EwWJlaHR7ZAvEmtdHhMEhpxsbuCOy4BhDMkbOMl9-zl95T3yizZgstcdpKyZ-B-uiI1AotnH1O0J9obJ4Jm3h-HViyQRgP9xLuBLPQ-AlwZPzW7C7YhCQy7pqTmq7_ub78Y-YbhGkBLWXvX8iRlcHNvfcPKaFMXMCZSVWaHLR7VTxHvH0MLOgV4xWu9f0BdXrl3-0E2J4iIdOhrY6A2Lyf3HLmIb1lFwVH9V3fj4Lv4J7HFRSIWVvFvktWqz-3bkIiTYlDOBDZCOUPjfXnDUFW4PzjLNWHAgzOgqKRvtKZgsZr5BSjSBcLX-Fd252--96U8TMRnmhgw4RhUK4jl1ZzEHK4QgEP6jjuB6jF1hVHScrd8xDLhTsT0IScp4PwgaLEe8Q9i2gWH1HOfOGpme3jiP0nK6BOQtuxa0mrE7VaUQhYgk4aNN8y8y2X_tcBbnbY4-IvzZ8cONKmmpu46o-C3nnCJ69EBARmx2vujrPg17fEKwK3Ul39vWB0sRSzfkMfT5d2JTrhM_8zkezHFEJfzufAGc6yBy_eh6aer8q-qNZF3Qg)

## Добавление ссылки
Для того, чтобы добавить ссылку надо:
[Работка с языком](https://lifehacker.ru/chto-takoe-markdown/)

## Добавление цитат
Для того, чтобы добавить **цитату** надо:

* Чтобы добавить одиночную **цитату**, надо поставить знак ">":
>Не относитесь к жизни сильно серьёзно, всё равно вам из неё живым не выбраться

* Чтобы поставить *цитату с цитатой* надо поставить ">>":
>Не относитесь к жизни сильно серьёзно, всё равно вам из неё живым не выбраться
>>>Падает тот, кто бежит. Тот, кто ползет, не падает.
---
## Добавление списков

** Нумерованные
1. Перый
2. Второй
3. Третий

** Ненумерованные
+ Перый
+ Второй
+ Третий

** Вариант 2
- Перый
- Второй
- Третий

** Вариант 3
* Перый
* Второй
* Третий
