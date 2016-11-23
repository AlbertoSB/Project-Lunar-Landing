# Lenguaje de Marcas y Sistemas de Gestión de la Información
## Tarea 02.3: Project-Lunar-Landing

Para esta tarea se han realizado 3 documentos HTML y 2 CSS. 

Los documentos HTML constan de:
* Una página de inicio.
* Una página con información acerca del creador.
* Una página con instrucciones para manejar la nave.

En cuanto a los CSS tenemos dos versiones:
* Una para escritorios, con una resolución mayor a 721px.
* Una para dispoditivos móviles, con una resolución máxima de 720px.

Así pues, la tarea de realizar la parte HTML y CSS del _Project Lunar Landing_ se puede dividir en 3 fases:  
1. Búsqueda y edición de las imágenes a utilizar.  
2. Creación de las 3 páginas web, sin estilos.  
3. Creación del documento CSS para escritorio y posterior adaptación para dispositivos móviles.  
4. Validación de los textos.  


#### 1. Imágenes
Se han buscado por internet varias imágenes que no tuvieran problemas de derechos de autor: una nave espacial, un fondo oscuro con estrellas y una foto de la superficie lunar. La última imagen ha sido editada con GIMP 2 para que su fondo sea transparente y así poder ponerla encima del fondo estrellado sin que quede mal y además se han realizado dos versiones, una más pequeña para dispositivos móviles y otra de mayor tamaño para escritorios (quedaba demasiado pixelada la imagen pequeña como para usarla en ambos casos).  
Todas las imágenes han sido procesadas con PNGGauntlet para que ocupen un menor espacio y así aligerar la carga de la web. 


#### 2. HTML
Se ha realizado un página sencila, con una lista ordenada de control panel y otra desordenada para las opciones. También se ha añadido la foto de la nave y los enlaces para las dos versiones de css, dependiendo se su tamaño. Para ello se han utilizado las expresiones:
* link rel="stylesheet" type="text/css" media="screen and (min-width: 721px)" href="css/deskop.css"
* link rel="stylesheet" type="text/css" media="screen and (max-width: 720px)" href="css/mobile.css"

A continuación se ha realizado la página _About_, con información del creador de los documentos y la las webs utilizadas para su elaboración escritas en diferentes líneas usando **p**. También se ha copiado la lista de opciones para poder navegar de un documento a otro.

Por último se ha realizado la página con las instrucciones de uso, en la que se ha creado una lista desordenada con las instrucciones y se ha vuelto a copiar la lista de opciones.


#### 3. CSS

Una vez realizados los documentos html se ha realizado un hoja de estilos, en la cual hemos puesto nuestro fondo enlazado con una ruta relativa. También hemos quitado los márgenes para que el fondo ocupe todo el espacio y se ha puesto la letra con la fuente Arial y de color blanco. Se ha puesto la lista _Panel Control_ en la esquina superior derecha, añadiendo un borde, y la lista de _Options_ en la esquina superior izquierda. Esta lista se ha puesto para que sea desplegable, creando un rectángulo negro con las letras blancas desde donde podemos acceder a las otras dos páginas. 

La nave se ha situado en la parte superior central y para los párrafos usados en la página _About_ se ha creado algo de espacio para que no empezaran las letras tan pegadas al borde.

Finalmente se ha puesto la imagen del suelo lunar en la parte inferior, de forma que ocupe todo el ancho de la pantalla.

Este documento ha sido adaptado a dispositivos móviles reduciendo los valores de los márgenes, los bordes, el tamaño de la letra, y colocando una imagen del suelo lunar de un tamaño inferior y menos pesada, la cual al ser la pantalla más pequeña se muestra sin demasiada pixelación. También se ha quitado el fondo negro del _Panel de Control_ para que en caso de dispositivos muy estrechos, no tape a la nave.


### 4. Validación

Una vez realizado todo, se ha comprobado la validez de los 5 documentos en sus respectivas webs para [HTML](https://validator.w3.org/) y [CSS](https://jigsaw.w3.org/css-validator/), comprobándose que todo estaba correcto antes de dar el trabajo como finalizado. 
