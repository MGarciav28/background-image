# TEXTO TRANSPARENTE CON IMAGEN DE FONDO.

Esta práctica consiste en generar un encabezado H1 cuyo contenido es una imagen de fondo. 

![](images/ejemplo.png)

En esta practica se hacen uso de 2 elementos de HTML,  un div contenedor y un H1.

Al *div* contenedor se el aplican `display: flex`  y `align-items: center`.

Al *H1* se le aplican las propiedades `text-align: center` para centrarlos.  
`background-image:url('images/sky.jpg')` para poner la imagen de fondo  
`background-position-x` y `background-position-y` para alinear la imagen.

La propiedad `background-clip:text` es la que determina que el area visible del fondo sea igual al texto.  
Esta propiedad va acompañada de su *-webkit* para aumentar la compatibilidad en diferentes navegadores.

### Comportamiento responsive
En este ejemplo se utiliza un mediaquery para pantallas menores a 900px, donde se aplican las propiedades  
`font-size: 20vw` para ajustar el tamaño del texto en relacion con el ancho de la pantalla y `background-size: 100vw` para dimensionar la imagen con respecto al ancho de la pantalla.
