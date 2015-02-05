#1.- COMANDOS-DE-LINUX
Comandos de Linux  
# **sudo**  
Cuando queramos hacer cambios como administrador.  
(Este comando nos confiere permisos de administrador del sistema y nos solicita siempre nuestra contraseña para poder ejecutarse. El comando sudo siempre inicia la linea de comandos a ejecutar.)  

#**sudo su**
Todo lo que hagamos a continuación será como super usuarios.  

#**exit**  
Para volver a ser usuario normal 

#**apt**  
(Advance Packagin Tool) es una herramienta de empaquetado de aplicaciones creada por el proyecto Debian, para simplificar la instalación y desinstalación de programas en Linux.

#**sudo apt-get update**  
Para leer los ficheros  
(Cada vez que deseemos comprobar actualizaciones usaremos el comando sudo apt-get update. Para que el sistema pueda obtener los paquetes que este contiene, antes de poder instalarlos.)

#**sudo apt-get upgrade**  
Para actualizar ficheros  
(Actualizar todos nuestros programas a sus últimas versiones, e instalar las actualizaciones del sistema de manera fácil y rápida, usamos el comando upgrade.)

#**sudo apt-get install**  
Para instalar un programa. 
(sudo apt-get install apache2) 

#**sudo apt-get remove**  
Para desinstalar un programa.  

#**sudo rm**      
Para borrar un archivo.  
Para borrar el archivo prueba.txt ubicado en /home, ejecutamos: $ rm /home/prueba.txt  

#**sudo rm -rf pw**  
para forzar el borrado de una carpeta que contiene archivos.

#**sudo rmdir**  
Para borrar un directorio.
Este comando también presenta varias opciones. La opción -R borra todos los archivos y directorios de forma recursiva. Por otra parte, -f borra todo sin pedir confirmación.   

sudo rmdir -R nombre del directorio

#**sudo mkdir**  
Para crear un directorio.  
(mkdir dir1: crear una carpeta o directorio con nombre ‘dir1′). 
Crea un directorio nuevo tomando en cuenta la ubicación actual. Por ejemplo, si estas en /home y deseas crear el directorio ejercicios, sería: $ mkdir /home/ejercicios  

#**mkdir -p**  
Mkdir tiene una opción bastante útil que permite crear un árbol de directorios completo que no existe. Para eso usamos la opción -p: $ mkdir -p /home/ejercicios/prueba/uno/dos/tres 

#**mkdir -p pt7/peliculas**  
Crea un directorio y otro que cuelga del primero.  

#**mv dir**  
Renombrar o mover un fichero o carpeta (directorio).  
mueve un archivo a una ruta específica, y a diferencia de cp, lo elimina del origen finalizada la operación. Por ejemplo:$ mv /home/prueba.txt /home/respaldos/prueba2.txt  
Al igual que cp, en la sintaxis se especifica primero el origen y luego el destino. Si indicamos un nombre de destino diferente, mv moverá el archivo o directorio con el nuevo nombre.  

#**rmdir p1 p2**  
Borra varios directorios  

#**sudo reboot**  
Reiniciar.  

#**sudo tasksel**  
Instala tareas de paquetes.  
Una que viene predefinida es la de servidor LAMP. tasksel nos ayuda a instalar un servidor LAMP en Ubuntu facilmente.  

#**cp**  
copia un archivo o directorio origen a un archivo o directorio destino.  
Por ejemplo, para copiar el archivo prueba.txt ubicado en /home a un directorio de respaldo, podemos usar:  
$ cp /home/prueba.txt /home/respaldo/prueba.txt  
En la sintaxis siempre se especifica primero el origen y luego el destino. Si indicamos un nombre de destino diferente, cp copiará el archivo o directorio con el nuevo nombre.  

#**cp -r**  

Con la opción -r copia no sólo el directorio especificado sino todos sus directorios internos de forma recursiva.   
Suponiendo que deseamos hacer una copia del directorio /home/ejercicios que a su vez tiene las carpetas ejercicio1 y ejercicio2 en su interior, en lugar de ejecutar un comando para cada carpeta, ejecutamos:  
$ cp -r /home/ejercicios /home/respaldos/

#**cp file1**  
Copiar un fichero. 

#**cp dir /* .**  
Copiar todos los ficheros de un directorio dentro del directorio de trabajo actual.  

#**find / -name file1**  
Buscar fichero y directorio a partir de la raíz del sistema.  

#**passwd**  
Cambiar contraseña.  

#**ifconfig**  
Para visualizar la IP de mi equipo. 

#**iwconfig**  
Para saber la IP del Wifi

