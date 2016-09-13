# 4Talent Test
## Objectivo:
Crear una aplicación (Rails + React) que permita consumir la API de http://openweathermap.org/api. La aplicación debe cumplir los siguientes requisitos:
- El proyecto debe estar en Rails con la gema de 'react-rails'
- El proyecto debe estar con git en github.com en un repositorio publico
- Se debe crear un componente de React que consuma la API OpenWeatherMap y debe renderizar la temperatura de las siguiente ciudades:
  - Santiago
  - Buenos Aires
  - Lima
  - Sao Pablo
- El componente debe almacenar dichas temperaturas en la base de datos a través de una API creada en el proyecto (Backend Rails)
- El componente debe poseer un botón que permita refrescar las temperaturas de las ciudades y actualizarlas en la base de datos del proyecto
- Se debe dejar un historial de las temperaturas
- Las vistas debe tener un minimo de diseño y usabilidad

## Casos de uso:
- El componente debe obtener la información de la base de datos local, si no existe la información debe ir a buscarla a la API de OpenWeatherMap.
- Si el usuario presiona el botón de actualizar temperaturas debe consumir la API de OpenWeatherMap para traer la nueva información.
