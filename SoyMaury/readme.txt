Malas Prácticas dichas en Clase Hasta Ahora


Utilizar tanto id en CSS
Utilizar el !important
Utilizar la etiqueta <style> dentro del archivo html
Utilizar el atributo style dentro de las etiquetas html
Utilizar div para contener todo ignorando los header, nav, section, article, etc.
No utilizar la etiqueta <form> para hacer formularios
Utilizar las etiquetas <select> y <option> para hacer selectores o menús desplegables.
No nombrar el primer archivo html del proyecto como index.html
No tener archivos .css para cada pantalla de un proyecto.
Tener todo el css junto en un solo archivo.
No ponerle el atributo alt a una imagen
Poner imágenes dentro de <div> en vez de <figure>
Utilizar textos solo en mayúscula en HTML, en vez de utilizar el atributo de CSS, text-transform, con el valor uppercase. Ya que al hacer esto pareciera que estuvieras gritando.
Poner videos que se reproduzcan solos.
No optimizar las imágenes.
No tener cuidado de cual es el formato ideal para las imágenes y su respectivo peso.
No tener cuidado con la respectiva semántica de HTML, y con la sintaxis adecuada para CSS.
No cerrar las etiquetas que se cierran en sí mismas como <br/>
No comentar partes esenciales de tu código.
No poner la etiqueta <meta name=”robots” content=”index,follow”> en tu proyecto para que los navegadores los puedan ubicar mejor.
No usar la etiqueta <meta name=”viewpor” content=”width=device-width, initial-scale=1.0”> para hacer tu proyecto responsive.
No poner el atributo autocomplete=”valor” en los campos de tu formulario para hacerle la vida más fácil al usuario
No usar el atributo required en los campos obligatorios de tu formulario como una primera capa de seguridad



En un elemento con display:inline no puedo usar margin ni padding arriba ni abajo, solo derecha e izquierda. Tampoco se puede aplicar width o height.

En un elemento con display:block el contenido del elemento toma el 100% del width, se puede usar margin y padding por todos los lados.

En un elemento con display:inline-block, se puede usar margin y padding por todos lados, así como darle width y height, y el contenido es del mismo tamaño que el elemento.

Etiquetas como p y div vienen por Default con un display:block
Etiquetas como span viene por Default con un display:inline



Mini guía de flexbox:

Propiedades en contenedores padre:
display:flex;
flex-direccion: row | column | row-reverse | column-reverse
flex-wrap: nowrap | wrap | wrap-reverse
Esta siguiente propiedad es un atajo para escribir el flex-direccion y el flex-wrap en una sola línea de código
flex-flow: Primero escribes dirección | Luego escribes flex-wrap
Posicionar horizontal
justify-content: flex-star | flex-end | center | space-around | space-between
Posicionar manera vertical
aling-items: flex-star | flex-end | center | stretch | baseline

aling-content: flex-star | flex-end | center | stretch | space-around | space-between “Aling-conten solo se utiliza varias filas de elementos, pero si es una sola línea usamos aling-items”

Propiedades en elemento hijo

order: ; Esto se utiliza para cambiar el orden de nuestros elementos sin cambiar el orden real semantico y correcto de html. Sencillamente colocando números.

aling-self: aling-items: flex-star | flex-end | center | stretch | baseline “Muy importante, si en el padre del elemento tiene declarado flex-direccion:row; esta propiedad lo acomodara verticalmente. Y si es flex.direccion: column lo ordenara horizontalmente”