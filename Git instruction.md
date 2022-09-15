# Контроль версий GIT

## Инструкция по установке и настройке GIT и VSCode

**ПЛАН:**  
 Шаг1. Устанавливаем VSCode [https://code.visualstudio.com/download](https://code.visualstudio.com/download)  
 Шаг 2. Закрываем его  
 Шаг 3. Устаналиваем GIT [https://git-scm.com/book/ru/v2/Введение-Установка-Git](https://git-scm.com/book/ru/v2/%D0%92%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-%D0%A3%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B0-Git)  
 Шаг 4. Часто нужна перезагрузка - перезагружаемся  
 Работаем
 
 Просим вас вести конспекты на лекциях и семинарах.
 
 Преимущества конспектов:  
 - Задействуют механическую память, помогают запоминать материал во время лекции.  
 - При конспектировании повышается концентрация и внимание.  
 - Возможность выделить и запомнить главное из новой темы.
 
 Конспекты можно вести в любом удобном формате.
 
 В конце курса, мы все соберем и поделимся с группой.
 
 Так, ваш конспект и конспекты одногруппников позволят еще раз проработать тему и увидеть все важные моменты.
 
 В конце курса "Введение в контроль версий (лекции)", под уроком 3, будет вкладка для сдачи практического задания. Туда и нужно будет приложить ваш конспект по курсу.
 
 Этот пункт не обязательный, но очень желателен.

## Команды GIT

**git init**
>git init
>>позволяет установить git в папку с проектом делая из неё репозиторий.



**git add**
>git add <название файла>
>>позволяет добавить изменения файла в репозиторий для дальнейших действий с ним.


**git commit**
>git commit -a
>>совершит **коммит**, автоматически индексируя изменения в файлах проекта. При этом новые файлы индексироваться не будут. Удаление же файлов будет учтено.

>git commit -m "commit comment"
>>комментируем **коммит** прямо из командной строки вместо текстового редактора.

Попытка создать конфликт

для начала напишем текст в ветке мастер.
Затем в ветке GiCommand на месте ,где уже написан текст в ветке мастер, напишем еще немного текста.

всё получилось, были сохранены обе версии

![coflict](https://sun9-west.userapi.com/sun9-66/s/v1/ig2/Tvn28_VXfpjpTztUeyX-lAgW88Zadg2r8rkVn1Uivhkx9Oo9bKsyMuseHafcRFnW-hiGuyjvstkjLNiM9wdxAoZR.jpg?size=740x265&quality=96&type=album)

>git commit -am ''
>>Сохраняет файл как при соманде *git add* делая сразу коммит

**git diff**
>git diff
>>позволяет увидеть разницу между сохраненным файлом репозитория и программной среды.
>>
>>![Пример использования команды](git_diff.png)

**git log**
>git log
>>позволяет посмотреть журнал изменений.
![Пример использования команды](https://sun9-west.userapi.com/sun9-68/s/v1/ig2/RQ12UzuNUHDMP6iS0N_fPktL7RVRsTWPNwnbXedpK-bOCiUxifOBFeonQOe3H9YM3amBpCJ8bm1Ydwgt6ohtCsnN.jpg?size=503x592&quality=96&type=album)

>git log --graph
>>позволяет увидеть лог всех сохранений веток.
![Пример использования команды](https://sun9-east.userapi.com/sun9-41/s/v1/ig2/CCax3PkRojovDjTUkeiQwtzuS1v1xA9szy9IGlkMCp_eGOffZVmpg4LOV4kdfNVZTRYccp5yYxZWngFOmShu5qXW.jpg?size=505x598&quality=96&type=album)

**git branch**
>git branch
>>позволяет просмотреть ветки контроля версий.
>>
>>![Пример использования команды](https://sun9-west.userapi.com/sun9-38/s/v1/ig2/a6JQBOA4QsnFELFLv81ZiSVia1U0c_Sn-JeWQTrtpASuLsy-yz9HPYmdTconY6yHcXLcdShKV37aXJejH4F9WxL1.jpg?size=387x74&quality=96&type=album)

>git branch branch_name
>>позволяет удалить ветку.

>git branch -d branch_name
>>позволяет создать новую ветку.

**git checkout**
>git checkout branch_name
>>позволяет перемещаться между ветками контроля версий.
>>
>>![Пример использования команды](https://sun9-west.userapi.com/sun9-70/s/v1/ig2/bLcvxzeaLMikeD5ccpS4H2xwfLp1FG5Yp5sKGXpm6o4HorYp4ok7Niq_rXNCVPVdH3DNRnweXjJ2q_UmQyDcJ_dj.jpg?size=485x41&quality=96&type=album)

**git merge**
>git merge branch_name
>>позволяет делать слияние указанной ветки в текущую ветку.
>>
>>![Пример использования команды](git_merge.jpg)

**git status**
>git status
>>позволяет просмотреть статус репозитория с отслеживаемыми и неотслеживаемыми файлами.
>>
>>![Пример использования команды](git_status.png)

**clear**
>clear
>>очищает терминал.

**Более подробно о командах Git можно узнать [тут](https://github.com/cyberspacedk/Git-commands).**

## Инструкция по добавлению в игнор лист

- В репозитории появляются неотслеживаемые картинки. 

>>![Пример использования команды](git_status_ignore.png)

- Для того, что бы он игнорировал эти файлы их необходимо добавить в игнор лист git.

>>![Пример использования команды](added_ignore.png)

- После чего необходимо сохранить изменения для дальнейщей работы.

>>![Пример использования команды](commit_ignore.png)

## Работа в GitKraken

Управление репозиторием возмоно из сторонних программ, например как **GitKraken**. Данная программа позволяет отображать древо сохранений, в котором можно переходить из сохранения в сохранение быстрым нажатием, что очень удобно. Обладает встроенным терминалом с синтаксическими подсказками. Также есть встроенный редактор.
![Интерфейс GitKraken](https://sun1.userapi.com/sun1-90/s/v1/ig2/l-uHhYc-X7Lr3k7Fix1ws-Br2ivOwUgubt5Pd716R-cwCXVB6jB1tpcyJn0gVxBrLWZsYLWIqDcBml9WzA5WKsv_.jpg?size=461x808&quality=96&type=album)

В ГитКракен моно делать коммиты при помощи интерфейса без использования командной строки.
![Commit GitKraken](https://sun9-north.userapi.com/sun9-78/s/v1/ig2/Hwh43co8tWEaaad-RtYou4Jp1zVLU0bFvCDGhAPnYP7Kac_IoWVtP4ptq0L2_OogkEdsfpnl2lRDtp3qD0slnWW6.jpg?size=357x527&quality=96&type=album)
Наимаем на Commit changes to 1 file и получаем результат:
![tree commit](https://sun1.userapi.com/sun1-18/s/v1/ig2/hwDkleCfnaOfrbZCHL-CByW_nLQb72gbdDOx0vU-RqIzrmjZlSYdUa1GYdx30IiGVA88kHjcN43xcmw0ASZ4x5uw.jpg?size=499x152&quality=96&type=album)
Программа хорошая, но пробный период составляет 21 день, а покупать её нет острой необходимости.




