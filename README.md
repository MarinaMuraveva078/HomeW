**git init** - Инициализация репозитория

**git add "file_name** - Добавить файлу с названием file_name версионность

**git add .** - Добавить всем файлам в папке версионность

**git reset .** - Убрать у всех файлов в папке версионность

**git reset "file_name"** - Удалить у файла с названием file_name версионность

**git commit -m "commit_massege"** - Упрощенный вариант ввода коммита

**git commit -am** - Если файл имеет состояние modified (т.е. был tracked ранее и мы его добавили с помощью git add), то можно пропустить этап с командой git add посредством использования данной команды

**git checkout "hash_number"** - Переместить на коммит с хэшем "hash_number" (для того, чтобы вернуться git checkout master/main)

**cd** - Переместиться внутрь папки

**cd ..** - Переместиться из папки

**mkdir** - Создать новую папку

**new-item** - Создать новый файл

**ls** - Просмотреть список файлов в папке

**git branch** - Проверить список сушествующих веток

**git branch branch_name** - Создать ветку с названием branch_name

**git checkout -b branch_name** - Создать новую ветку branch_name и сразу в нее переместиться

**git merge branch_name** - Слить в текущую ветку изменения из branch_name

**git branch -D branch_name** - Удалить еще не слитую ветку

**git branch -d branch_name** - Удалить уже слитую ветку
