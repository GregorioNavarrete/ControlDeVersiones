# ControlDeVersiones
de pruba

# Creo mi repo local nuevo con una rama "master" y luego relacionos con el repo remoto nuevo 
$ git init

$ git remote -v             //para ver si ya estoy con un repo remoto

(si es recien creado)$ git remote add origin https://github.com/GregorioNavarrete/Clase-API-CRUDdb

(si quiero de cambiarlo de repositori remoto)$ git remote set-url origin https://github.com/GregorioNavarrete/ControlDeVersiones

$ git add .

$ git commit -m "Tu mensaje de commit aquí"

$ git status

$ git push -u origin master

# Como manejarse entre ramas de desarrollo 

$ git branch -a    // me dice en q rama estoy ,las locales y remotas

$ git checkout main  // para ir a la rama main 

$  git branch -m grego // para crear ramas 

git merge-base rama1 rama2 //para ver en que commit fue se difurco una nueva rama 

git log  // ve todos los commits de la rama donde estas

git log --all  //todos los commites de todas las ramas 

# Como unir ramas , si quiero agregar archivos a DEV , desde grego

git checkout DEV // la rama con las caracteristicas a agregar, a DEV

git merge grego //desde DEV pedir las actualisaciones de grego

$ git add . // para mandar la actualisacion al repo remoto

$ git commit -m "agregamos actualisacion de grego en rama DEV, funciona"

$ git push -u origin DEV

//luego si no sirve mas la rama "grego" xq ya se fuciono con DEV, la podemos borrar 

# Subir codigo local ya crado a remoto remoto nuevo, con comandos 

git init  //para iniciar el repo local

git remote add origin URL_DEL_REPOSITORIO_EN_GITHUB   //Enlazar el repositorio local con el remoto

git remote set-url origin URL_DEL_REPOSITORIO_EN_GITHUB   //Si ya existe un repositorio remoto y quieres cambiar la URL   " no lo use aun "

git remote -v    // verificar si el repositorio local está conectado correctamente al remoto

$ git branch -m MIDerror  //crea tu propia rama y luego hace marge, para no tener quilombo

$ git add .

$ git commit -m "primera rama, clase de MID de errores"

$ git push -u origin MIDerror 






