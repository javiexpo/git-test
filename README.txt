Inicio del proyecto
Hola mundo


Creacion de un repositorio desde cero
1. Creamos un directorio de trabajo
2. lanzamos dentro de ese dierectorio de trabajo el comando "git init"
3. Agregamos todos los ficheros del codigo fuente del proyecto con el comando "git add <nombre fichero>" ó "git add -A"
4. Hacemos el commit con el comando: "git commit -m "mensaje del commit"".
5. Conectamos nuestro repositorio local con el remoto usando el comando: "git remote add origin <server>": 
donde <server> representa la url del repositorio remoto por ejemplo "https://github.com/javiexpo/git-test.git"
6. Por ultimo subimos los cambios del repositorio local al repositorio remoto con el comando: "git push origin master"


Creacion de un repositorio clonado
1. Clonamos el repositorio con el comando "git clone <server>", donde <server> representa la url del repositorio remoto 
por ejemplo "https://github.com/javiexpo/git-test.git"
2. Trabajamos sobre el codigo fuente, modificando los ficheros, creando nuevos ficheros, etc..
3. Agregamos todos los ficheros del codigo fuente del proyecto con el comando "git add <nombre fichero>" ó "git add -A"
4. Hacemos el commit con el comando: "git commit -m "mensaje del commit"".
6. Por ultimo subimos los cambios del repositorio local al repositorio remoto con el comando: "git push"



Una vez creado el repositorio local y linkado con el repositorio remoto:
1. git pull -> Para actualizar nuestro repositorio local con lo que este cargado en el repositorio remoto.
2. git add -A -> para agregar nuestros cambios al stage.
3. git commit -m "<mensaje>" -> Para commitear nuestros cambios 
4. git push -> Para subir los cambios de nuestro repositorio local al repositorio remoto.


