React es una librería de JS que aprovecha el uso de componentes. Es reactiva, por eso se llama react, porque reacciona a las peticiones y usuarios.
# Conocimientos previos
HTML, CSS y Javascript, mientras más mejor
# Instalación
Hay que tener estos programas instalados:
- Chrome
- Editor de código (Vim, Vsc, etc.)
- Git (must have)
- NodeJS (otro must have)
- Postman (para consumir api's)
- MongoDB (nativo)
- Mongo compass (DB con interfaz de usuario, corte pgadmin)
- React Dev Tools
- Redux Dev Tools
**- Extensiones de VSC**
	- Simple React Snippets (logo de react azul)
	- ES7+ React/Redux/React-Native snippets (mismo logo)
# Hola mundo
Antes que nada, hay que usar Vite, que es un server local de desarrollo, que nos va a permitir armar una app de react con una plantilla, en vez de hacer todo nosotros como unos boludos.
Vite usa HMR para actualizar componentes individuales y no toda la página, corte lazy loading.
Se usa con NPM, conviene leer la [doc oficial](https://vitejs.dev/guide/)

> **Swc?** Es un compilador de JS, no es necesario usarlo pero conviene, mil veces mejor

Una vez iniciado el proyecto con Vite, vemos una banda de carpetas, un index.html, etc. etc.
Hay varios scripts para ejecutar y buildear la app, y muchos más. Es cuestión de ir probando.
Nosotros trabajamos siempre sobre la carpeta `src`, SIEMPRE.

> React en si es el entorno donde trabajamos. React-DOM es la librería que permite que todo lo que hicimos en React se pueda ver en web.

Adentro de  `src`  tenemos varios archivos .jsx y .css. Por ahora los dejamos así, solo los miramos. JSX es Javascript con papota.
