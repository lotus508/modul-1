# git-config

git config --global user.name "Жас"
git config --global user.email "zhasulan@bk.ru"

git config --global list

git config --global core.autocrlf true
git config --global core.safecrlf warn
git config --global core.quotepath off
git config --global init.defaultBranch main

git init # инициализация репозитория
git add . # добавить все файлы
git commit -m 'описание' # сделать коммит