# РУКОВОДСТВО ПОЛЬЗОВАТЕЛЯ GID
## 1 локальный репозиторий 
* git init иницилизацыя репозитория 
* git add fail 
* git commit -am "" сахронение репозитория 
* git log журнал изменений 
* git checkout возмжность перемешятся через версию 
* git checkout master возврошает на главную ветку (версию) 
## 2 работа с ветками 
* git branch "Naem" добовление ветки 
* git merge "Naem"слияние веток 
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


