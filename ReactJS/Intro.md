ReactJS es una biblioteca de Javascript, orientada a frontend, que sirve para construir interfaces de usuario basadas en [componentes](Conceptos%20de%20React.md). Tiene la particularidad de poder ejecutarse en múltiples plataformas al mismo tiempo, tanto en el frontend como en el backend, como por ejemplo web, aplicaciones terminal-based, mobile apps, etc.

ReactJS es **declarativo**, que quiere decir que no necesitamos especificar tánto las instrucciones dentro del programa para que realice tal o cual acción, podemos permitirnos ser más generales.

Por ejemplo, normalmente en Javascript, para implementar un botón que sea dinámico y cambie su texto interno cada vez que es presionado, como un *follow* de Twitter, deberíamos hacer algo así:

```javascript
const btn = document.querySelector('#btn')
button.addEventListener('click', () => {
    if (button.classList.contains('follow'){
        button.classList.remove('follow');
        button.innerText = 'Siguiendo';
    } else {
        button.classList.add('no-follow');
        button.innerText = 'Seguir'
    }
})
```

Esto en ReactJS no llevaría tanto código ni sería tan específico ni repetitivo, considerando que tendremos que hacer esto mismo para cada botón que queramos. Más adelante veremos un ejemplo...
# Ventajas de React
- Es recontra demandado, tiene muchísima salida laboral
- Se pueden hacer apps mobile y de escritorio con React Native, usando el mismo código sin importar la plataforma
- Tiene mantenimiento asegurado, no se va a morir en muchísimo tiempo
- Tiene una comunidad inmensa. Hay soluciones literalmente para todo
- Aprender React ayuda a aprender otros frameworks, como Svelte, Vue, Angular, etc. (y viceversa)
- Tiene una proyección enorme, ya que permite hacer un montón de cosas
- Tiene una Api estable, es decir que cambia poco y encima mejora, lo que no es un problema al actualizar entre versiones y código viejo
