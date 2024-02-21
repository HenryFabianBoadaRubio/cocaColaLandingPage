# Video de referencia

<iframe width="560" height="315" src="https://www.youtube.com/embed/KP398UANzfw?si=rZW8KDYi1EujsnaW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


1-"ustify-content: center;: Alinea los elementos hijos horizontalmente dentro del contenedor. En este caso, se centran los elementos horizontalmente.

2-align-items: center;: Alinea los elementos hijos verticalmente dentro del contenedor. En este caso, se centran los elementos verticalmente.

3-display: flex;: Establece el contenedor como un contenedor flexible, lo que permite que los elementos hijos se organicen en una fila o en una columna y se ajusten automáticamente según el tamaño del contenedor.

4-cursor: pointer;: Cambia el cursor del mouse a una mano cuando pasa sobre el botón, indicando que es interactivo y se puede hacer clic

5-transition: 0.2s ease;: Aplica una transición suave con una duración de 0.2 segundos cuando hay cambios en las propiedades CSS del botón. Esto proporciona una animación suave cuando se produce un cambio, como un cambio de color al pasar el mouse sobre el botón.

6-La línea de código padding: 0; en CSS establece el relleno de un elemento a 0 píxeles en todas las direcciones. El relleno es el espacio entre el borde de un elemento y su contenido.

Cuando se establece padding: 0;, se elimina cualquier relleno que el elemento pueda tener, lo que significa que el contenido del elemento se colocará directamente contra el borde del mismo. Esto puede ser útil para restablecer el relleno predeterminado de un elemento a cero o para eliminar el espacio no deseado alrededor del contenido.

7-width(ancho), left(izquierda), height(alto)

8-top: La propiedad top en CSS se utiliza para especificar la distancia entre el borde superior de un elemento posicionado y el borde superior de su contenedor posicionado más cercano.

9-position: relative;: Cuando se aplica esta propiedad a un elemento, se mantiene en su posición original en el flujo del documento, pero permite ajustar su posición utilizando las propiedades top, bottom, left y right. Los desplazamientos realizados utilizando estas propiedades se basan en la posición original del elemento. Otros elementos a su alrededor se ajustan como si el elemento mantuviera su posición original, incluso si se desplaza. Esto puede ser útil para mover un elemento ligeramente desde su posición original o para crear un contexto de posicionamiento para los elementos secundarios que tienen position: absolute;.

10-position: absolute;: Esta propiedad posiciona un elemento en relación con su primer ancestro posicionado, que puede ser otro elemento con position: relative;, position: absolute;, o position: fixed;. Si no hay ningún ancestro posicionado, el elemento se posicionará en relación con el documento HTML. Los desplazamientos realizados utilizando las propiedades top, bottom, left y right se basan en el borde del contenedor posicionado más cercano. El elemento es retirado del flujo normal del documento, lo que significa que no afecta la posición de otros elementos.

11-position: fixed;: Esta propiedad posiciona un elemento en relación con la ventana del navegador. No se ve afectado por el desplazamiento de la página y permanece fijo en la misma posición en la ventana, incluso cuando se desplaza la página hacia arriba o hacia abajo. Esto es útil para elementos que deben permanecer visibles en todo momento, como barras de navegación fijas en la parte superior de la página o botones de acción flotantes.