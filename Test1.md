# Инструкция для работы с Git и удалёнными репозиториями
## Что такое Git?
Git - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.
Подготовка репозитория
Для создание репозитория необходимо выполнить команду *git init*  в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка .git)

## Создание коммитов

Git add
Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*

Просмотр состояния репозитория
Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

Создание коммитов
Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

Перемещение между сохранениями
Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с пепозиторием следующим образом: *git checkout <номер коммита>*

Журнал изменений
Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием

Ветки в Git

Создание ветки

Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*

Слияние веток

Для того чтобы дабавить ветку в текущую ветку используется команда *git merge <name branch>*

Удаление веток
Для удаления ветки ввести команду "git branch -d 'name branch'"

## добавление картинок
Для того,чтобы добаваить **картинку**, надо:
![картинка](https://vsegda-pomnim.com/uploads/posts/2022-04/1651034819_20-vsegda-pomnim-com-p-kottedzh-u-morya-foto-20.jpg)
## добавление ссылок
для того, чтобы добавить ***ссылку***, надо:
[инструкция](https://doma-servis.ru/expert?utm_medium=cpc&utm_source=yandex.search&utm_campaign=russia_dom_kottedj_krasnodar&utm_content=t1&utm_term=%D0%BA%D1%83%D0%BF%D0%B8%D1%82%D1%8C%20%D0%B4%D0%BE%D0%BC%20%D0%B2%20%D0%BA%D1%80%D0%B0%D1%81%D0%BD%D0%BE%D0%B4%D0%B0%D1%80%D1%81%D0%BA%D0%BE%D0%BC%20%D0%BA%D1%80%D0%B0%D0%B5&_openstat=ZGlyZWN0LnlhbmRleC5ydTs4MDM1NTg2MzsxMzAyODgyNTk0Nzt5YW5kZXgucnU6cHJlbWl1bQ&yclid=12039778316154044415)

## добавление списков и цитат
* ненумерованные списки задаются тремя фигурами:

* первый
+ второй
- третий

Чтобы добавить *цитату* используем знак ">"

> Делаешь — не бойся, боишься — не делай.

Чтобы добавить *цитату в цитате*, надо:
> Делаешь — не бойся, боишься — не делай.
>> Лучше быть последним среди волков, чем первым среди шакалов.


![картинка2](https://www.bmwcartuning.com/wp-content/uploads/2017/11/BMW-F10-M5-with-Vossen-Wheels-5.jpg)

[ссылка](https://auto.ru/showcaptcha?cc=1&mt=AEB0153630B3DB152CA436673389361AE8CF9C3CDF419A08D499D6FA9E8DF06635DB&retpath=aHR0cHM6Ly9hdXRvLnJ1L3RhdGFyc3Rhbi9jYXJzL2Jtdy94NS91c2VkP3V0bV9zb3VyY2U9eWFuZGV4X2RpcmVjdCZ1dG1fbWVkaXVtPWRpcmVjdC5tb2RlbCZ1dG1fY2FtcGFpZ249azUwX2FsbHdlYl91c2VkX21vZGVsX3NlYXJjaF9rYXphbl80NjAtNTBfNzMwMzAwMjAmdXRtX2NvbnRlbnQ9Y2lkJTNBNzMwMzAwMjAlN0NnaWQlM0E0OTM5ODU2OTAyJTdDYWlkJTNBMTIyNzczOTI0MzElN0NwaCUzQTQxNDQ2NTA3MTkyJTdDcHQlM0FwcmVtaXVtJTdDcG4lM0ExJTdDc3JjJTNBbm9uZSU3Q3N0JTNBc2VhcmNoJTdDY2djaWQlM0EwJnV0bV90ZXJtPSVEMCVCMSVEMCVCQyVEMCVCMislRDElODU1KyVEMCVCRiVEMSU4MCVEMCVCRSVEMCVCNCVEMCVCMCVEMCVCNiVEMCVCMCZhZGp1c3RfdD1jbDRxdHR0X25zdzRpdDYmYWRqdXN0X2NhbXBhaWduPTczMDMwMDIwJmFkanVzdF9hZGdyb3VwPTQ5Mzk4NTY5MDImdHJhY2tlcl9saW1pdD0xMDAwMCZfb3BlbnN0YXQ9WkdseVpXTjBMbmxoYm1SbGVDNXlkVHMzTXpBek1EQXlNRHN4TWpJM056TTVNalF6TVR0NVlXNWtaWGd1Y25VNmNISmxiV2wxYlEmeWNsaWQ9OTkyMjc1MjY5MDIwMzkxODMzNSZjb29raWVzeW5jPXRydWU%2C_c00256971e1917fdb923828f0e4868b1&t=2/1670083812/71af14433e56f302b47fa5fa79a7fc92&u=1660fafe-6db83f39-f2a439fb-15b29eaf&s=6aa65dc39228757562e81ef5b886ee61)

>Не позволяй никому, никогда, заставлять тебя чувствовать, что ты не заслуживаешь того, что хочешь.

>>>Мы ходим на работу, которую ненавидим, чтобы купить вещи, которые нам не нужны.
Тайлер Дерден из к/ф “Бойцовский клуб“.

![картинка](https://vsegda-pomnim.com/uploads/posts/2022-04/1651045073_2-vsegda-pomnim-com-p-krasivii-dom-u-morya-foto-2.jpg

