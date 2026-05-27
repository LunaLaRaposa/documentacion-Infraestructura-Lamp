# Instalacion y configuracion de sistema de monitorizacion

## 1.Seleccion de sistemas a monitorizar
Lo primero seria analizar que sistemas queremos monitorizar y a que escala, en este caso queremos monitorizar:
- linux(Sistema operativo)
- Apache(servidor web)
- MySQL (Base de datos)
- Sistema de backups(Evitar perdida informacion)
- Firewall

## 2.  Buscar programa para monitorizacion
ahora buscamos un programa para monitorizacion de sistemas, para este caso convendria un programa que realice pings a ciertas direcciones para comprobar si firewall y apache funciona, pero tambien gestione y centralice los logs para poder ver si hay algun reporte de error

## 3. Instalacion del programa de monitorizacion
Una vez tenemos claro el programa que necesitamos lo instalaremos en la maquina siguiendo las intrucciones provistas por el desarrollador

## 4. Configuracion

### 4.1 Configuracion de comprobacion de estado
Lo primero que haremos sera configurar que el programa pueda leer el estado de los distintos servicios

### 4.2 Centralizacion de logs
Configuraremos el programa para que tome automaticamente los archivos de log de los distintos servicios para que en caso de error se pueda comprobar facilmente desde un lugar centralizado

### 4.3 Configuracion notificaciones
Por ultimo configuraremos el sistema de notificaciones, esto servira para avisar al instante siempre que haya algun error o algun servicio este caido para poder actuar con la mayor rapidez
