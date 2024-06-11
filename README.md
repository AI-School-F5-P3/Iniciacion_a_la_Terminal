# Iniciación al uso de la Terminal
![image](https://github.com/AI-School-F5-P3/Iniciacion_a_la_Terminal/assets/18529354/d1e86a01-1560-4c31-898f-65f2616ae601)

Ejercicios básicos con explicaciones para el uso la terminal en Windows (PowerShell y CMD) y en Linux. Se deberán ir probando todos los comandos según en el sistema operativo que estés usando. Estos ejercicios cubren las tareas básicas necesarias para comenzar a usar la terminal en Windows (PowerShell y CMD) y en Linux. 

## Ejercicio 1: Navegar por directorios 

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

