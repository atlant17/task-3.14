## Создание веток и переключение между ними
---
Создадим две дополнительные ветки __Dev и Test__ (например, одна может пригодиться для процесса разработки, а другая — для запуска в тестирование). Введем команду _git branch "branch-name"_ дважды с разными аргументами: 

    git branch Dev  
    git branch Test

Ветки созданы, но мы по-прежнему работаем в master. Для переключения на другую нужно выполнить _git checkout "branch-name"_:

>git checkout Dev  

    Switched to branch ‘Dev’  
    Your branch is up to date with ‘origin/Dev’.

Внесем некоторые изменения в файл README.md и зафиксируем их, чтобы они отразились в ветке Dev:

>git add .
>git commit -m “dev readme changed”

    [Dev #####] dev readme changed  
    1 file changed, 2 insertions(+)

Если теперь отправить их на сервер, то можно убедиться в появившемся отличии веток

[ссылка](https://selectel.ru/blog/tutorials/git-setup-and-common-commands/) на официальный источник 

[Главное меню](./readme.md)