# РУКОВОДСТВО ПОЛЬЗОВАТЕЛЯ GID
## 1 локальный репозиторий 
* git init иницилизацыя репозитория 
* git status показать состояние репозитория
* git diff сравнить рабочую директорию и индекс
* git add fail добовление файла
* git commit -m "" сахронение репозитория и собшение 
* git commit -am "" обединяет две команды add и b commit
* git log журнал изменений 
* git checkout возмжность перемешятся через версию 
* git checkout master возврошает на главную ветку (версию) 
## 2 работа с ветками 
* git branch "Naem" добовление ветки 
* git merge "Naem"слияние веток 
* git branch -d naem удалить ветку (используется, если её изменения уже влиты в главную ветку)
* git checkout -b "naem" созданеи и переход по веткам 
* git branch список веток
* git log --graph граффический журнал изменений 
## 3 работа с удаленм репозиторием 
## для создание удаленого репозитория 
* echo "# название репозитория на гит хабе" >> README.md
* git init
* git add README.md
* git commit -m "first commit"
* git branch -M main
* git remote add origin "**сылка на репозиторий из гит хба**"
* git push -u origin main 
## для переноса готового репозитория на гит хаб 
* git remote add origin "**сылка на удаленый репозиторий**"
* git branch -M main
* git push -u origin main
### для переноса репозитория из хит хаба 
* git pull переносит из удаленого репозитория 
* git clone (сылка на репозиторий которы хотим с клонировать)
*



