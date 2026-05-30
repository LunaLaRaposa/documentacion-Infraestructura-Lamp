# Instalacion y configuracion sistema Backup

## 1. Busqueda sistema Backup
Lo primero que hacemos es investigar que clase de sistema de backup seria el mas optimo para la situacion de la empresa

## 2. Instalacion del sistema Backup
Una vez tenemos elegido el sistema que utilzar comenzaremos con la instalacion del servidor de backup en el propio servidor siguiendo los pasos necesarios

## 3. Configuracion sistema Backup

### 3.1 Configurar tipo de backup
Cuando se realizan backups se pueden elegir distintos metodos para realizarlos segun las necesidades de backup de la empresa y los recursos de espacio disponibles, en esta caso usaremos un backup incremental para ahorrar la mayor cantidad de espacio

### 3.2 Configurar lugar de guardado de backups
A la hora de configurar donde guardar los archivos de backup se hara  en una carpeta donde solo el programa tenga  acceso de escritura por cuestiones de seguridad

### 3.3 Configurar automatismo de copias de seguridad
COnfiguraremos la opcion de hacer copias de seguridad manualmente si se necesita, pero tambien se necesitara activar que se realicen automaticamente las copias de seguridad para evitar perdidas de datos

### 3.4 Configurar horario de copias de seguridad
tambien configuraremos el horario en el que se hacen las copias de seguridad, en este caso he elegido hacer tanto en martes como en viernes, martes para guardar cambios urgentes de problemas ocurridos durante el fin de semana y el viernes para guardar guardar el progreso general de la semana, todas la copias se haran siempre 15 minutos antes del fin de la jornada en caso de que ocurra algun error catastrofico durante la creacion de la copia

| lunes | marte | miercoles | jueves | viernes |   sabado   |  domingo   |
| :---: | :---: | :-------: | :----: | :-----: | :--------: | :--------: |
|       |   X   |           |        |    X    | No Trabajo | No Trabajo |

