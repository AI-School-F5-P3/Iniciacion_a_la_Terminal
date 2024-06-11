# Iniciación al uso de la Terminal
![image](https://github.com/AI-School-F5-P3/Iniciacion_a_la_Terminal/assets/18529354/d1e86a01-1560-4c31-898f-65f2616ae601)

Ejercicios básicos con explicaciones para el uso la terminal en Windows (PowerShell y CMD) y en Linux. Se deberán ir probando todos los comandos según en el sistema operativo que estés usando. Estos ejercicios cubren las tareas básicas necesarias para comenzar a usar la terminal en Windows (PowerShell y CMD) y en Linux. 

## Ejercicio 1: Navegar por directorios 
![CD1](https://github.com/AI-School-F5-P3/Iniciacion_a_la_Terminal/assets/18529354/674901b2-9a0d-4a28-84ff-dfb3bee9f2fe)

**Objetivo**: Aprender a moverse entre directorios. 

**Explicación**: El comando `cd` (change directory) se utiliza para cambiar de directorio en la terminal. 

## Ejercicio 2: Listar el contenido de un directorio 

**Objetivo**: Aprender a listar los archivos y carpetas en un directorio. 

**Explicación:** Los comandos `dir` (en CMD), `Get-ChildItem` (PowerShell) y ls (en Linux) se utilizan para listar los contenidos de un directorio.

## Ejercicio 3: Crear una carpeta 

**Objetivo**: Aprender a crear una nueva carpeta. 

**Explicación**: Los comandos `mkdir` (Linux y PowerShell) y `New-Item` (en PowerShell) se utilizan para crear directorios. 

## Ejercicio 4: Crear un archivo 

**Objetivo**: Aprender a crear un archivo vacío. 

**Explicación**: Los comandos `New-Item` (en PowerShell), `type nul >` (en CMD) y touch (en Linux) se utilizan para crear archivos. 

## Ejercicio 5: Escribir en un archivo 

**Objetivo**: Aprender a escribir texto en un archivo. 

**Explicación**: Los comandos `echo` y `>` se utilizan para escribir texto en un archivo. 

## Ejercicio 6: Leer el contenido de un archivo 

**Objetivo**: Aprender a leer el contenido de un archivo. 

**Explicación**: Los comandos `Get-Content` (PowerShell), `type` (CMD) y `cat` (Linux) se utilizan para mostrar el contenido de un archivo. 

## Ejercicio 7: Borrar un archivo 

**Objetivo**: Aprender a borrar un archivo. 

**Explicación**: Los comandos `Remove-Item` (PowerShell), `del` (CMD) y `rm` (Linux) se utilizan para borrar archivos. 

**Ejercicio 8**: Borrar una carpeta 

**Objetivo**: Aprender a borrar una carpeta. 

**Explicación**: Los comandos Remove-Item (PowerShell), `rmdir` (CMD) y `rm -r` (Linux) se utilizan para borrar directorios. 

## Ejercicio 9: Buscar archivos 

**Objetivo**: Aprender a buscar archivos en un directorio.

**Explicación**: Los comandos `Get-ChildItem` (PowerShell), `dir /s` (CMD) y `find` (Linux) se utilizan para buscar archivos. 

## Ejercicio 10: Saber en qué ruta estás 

**Objetivo**: Aprender a identificar el directorio actual. 

**Explicación**: Los comandos `Get-Location` (PowerShell), `cd` (sin argumentos en CMD) y `pwd` (Linux) se utilizan para mostrar el directorio actual. 

## Ejercicio 11: Copiar ficheros entre carpetas 

**Objetivo**: Aprender a copiar archivos entre directorios. 

**Explicación**: Los comandos `Copy-Item` (PowerShell), `copy` (CMD) y `cp` (Linux) se utilizan para copiar archivos. 

## Ejercicio 12: Mover un fichero entre directorios 

**Objetivo**: Aprender a mover archivos entre directorios. 

**Explicación**: Los comandos `Move-Item` (PowerShell), `move` (CMD) y `mv` (Linux) se utilizan para mover archivos. 

## Ejercicio 13: Visualizar el contenido de un fichero de texto 

**Objetivo**: Aprender a visualizar el contenido de un archivo de texto. 

**Explicación**: Los comandos `Get-Content` (PowerShell), `type` (CMD) y `cat` (Linux) se utilizan para mostrar el contenido de un archivo. 

## Ejercicio 14: Borrar el contenido de la pantalla (clear) Objetivo: Aprender a borrar el contenido de la pantalla de la terminal. 

**Explicación**: Los comandos `clear` (Linux y PowerShell) y `cls` (CMD) se utilizan para limpiar la pantalla de la terminal. 

## Ejercicio 15: Usar permisos de super usuario (sudo) 

**Objetivo**: Aprender a ejecutar comandos con permisos de superusuario (solo en linux). 

**Explicación**: El comando `sudo` (Linux) se utiliza para ejecutar comandos con privilegios elevados.

> Nota: En Windows, PowerShell debe ser ejecutado como administrador para realizar tareas con permisos elevados. 

## Ejercicio 16: Ver los permisos de un fichero 

**Objetivo**: Aprender a ver los permisos de un archivo. 

**Explicación**: Los comandos `ls -l` (Linux) y `Get-Acl` (PowerShell) se utilizan para ver los permisos de un archivo. 

## Ejercicio 17: Modificar los permisos de un fichero Objetivo: Aprender a modificar los permisos de un archivo. 

**Explicación**: Los comandos `chmod` (Linux) y `icacls` (CMD) se utilizan para cambiar los permisos de un archivo. 

## Ejercicio 18: Ver la lista de procesos 

**Objetivo**: Aprender a ver la lista de procesos en ejecución. 

**Explicación**: Los comandos `Get-Process` (PowerShell), `tasklist` (CMD) y `ps` (Linux) se utilizan para listar los procesos. 

## Ejercicio 19: Ver la lista de IPs de tu ordenador 

**Objetivo**: Aprender a ver las direcciones IP de tu ordenador. 

**Explicación**: Los comandos `ipconfig` (PowerShell y CMD) y `ifconfig` o `ip a` (Linux) se utilizan para mostrar la configuración de red. 

## Ejercicio 20: Hacer un ping a una web 

**Objetivo**: Aprender a verificar la conectividad a una web. 

**Explicación**: El comando `ping` se utiliza para verificar la conectividad de red con un servidor. 

## Ejercicio 21: Descargar el contenido de una web (wget) 

**Objetivo**: Aprender a descargar archivos desde la web.

**Explicación**: El comando `wget` (CMD y Linux) y `Invoke-WebRequest` (PowerShell) se utiliza para descargar archivos desde la web. En Windows, se puede utilizar PowerShell para descargar archivos.

# Ejercicios Iniciación terminal Linux 

Vamos a practicar un poco con la terminal de Linux con una serie de ejercicios, para ello vamos a utilizar la siguiente web: Webimal (https://www.webminal.org/) 

🖥️ Abre un terminal y escribe los comandos que te permitan realizar las siguientes acciones: 

1. Crea un archivo de tamaño 0 

`<span style="color:yellow";>touch</span> arch_tam0`

2. Listar todos los archivos del directorio bin. 

`ls /bin`

3. Listar todos los archivos del directorio etc que empiecen por t en orden inverso. 

`ls /etc/t* -r`

`ls –r /etc | grep ^t`

4. Listar todos los archivos del directorio dev que empiecen por tty y tengan 5 caracteres. 

`ls /dev/tty`

5. Listar todos los archivos del directorio dev que empiecen por tty y acaben en 1,2,3 ó 4. 

`ls /dev/tty[1,2,3,4]`

`ls /dev/tty[1-4]`

`ls /dev/tty*[1-4]`

6. Listar todos los archivos, incluidos los ocultos, del directorio raíz. 

ls -la /

7. Listar todos los archivos del directorio etc que no empiecen por t.
ls -I “t*” /etc 
ls  ignore=t* /etc 
8. Listar todos los archivos del directorio usr y sus subdirectorios. 
ls -R /usr 
9. Cambiarse al directorio tmp y verificarlo. 
cd /tmp 
pwd 
10. Mostrar el día y la hora actual. 
date 
11. Con un solo comando posicionarse en el directorio $HOME y verificarlo. 
cd 
pwd 
12. Crear los directorios dir1, dir2 y dir3 en el directorio PRUEBA. Dentro de dir1 crear el directorio dir11. Dentro del directorio dir3 crear el directorio dir31. Dentro del directorio dir31, crear los directorios dir311 y dir312. 
cd 
mkdir PRUEBA 
mkdir dir1 & mkdir dir2 & mkdir dir3 
mkdir dir1/dir11 & mkdir dir3/dir31 
mkdir dir31/dir311 & mkdir dir31/dir312 
13. Copiar un archivo /etc/motd a un archivo llamado mensaje de vuestro directorio PRUEBA. cp /etc/motd /home/usuario/PRUEBA/mensaje 
14. Copiar mensaje en dir1 y dir2, y verificarlo. 
cp mensaje ~/PRUEBA/dir1 & cp mensaje ~/PRUEBA/dir2
ls -R /PRUEBA 
15. Copiar en el directorio dir311 los archivos de /bin que tengan una a como segunda letra y su nombre tenga cuatro letras. 
cp /bin/?[a] /home/usuario/PRUEBA/dir3/dir311 
16. Mover el directorio dir31 y sus subdirectorios debajo de dir2. 
mv –r ~/PRUEBA/dir3/dir31 ~/PRUEBA/dir2/ 
17. Mostrar por pantalla los archivos ordinarios del directorio HOME y sus subdirectorios. ls -R /home 
18. Ocultar el archivo mensaje del directorio dir3. 
mv /home/usuario/PRUEBA/dir3/mensaje /home/usuario/PRUEBA/dir3/.mensaje 19. Borrar los archivos y directorios de dir1, incluido el propio directorio. 
rm -rf /home/usuario/PRUEBA/dir1 
rm -R dir1 
20. Copiar al directorio dir312 los ficheros del directorio /dev que empiecen por t, acaben en una letra que vaya de la a la b y tengan cinco letras en su nombre. 
cp /dev/t???[a-b] /home/usuario/PRUEBA/dir3/dir312 
21. Mover el directorio dir312 debajo de dir3. 
mv /home/usuario/PRUEBA/dir3/dir31/dir312 /home/usuario/PRUEBA/dir3/dir312 22. Crear un enlace simbólico al directorio dir1 dentro del directorio dir3 llamado enlacedir1. ln -s /home/usuario/PRUEBA/dir1 /home/usuario/PRUEBA/dir3/enlacedir1
23. Utilizando el enlace enlacedir1 copiar los archivos que empiecen por u del directorio /bin en directorio nuevo1. 
cp /bin/u* enlacedir1/nuevo1/ 
ls /bin/u* > cp /home/usuario/PRUEBA/dir3/enlacedir1 
24. Crear un enlace simbólico (llamado enlafich1) a un fichero enlace de dir2 en dir1. 
ln -s /home/usuario/PRUEBA/dir2/enlace 
/home/usuario/PRUEBA/dir1/enlacefich1 
25. Posicionarse en dir1 y, mediante el enlace enlafich1 copiar el archivo fich1 dentro de dir311. 
cp  /fich1 enlafich1/dir31/dir311 
26. Seguir en dir1 y, mediante el enlace enlafich1, sacar por pantalla las líneas que tiene el archivo fich1. 
cd /home/usuario/PRUEBA/dir1 
cat enlacefich1 
27. Borrar todos los archivos y directorios creados en el directorio PRUEBA. rm -R PRUEBA 
28. Crear el directorio dir2 y dir3 en el directorio PRUEBA. 
mkdir /home/usuario/PRUEBA/dir2 & mkdir /home/usuario/PRUEBA/dir3 29. Eliminar todos los permisos de escritura (propietario, grupo, otros) del directorio dir2. chmod u-w,g-w,a-w /home/usuario/PRUEBA/dir2 
30. Cambiar el directorio actual al directorio dir3, y crear cuatro nuevos directorios llamados dira, dirb, dirc, y dird bajo el directorio actual.
mkdir dira & mkdir dirb & mkdir dirc 
31. Comprobar los permisos de acceso de los directorios recién creados. ls -la 
32. Crear el fichero uno. Quitarle todos los permisos de lectura. Comprobarlo. Intentar borrar dicho fichero. 
touch uno 
chmod u-r,g-r,a-r uno 
ls -l uno 
rm uno 
33. Crear en el directorio actual un directorio carpeta1 con los tres permisos para el propietario, dentro de él fich1 con lectura y escritura para todos y fich2 con lectura y escritura para el propietario y solo lectura para el resto. El directorio carpeta2 con todos los permisos para el propietario y lectura y ejecución para los del mismo grupo. Dentro file1 con lectura y escritura para el propietario y los del grupo y file2 con los mismos para el propietario y solo lectura para el grupo. 
mkdir carpeta1 
chmod u+rwx 
mkdir carpeta2 
chmod u+rwx g+rx 
touch carpeta1/fich1 
chmod +rw carpeta1/fich1 
touch carpeta1/fich2 
chmod u+rw o+wx 
touch carpeta2/file2 
chmod u+rwx g+r;
