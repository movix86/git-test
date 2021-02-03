# git-test
Proyecto de prueba con git, aqui se puede probar todos los comandos y modificaciones (Área de prueba)
Este es un proyecto de prueba con git, para probar comandos y codigo.


Working directory --(git add)--> Staging area --(git commit)--> Repository*

# GIT COMMANS
1. git init   -> Se le dice a git que se va a iniciar un proyecto nuevo
2. git status -> Para ver como estan los archivos (Si estan listos para subir a no)
3. git add (nombre archivo) -> Pasar archivos del working a staging area (listo a subir)
4. git commit ->  Pasar al repositorio, como una primera foto del codigo en git
5. git commit -m "Mensaje de version" -> Esta es una forma mas rapido de guardar un commit
6. git push -u origin master   -> Subir al servidor para los demas desarrolladores
7. git push --all   -> Subir todo, ramas, etiquetas, configuraciones y mas.
8. git pull   -> Bajar lo que hicieron otros
9. git clone  -> Clonar un proyecto
10. git checkout -- index.html -> deshace los cambios guardados en el sublime. siempre que no tenga commit.
11. git diff index.html -> Este me muestra que fue lo que se agrego al nuevo codigo o proyecto.

11. git checkout (nombre de la rama que deseamos) -> este es para cambiar entre ramas
12. git checkout -- (nombre del archivo donde queremos deshacer el cambio.) -> este es para dar un paso atras en los archivos modificados.
13. git log -> Muestra todas las versiones o commits
14. git remote rm destination -> Elimina repositorio remoto del proyecto local.
15. git remote -v destination -> Muestra los repositorios remotos actuales en este proyecto.
16. git remote add origin <ssh direction> -> Agrega repsositorio remoto al proyecto local.

* Para guardar con "git commit" primero se oprime tecla I o S, para poder escribir y luego se escribe :wq y ENTER. (Laptop ASUS modernas)
* Si creo el archivo (.gitignore) y en el escribo los archivos y carpetas que quiero que git ignore. Nota: Solo basta con escribir el nombre del archivo o la carpeta
# HASTA AQUI GIT CODIGO Y PASAMOS A GITHUB
Es necesario sincronizar el codigo de proyecto con github. En la seccion repository se crea un repositorio nuevo.
1) Despues en la consola local se escribe:

# git remote add origin <codigo ssh del proyecto>
--->Ejem: git remote add origin git@github.com:movix86/git-test.git

2) Despues se sincrinoza la rama master local con la remota:
# git push -u origin master
