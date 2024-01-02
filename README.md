# Blog con CRUD de posts

Web app realizada con reactjs, componentes de material UI, dummy backend con mockapi & firebase para cloud storage de imagenes.

Instalacion inicial :

### `npm install`

El mismo va a instalar las dependencias necesarias como son Axios para endpoint request, material UI para componentes de layout, firebase para cloud image storage.

## Correr el proyecto

Para ejecutar de manera local :

### `npm start`

Corre la aplicacion en development mode.\
Se abre en [http://localhost:3000](http://localhost:3000) en tu navegador preferido.

## Endpoints

API de blog: https://65305bc56c756603295e8df4.mockapi.io/api/v1/blogposts

API de usuarios: https://65305bc56c756603295e8df4.mockapi.io/api/v1/users

## Usuario base

User: admin
Password: 123455

## Mejoras a futuro

Si bien el proyecto esta completamente funcional, podrian sumarse funcionalidades para mejorar la experiencia de usuario.

-   Agregar el nombre de la imagen al lado del boton adjuntar, una vez que finalizo la carga con un action que permita removerla.
-   Posibilidad de edición de posts, sumando un badge de post editado
-   Dar feedback al usuario mientras se procesa la informacion y se carga el post (un loader y un badge de reclamo enviado exitosamente)
-   Creacion de distintos roles para definir permisos de edicion y borrado, creacion y solo lectura.
