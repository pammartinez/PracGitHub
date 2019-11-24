# Respuestas al Ejercicio 1.
# Pam Martínez

**Paso 11**
$ git reset --hard HEAD~1
Reset con modificador hard para perder los cambios realizzados. 

**Paso 12**
$ git reflog
$ git reset --hard 22330d
Ver todos los commits efectuados y mover el master y head al puntero que le digo averiguado en reglog,--hadr mofifica el WC 

**Paso 13**
$ git merge master
No hay conflicto por que 
EStando en la rama styled absorber a master con un merge.

**Paso 19**
$ git branch
$ git checkout styled
$ git merge htmlify
Si hay conflicto porque estan distintos los archivos en la misma linea.por ello hay que resolver editando y gravando.

**Paso 21**
$ git checkout master
$ git merge styled

**Paso 25**
$ git log --graph

**Paso 26**
$ git merge --no-ff title, no podria porque necesita crear un nuevo nodo para unir las ramas.

**Paso 27** 
 
$ git reset HEAD~1

**Paso 28**
$ git status 
$ git restore git-nuestro.md

Paso 29
$ git branch -D title

**Paso 30**
$git reflog 
git reset --hard 358a663bra
$ git switch -c titles
git checkout master
git merge titles 

**Paso 32**
git log 
git checkout  22330d69c920a69196d1473f9fd590a5d03ffabc
Paso 33
git reflog
$ git checkout 0c486d7
