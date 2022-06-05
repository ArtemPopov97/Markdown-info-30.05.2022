# Инструкция по работе с git

## что такое git?
Git одна из реализаций распределённых систем контроля версий ,*Git* на данный момент является самой популярной реализацией. Самой популярной реализацией *Git* является [GitHub](https://github.com)
## Подготовка репозитория


Для того чтобы создать репозиторий используется команда *Git init*. Для этого необходимо написать в терминале в папке будущего репозитория *Git init*

## Создания "сохранений"

### Добавление файла к коммиту

Для добавления файла к коммиту используется команда * git add* / Пишется она следующим образом *git add<имя файла>* в терминале в папке с созданным репозиторием.

### Создания коммита 
Для создания нового "сохранения" используется команда *git init*. Используется она следующим способом: в терминале в с папкой -репозиторием пишется *git commit -m <сообщение к коммиту >*. Сообщение к коммиту писать **обязательно**!!!

## Журнал изменений
Для просмотра журнала изменений используется команда изменений команда *git log*. Для этого в терминале в папке с рипозиторием достаточно написать *git log*

## Перемищение между коммитами
Для перемещения между сохранениями используется команда *git checkout*. Для того, чтобы переместится на указанный коммит в терминале в папке с репозиторием пишем *git checkout <номер коммита>*. ** Номмер коммита** берется из журнала изменений ,о котором сказанно выше. После перемищенияна указанный коммит мы попадаем в состояние **detached head*. Чтобы вернутся к обычной работе , необходимо написать *git checkout master*.

## Ветки в git

## Слияние веток и разешение конфликтов

## Удаление веток