#**nano**  
Para usar un editor de texto.  
Para escribir en una web que tenemos situada en HTML  
cd /var/www/html  
ls  
index.html  
sudo nano index.html   

#**ls**  
Para listar ficheros.  
(Ver los ficheros de un directorio).   

#**ls -l /**  

nos lista todos los archivos desde la raíz (estemos en el directorio que sea).  

ls es el comando, -l es la opción. 

ls -l /var/www/html  -- nos listaría los ficheros que haya en HTML  

Para ver los archivos que tenemos desde la raíz (root /) ejecutar los comandos:

ls -l / 

![](http://grabilla.com/0511c-5789affd-af8d-42fe-bf51-9fbaa5b9b168.png)  


#**ls -la** sirve para que nos liste con más información.


![](http://grabilla.com/0511c-d5044934-fdd3-4652-abd9-21549344509b.png)  

El archivo con .. es el padre.  
El que tiene . soy yo mismo.

#**ls *txt**  

Para hacer una búsqueda de cualquier fichero que termine en txt  

#**ls -l**  
nos muestra lo que contiene un directorio  

#**ls -la**    
nos muestra también los archivos ocultos del directorio  

#**ls -F**  
Lista los ficheros que contiene un directorio y nos informa de qué tipo son: ejecutables (*), directorios, archivos normales (.txt) 

#**ls /bin**  
Nos lista todos los comandos de Linux   

#**ls |more**  
Para que cuando liste los ficheros se pare a golpes de pantalla.  

#**clear**  
Para limpiar pantalla  

#**pwd**  
Me indica donde estoy desde la raíz (/). 
(Mostrar el camino del directorio de trabajo). 

#**cat**  
Para ver los contenidos de un fichero.  
Cat (de concatenar), es una utilidad que nos permite visualizar el contenido de un archivo de texto sin la necesidad de un editor. Para utilizarlo solo debemos mencionarlo junto al archivo que deseamos visualizar:
$ cat prueba.txt  

#**cd**   
Ir al directorio raíz.  
Nos permite cambiar de directorio en la terminal. 
cd seguido de una ruta, se usa para ubicarse en un directorio especifico.(Pe. cd /documentos).    

#**cd ..**  
Éste cambiará al directorio superior desde el directorio actual (retroceder un nivel). 

#**cd ../../etc**  
Es una ruta relativa.  
Sirve para llegar donde queramos subiendo varios niveles. 

#**cd ~user**  
Éste comando irá al directorio de inicio del usuario que es "/home/username".  
(Ctrl X cuando queremos ir a nuestro usuario mariel@mariel:$)      

#**cd -**  
Ir (regresar) al directorio anterior.  

#**touch**  
Crea un archivo vacío, si el archivo existe actualiza la hora de modificación.  
Para crear el archivo prueba1.txt en /home, seria: $ touch /home/prueba1.txt  

#**script**  
Es un archivo que contiene varios comandos.  
Suele terminar en .sh  
La secuencia para crearlo es la siguiente:  
cd (para ir al directorio donde queremos crearlo)  
nano nombredelarchivo.sh  
 #!/bin/bash (guardar y salir)  
Para ejecutarlo: 
chmod +x nombredelarchivo  
./nombredelarchivo  
Para poder listarlo y ver que esté.  

#**whois www.example.com**  
Buscar en base de datos Whois. Para averiguar datos de alguien.  

#**cd /var** ENTER **ls**  
Si no aparece www es que no tenemos Apache instalado. 

#**sudo cp -r wordpress/ /var/www/html/**
(-r quiere decir recursivo, desde donde le decimos hasta abajo, todos los archivos inferiores)
Copiar un archivo de una carpeta a otra

#**sudo chmod 777 NO USARLO NUNCA**, abriríamos nuestro servidor a cualquiera.
sudo chmod 777 -R /var/www/html/wordpress/  

#**wget**   
Seguido de  (espacio) una dirección https desde la carpeta home y nos copia todo lo que contenga esa página.  

#**CTRL + ALT GR Y F1-F6**  
Nos permite crear usuarios desde la terminal de Guadalinex  

Desde el entorno gráfico también podemos abrir un terminal: botón dr. ratón ABRIR UN TERMINAL  

#**ALT GR + 4**  
Para generar este carácter ~  

#**Uso de caracteres recomendados**  

A-Z  
a-z  
0-9  
_  

#**Para ver los comandos de un tipo pe. rm**   
Escribimos rm y pulsamos dos veces el tabulador, nos aparecerán todos los que haya de ese tipo:  
rm  rmdir  rmid  rmmod  


