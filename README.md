# Tienda 32 Bits

![Imagen tienda](https://cli.vuejs.org/config/).  
Este proyecto es una aplicación web simple para la gestión de una lista de juegos en una tienda. La aplicación permite ver una lista de juegos con su código, nombre, stock y precio, y proporciona botones para incrementar o disminuir el stock de cada juego.

## Estructura del Proyecto
El proyecto está dividido en varias secciones:

* Template: Define la estructura HTML de la aplicación. [GameList](https://github.com/RerreRojas/tienda-bits/blob/main/src/components/GameList.vue)
* Script: Contiene la lógica de la aplicación en JavaScript, utilizando Vue.js y Vuex.
* Style: Define los estilos CSS para la aplicación.
* Store: Configuración de Vuex para la gestión del estado. [index.js](https://github.com/RerreRojas/tienda-bits/blob/main/src/store/index.js)
`El store Vuex gestiona el estado de la lista de juegos, incluyendo acciones para obtener los datos de los juegos desde un archivo JSON, e incrementar o disminuir el stock de los juegos.`
## Descripción de Funcionalidades
* fetchGames: Acción que obtiene la lista de juegos desde un archivo JSON y la guarda en el estado de Vuex.
* Incrementar: Acción que incrementa el stock de un juego específico.
* Disminuir: Acción que disminuye el stock de un juego específico.

