<h1>MD5</h1>

<h3>1. Crea un hash MD5 del fichero ejercicio_crypto.txt y guárdalo como hash1.txt.</h3>

<br>


Si realizamos un listado de archivos/directorios, vemos el archivo **ejercicio_crypto.txt**. <p>

- `ls`

 <img src="src/ls md5.png" alt="md5" width="300" /> <p>

Calculamos el **hash MD5** del archivo y enviamos el resultado al archivo **hash1.txt**. 

- `md5sum ejercicio_crypto.txt > hash1.txt`

 <img src="src/send md5.png" alt="send" width="390" /> <p>

Podemos ver que dentro de **hash1.txt** se encuentra el **hash md5** del contenido de **ejercicio_crypto.txt** y el archivo ejercicio_crypto.txt.

- `cat hash1.txt`

 <img src="src/hash 1.png" alt="hash" width="470" /> <p>
