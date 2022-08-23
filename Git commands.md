# Git commands

## Initialization
Инициализирует новый репозиторий (папка в которой лежат файлы для отслеживания):

    git init


## Status 
Показывает текущий статус (что удалено, изменено и т.д.):

    git status

## Add
После сохранения изменений добавляет новую версию для отслеживания. После добавления нужно делать commit с описанием изменений:

    git add

## Commit


    git commit

    git commit -m

    git commit -a

    git commit -am

## Difference
Показывает разницу между текущим файлом и *последним по времени* коммитом.

    git diff 

Показывает разницу между *любыми выбранными* коммитами 12345a и 12345b. Порядок важен - поазывает, что изменилось в первом с сравнении со вторым.

    git diff 12345a 12345b

## Log

    git log


    git log --oneline


    git log --all


    git log --oneline --all

## Checkout

    git checkout

    git checkout master


