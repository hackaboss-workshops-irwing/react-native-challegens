# News App Challenge

## Descripción

Se requiere hacer una aplicación de noticias para la empresa News de España. Esta empresa se dedica a las noticias en tres ciudades del país: Barcelona, Madrid y Valencia.

En su modelo de negocio es importante que las noticias estén separadas según el país. Por lo tanto, se requiere que la aplicación tenga un menú principal donde el usuario pueda seleccionar la ciudad de su interes, es importante destacar que el usuario podrá cambiar luego de ciudad en cualquier momento, sin tener que volver a la pantalla de selección de ciudad. La ciudad seleccionada debe quedar almacenada de manera que el usuario al volver a abrir la aplicación, se le muestre la última ciudad que seleccionó.

Una vez seleccionada la ciudad, se debe mostrar una lista de noticias, donde cada noticia debe contener: imagen, título y breve descripción. Al hacer touch en una noticia, se debe mostrar el detalle de la misma, donde se debe mostrar la imagen, el título, y la descripción completa del contenido y un botón para volver a la lista de noticias.

Si bien el equipo de BackEnd no ha creado un paginado para solicitar las noticias se requiere que la aplicación las muestre de 10 en 10 con un botón que solicite al usuario consultar mas noticias, si el usuario llega al final de la lista de noticias, el botón debe desaparecer.

Las noticias se proporcionan de un servicio BackEnd que ha desarrollado el equipo de la empresa y que se encuentra en la siguiente URL: https://jsonplaceholder.typicode.com/ debe leer la documentación y utilizar el servicio de posts y el servicio de photos.

## Requerimientos

Para el desarrollo de la aplicación se requiere utilizar las siguientes herramientas o similares:
- Usar React Native ó Expo
- Usar React Navigation
- Usar estados globales para controlar la ciudad seleccionada
- Usar LocalStorage para almacenar la ciudad seleccionada
- Usar Git para el control de versiones
- Usar Github para compartir el código del proyecto
- Crear y configurar todos los assets necesarios para la aplicación (logo, splash, favicon y demás assets necesarios)

## Diseño

El diseño de la aplicación es libre, se puede utilizar cualquier librería de componentes o hacer los componentes desde cero. Pero se debe cumplir con el diseño mínimo que se adjunta en las imagenes.

## Se valora

- Entrega del proeyecto en repositorio github rama main
- Utilizar README.md para documentar el proyecto y explicar como instalarlo y ejecutarlo
- Utilizar commits semánticos para documentar los avances del proyecto