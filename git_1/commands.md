git init - initialized new repository in new folder .
git add . - index all files .
git commit -m "text commit" - make commit . save current .version of code .
clear - clear terminal .
ctrl + l - like "clear" .
git log - look history of commit .
    
### text commit

ref - refactor .
init - initialization .
upd - update .
fix - fixed . 
add - addition.
rm - remove .
#
git config --global user.name "Твоё имя"
git config --global user.email "email@example.com"
git init                # создать новый репозиторий
git clone <url>         # склонировать проект с GitHub (или другого источника)
# Work with files
git status              # показать статус файлов
git add .               # добавить все изменения
git add <file>          # добавить конкретный файл
git commit -m "Комментарий"   # зафиксировать изменения

# Send and Get 
git push                # отправить изменения на сервер (GitHub и т.п.)
git pull                # забрать изменения с сервера
git fetch               # получить изменения, но не сливать

# Branches
git branch              # показать список веток
git branch <название>   # создать новую ветку
git checkout <название> # перейти на ветку
git switch <название>   # (современный способ) перейти на ветку
git merge <ветка>       # слить ветку в текущую

# History 

git log                 # история коммитов
git diff                # показать отличия
git show                # показать детали последнего коммита

# Remove and cancellation

git rm <файл>           # удалить файл из Git
git restore <файл>      # восстановить файл (отменить изменения)
git reset HEAD <файл>   # убрать файл из индекса (до коммита)
