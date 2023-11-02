# ControlDeVersiones
de pruba

###  Creo mi repo local con una rama "master" y luego relacionos con el repo remoto 
$ git init

$ git remote -v             //para ver si ya estoy con un repo remoto

$ git remote set-url origin https://github.com/GregorioNavarrete/ControlDeVersiones

$ git add .

$ git commit -m "Tu mensaje de commit aquí"

$ git status

$ git push -u origin master

### Como manejarse entre ramas de desarrollo 

$ git branch -a    // me dice en q rama estoy ,las locales y remotas

$ git checkout main  // para ir a la rama main 

$  git branch -m grego // para crear ramas 

git merge-base rama1 rama2 //para ver en que commit fue se difurco una nueva rama 

git log  // ve todos los commits de la rama donde estas

git log --all  //todos los commites de todas las ramas 

### Como unir ramas , si quiero agregar archivos a DEV , desde grego

git checkout DEV // la rama con las caracteristicas a agregar, a DEV

git merge grego //desde DEV pedir las actualisaciones de grego









