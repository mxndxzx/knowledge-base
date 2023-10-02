A continuación explicaremos algunos conceptos claves para entender a detalle el funcionamiento de ReactJS sobre Javascript y sus entornos.
## Componentes
Los **componentes** no son más que porciones de la interfaz visual que podremos repetir según queramos, incluyendo todas sus acciones y comportamientos. Pueden ser botones, modales, cards, carruseles, cuadros, etc.

Estos componentes, como mencionamos antes, pueden tener comportamiento propio (como el ejemplo del botón) declarado por funciones

En esto se basa ReactJS, en **reutilizar componentes** tantas veces como queramos. De esta manera, construir interfaces visuales, como la de Twitter, no resulta tan complicado. Mirando específicamente la de Twitter, podemos ver que no son más que componentes en forma de tweets, cartas, botones, retweets, comentarios, etc.

El esquema no cambia, se ve exactamente igual, lo único que cambia es el contenido (texto, imágenes, números, etc.)

## Renderizado
ReactJS muestra estos componentes en pantalla mediante el uso de un **Virtual DOM** y el **renderizado**.

¿Qué quiere decir esto? Que el **Virtual DOM** es una representación del DOM nativo de Javascript, pero que se compara constantemente contra este mismo. Cada vez que ocurre un cambio en el Virtual DOM lo compara contra el DOM nativo y actualiza los cambios.

Esto permite una función bastante copada llamada **Lazy Loading**, que permite recargar solo una parte de la página sin refrescar todo el navegador o la app.

El **renderizado** es parte de esto. Simplemente lo que hace es que cada vez que el Virtual DOM se actualiza, efectúa propiamente los cambios necesarios. Es un concepto muy parecido a *"imprimir en pantalla"* un componente.