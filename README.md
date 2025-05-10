git status - проверить наичие файлов в папке
git add [files] - добавить 1 файл в stage(промежуточная область)
gir add . - добавить все созданные файлы
git commit -m "comment" - добавить комметарии к записи
git log - просмотреть записи (добавленные комментарии)
git config -get user.name, user.email - просмотреть имя автора (свое на git), просмотреть емаил (свое на git)
git log --oneline - просмотреть короткую запись комментария
git push [rep_link] [branch_name] - добавить файлы в репозиторий github (branch - ветка)
git remote -v - ссылка на репозиторий
git branch - посмотреть название ветки(все ветки)
git push origin(название ссылки, можно по названию) master(branch название ветки)
git reset [file] - удалить запись из промежуточной области (stage)
git diff - прсмотреть проведенные изменения в файлах
git reset --hard - возвращает изменения в файлах назад и очищает git status(отменяет изменения которые сделали)


ВЕТКИ
master - главная ветка
develop - ветка код для разработки
feature/main-page - ветка отвечает за разработку главной страницы
feature/about-company - ветка отвечает за разработку о компании

git branch develop - создать ветку "develop"
git checkout develop - переключиться на ветку "develop"
