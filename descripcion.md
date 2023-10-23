1.	Crear un repositorio en GitHub con el nombre PrimerRepoGithub
Poner en terminal => `git clone https://github.com/Grupo-2-El-mas-Melon/PrimerRepoGithub`
2.	Clonarlo en una carpeta de nuestro repositorio local.
Hemos creado una carpeta y la hemos puesto en nuestro visual. 
3.	Crear un archivo descripción.txt y hacer un commit. Comprobar los cambios en la web del repositorio.
Hemos puesto el comando en terminal => `git add` y ``luego git commit -m "Hemos añadido en txt"``
4.	Crear una rama con el nombre RamaDesarrolloFront
Hemos creado la rama con => ``git branch RamaDesarrolloFrontRocio`` (Rocio será el nombre de cada uno de los componentes)
Verificamos en donde estamos => ``git branch``
Y nos debe de salir :
```bash
      RamaDesarrolloFrontRocio
    * main
```
5.	Crear un archivo index.html y hacer un commit. Comprobar la existencia de la rama y su contenido en la web del repositorio.
Luego en la terminal => ``git checkout RamaDesarrolloFrontRocio`` para diferenciarnos de los demas para no pisarnos. Para entrar en esta rama nueva.
Luego hemos creado un index.html
Luego en la terminal => ``git add .``
Luego en la terminal => ``git commit -am "Hemos añadido a Html"``
6.	Hacer el merge de la rama RamaDesarrolloFront a la rama master.
Primero nos movemos a la rama main => `git checkout main` 
Aqui se hace el merge => `git merge RamaDesarrolloFrontRocio`
7.	Eliminar la rama RamaDesarrolloFront y comprobar el resultado en la web del repositorio.
Eliminamos => `git branch -d RamaDesarrolloFrontRocio`
Verifica que solo te queda el MAIN => `git branch` y solo saldrá:
```bash
    * main
```
(EN CASO DE ERROR, forzar con `git branch -D RamaDesarrolloFrontRocio`)

