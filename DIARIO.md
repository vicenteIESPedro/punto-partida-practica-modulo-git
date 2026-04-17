TAREA 1
Un fork es una copia de un repositorio de github en tu repositorio. Se mentiene un enlace al repositorio original.
Se usa para realizar modificaciones sin que afecte al repositorio original. 
En un momento determinado puedes hacer un PR sobre el proyecto original para actualizalo con lo que hayas modificado.
<img width="717" height="244" alt="git remote -v" src="https://github.com/user-attachments/assets/540015ee-8dc3-41aa-95e3-6e9e1eebc043" />

He descomentado la opcion 4 para que quede como acabamos en la practica
Parto de la rama main y creo la rama dev

<img width="1042" height="393" alt="captura 2-rama dev" src="https://github.com/user-attachments/assets/2296fc26-3277-4f1d-9886-88365733f239" />
<br><br>
TAREA 2
La rama main es la rama estable. Trabajamos con la rama dev para que los cambios, si no van bien, no afecten a la aplicación en producción. A partir de dev vamos creando ramas para las nuevas funcionalidades. 
<br><br>
<img width="1076" height="708" alt="captura 3- programa" src="https://github.com/user-attachments/assets/4129b331-f42a-4d8f-85b7-df22d57f136d" />

<br><br>
TAREA 3
Un conflicto se produce cuando mezclar dos ramas (merge) y git no la puede realizar de forma automática. 
Esto sucede porque la rama en la que se va a realizar un merge ya contiene una versión de un archivo de fecha de commit posterior a la que proviene de la rama a partir de la que queremos combinar y ambas contienen una misma línea con contenido distinto.
En esta caso, se han generado dos ramas a partir de la misma versión en la rama dev. Las dos ramas cambian de forma distinta la linea correspondiente a la descripcion de Opción 3. Volcaremos (merge) una rama sobre dev. Al volcar la segunda rama, y tener la misma linea con contenido distinto, git no sabrá cual de las versiones de la línea debe conservar.
<br><br>
TAREA 4
En la ventana de Files Changed, en la parte inferior nos aparece una comparativa (diff) del fichero en las dos ramas involucradas en el merge. Nos aparecen las líneas que se añaden/eliminan en la versión definitiva del fichero tras el merge.
Es últil revisarlo para asegurarse de que estamos realizando el merge con la versión del fichero correcta
<br>
<img width="1449" height="718" alt="captura 4- PR feature-opcion-5" src="https://github.com/user-attachments/assets/4eda4f04-a266-4bf3-9acb-dbe5d91ed710" />
<img width="1574" height="726" alt="captura 4-2- PR feature-opcion-5" src="https://github.com/user-attachments/assets/fb32eeb3-18ff-4eb1-8444-864bc2a22a94" />
<br><br>
TAREA 5
Aparecen cuando se hace un diff entre dos versiones del fichero. En este caso, ha ocurrigo cuando se ha hecho el merge y hay confilcto entre las dos versiones del fichero (una de cada brazo).
Indican, para cada conflicto,  lo que aparecía en el primer fichero (<<<<<) y lo que aparecía en el segundo fichero (>>>>>>>) separados por ======
<br><br>
<img width="789" height="481" alt="captura 5- PR con error" src="https://github.com/user-attachments/assets/97fe980b-2748-4fc8-8c27-5653f5181180" />
<br><br>
<img width="784" height="716" alt="Captura 5-lineas de conflicto" src="https://github.com/user-attachments/assets/33a70062-c8f9-4518-88ce-6b1c56457ca9" />
<br><br>
<img width="996" height="679" alt="Captura 7-programa final" src="https://github.com/user-attachments/assets/e3bda00a-0290-4973-84f3-fd3f5e744e06" />



