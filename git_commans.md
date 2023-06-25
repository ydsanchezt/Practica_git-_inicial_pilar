Describe que hacen los siguientes comandos de git, escribe su descripcion al frente en una sola linea.

1. git status: Este comando se usa para obtener el estado actual del repositorio

2. git clone: "clonar", crea una copia local del repositorio. A partir de que se hace la copia, los dos repositorios, el original y la copia, son independientes, es decir, cualquier cambio en uno de ellos no se verá reflejado en el otro.

3. git pull:  descarga los cambios de la rama <rama> del repositorio remoto <remoto> y los integra en la última versión del repositorio local, es decir, en el HEAD.

4. git checkout: git checkout <rama> actualiza los ficheros del directorio de trabajo a la última versión del repositorio correspondiente a la rama <rama>, y la activa, es decir, HEAD pasa a apuntar al último commit de esta rama. 
git checkout -b <rama> crea una nueva rama con el nombre <rama> y la activa, es decir, HEAD pasa a apuntar al último commit de esta rama. Este comando es equivalente aplicar los comandos git
branch <rama> y después git checkout <rama>. 

5. git log: muestra el historial de commits de un repositorio ordenado cronológicamente. Para cada commit muestra su código hash, el autor, la fecha, la hora y el mensaje asociado. Este comando es muy versátil y muestra la historia del repositorio en distintos formatos dependiendo de los parámetros que se le den.   

6. git branch:crea una nueva rama con el nombre <rama> en el repositorio a partir del último commit, es decir, donde apunte HEAD. Al crear una rama a partir de un commit, el flujo de commits se bifurca en
dos de manera que se pueden desarrollar dos versiones del proyecto en paralelo.

7. git add: Añadir cambios al area de preparación.
git add <fichero> añade los cambios en el fichero <fichero> del directorio de trabajo al área de preparación
git add <carpeta> añade los cambios en todos los ficheros de la carpeta <carpeta> del directorio de trabajo al área de preparación.
git add . añade todos los cambios de todos los cheros no guardados aún en el área de preparación.

8. git commit: Añadir cambios al repositorio.  Componentes básicos de la límea de tiempo de un proyecto de git. Registris en el tiempo.
git commit -m "mensaje" conrma todos los cambios de la zona de intercambio temporal añadiéndolos al repositorio y creando una nueva versión del proyecto. "mensaje" es un breve mensaje describiendo los cambios realizados que se asociará a la nueva versión del proyecto.  
git commit --amend -m "mensaje" cambia el mensaje del último commit por el nuevo mensaje "mensaje

9. git push: sube al repositorio remoto <remoto> los cambios de la rama <rama> en el repositorio local.

10. git merge: > integra los cambios de la rama <rama> en la rama actual a la que apunta HEAD.

Bibliografía
Sánchez, A.2023. Introducción a GIT. Aprendeconalf.es. Recuperado el 25 de junio de 2023, de https://aprendeconalf.es/docencia/git/manual/manual-git.pdf
