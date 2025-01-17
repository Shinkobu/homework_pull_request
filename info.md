# Инструкция по работе с GIT

Картинка:

![error](car.png)

## Начало работы с репозиторием
> git init

* создаёт локальный репозиторий

Если не было задано имя пользователя 
> git config --global user.name "name"
> git config --global user.email "email"

## Добавление файлов в репозиторий
>git add file_name

Добавляет файл в репозиторий
>git commit -m "message"

Фиксирует все файлы добавленные для отслеживания

## Отслеживание состояния репозитория
> git status

показывает измененённые файлы и файлы готовые для комита
> git log

для визуализации нужно добавлять тег
> git log --graph

показывает все комиты
>git diff

показывает разницу между текущей версией и зафиксированной

## Переход между комитами
> git checkout comit_code

Переходит к комиту с кодом
> git checkout master

Вернуться к актуальному состоянию

## Справка
Вызвать справку можно с помощью тега --help
> пример git add --help

Пример ссылки:

  [GeekBrains](https://gb.ru/ "Переходи на Gb")

Удачи!

## Ветки в GIT

Чтобы посмотреть все ветки
>git branch

Для создания ветки branch_name
>git branch branch_name

Переместится к ветке branch_name
>git checkout branch_name

## Удаление веток

Удалить ветку branch_name можно командой
>git branch -d branch_name

Удалить ветку branch_name игнорируя все ошибки
>git branch -D branch_name

## Слияние веток и решение конфликтов
Команда для выкачивания информации из ветки branch_name в текущую ветку
>git merge branch_name

Для того, чтобы решить мердж конфликт нужно убрать лишние строки и отредактировать текст

## Справка
Чтобы вызвать справку для команды нужно использовать тег 
>--help

Примеры:
>git add--help
>git commit--help
>git branch--help

# Александр Пушкин — Зимнее утро

Мороз и солнце; день чудесный! 

Еще ты дремлешь, друг прелестный —

Пора, красавица, проснись:

Открой сомкнуты негой взоры

Пора, красавица, проснись:

Звездою севера явись!

## Работа с удалённым репозиторием
Клонировать удалённый репозиторий в новую папку
> Clone
Загрузить обновлённый код в удалённый репозиторий
> Push
Загрузить обновлённый код из удалённого репозитория + merge
> Pull
Привязать удалённый репозиторий к локальному
> Remote