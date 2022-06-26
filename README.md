# Taller spring ARSW

## Nicolas Palacios

## 25/06/2022

### En que consiste el proyecto?

El proyecto consiste en la creacion de un tablero interactivo colaborativo, el proyecto cuenta con 300 lineas y fue realizado en 4 horas.

LOC/H = 74

Comando utilizado para ejecutar servidor web: mvn sprint-boot:run



Para ingresar a la pagina principal se ingresara a http://localhost:8080
El link de heroku es el siguiente:
https://getpostarsw.herokuapp.com/
Nos saldran lo siguiente, donde veremos el status y podremos cambiar nuestro nombre.
<img src= imagen\imagen.png>

tablero, cuanta con la opcion de seleccionar color, borrador simple y borrar el tablero.

<img src= imagen\imagen2.png>



### Diagrama de Clases

<img src="imagen\imagen3.png">  
 

### Documentacion

Para ver la documentacion, se debe realizar el comando mvn javadoc:javadoc, luego en target/../index.html se visualizara esta.

### Estructura de archivos

|\_**\_pom.xml  
|\_\_**src  
| |\_**\_main  
| | |\_\_**java  
| | | |\_**\_edu  
| | | | |\_\_**escuelaing  
| | | | | |\_**\_arsw  
| | | | | | |\_**\_ASE  
| | | | | | | |\_**\_app  
| | | | | | | | |TableroSocket.java  
| | | | | | | | |WebSiteController.java  
| | | | | | | | | | \_**\_resources 
| | | | | | | | | | | \_**\_static
| | | | | | | | | | | | |index.html 
| | | | | | | | | | | | |tablero.html 
| | | | | | | | | | | | |\_**\_css
| | | | | | | | | | | | css.css 
| | | | | | | | | | | | |\_**\_js
| | | | | | | | | | | | js.js 
| | | | | | | | | | | | FirstComponent.jsx 

| |\_\_**test  
| | |\_**\_java  
| | | |\_\_**edu  
| | | | |\_**\_escuelaing  
| | | | | |\_\_**app  
| | | | | | |\_\_\_\_AppTest.java