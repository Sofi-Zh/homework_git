это какой-то ужас

как подключиться:

git init
git add .
git commit -m "first commit"
git remote set-url origin git@github.com:Sofi-Zh/homework_git.git (тут ссылка на нужный репозиторий)
(когда я вызыываю ggeit remote add origin  https://github.com/Sofi-Zh/homework_git.git, запрашивается логин и пароль)
git branch -M main
git push -u origin main

Ветки
git branch - список веток
git branch new_feature - создать ветку
git checkout new_feature - переключиться
git checkout -b new_feature - создать и переключиться сразу
get branch -d new_feature - удалить ветку
get merge new_feature - cлить ветки (нужно вызывать в ветку, в которую нужно добавить информацию)
