Para comenzar he creado una carpeta llamada Prueba1Git-Github, he inicializado
el repositorio con el comando: git init

Acto seguido he enlazado este repositorio con el que se me ha asignado con el comando:

git remote add origin https://github.com/IESJacaranda/prueba1git-github-PedrassoxD.git

A continuación he clonado el repositorio que se me ha asignado con el comando:

git clone https://github.com/IESJacaranda/prueba1git-github-PedrassoxD.git

Ahora he traido todos los documentos de dicho repositorio con el comando:

git pull

El ejercicio me pide que tache mi nombre en el fichero listado.md, abro dicho
fichero con el programa remarkable y en la linea donde se situa mi nombre
añado al principio y al final dos veces el signo ~~ de forma que quedaria asi

~~Perez Labrada, Pedro Jose~~

Una vez hecho eso, guardo el fichero, y a continuación agrego los cambios con el comando:

git add .	(Este comando me añade todos los cambios realizados)

Ahora lo tenemos que guardar con el comando:

git commit -m "comentario"

Una vez hecho el commit, tenemos que subirlo al repositorio de nuevo con el comando:

git push

Nos mostrará para introducir nuestro nombre de ususario y contraseña de github
al introducirlo se habrá enviado a nuestro repositorio. 


