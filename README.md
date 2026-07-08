# Reporteria Comercial Instituto Bruner

Panel HTML estatico para publicar en GitHub Pages.

## Publicacion en GitHub Pages

1. Crear un repositorio nuevo en GitHub, por ejemplo `reporteria-bruner`.
2. Subir el contenido de esta carpeta a la rama principal.
3. En GitHub: Settings > Pages.
4. Source: Deploy from a branch.
5. Branch: `main`, folder `/root`.
6. Guardar.

La URL queda con este formato:

`https://USUARIO.github.io/reporteria-bruner/`

## Actualizacion compartida

El boton `Actualizar todo` ya apunta al backend publicado en Google Apps Script con la cuenta `admbrunerinstituto@gmail.com`.

Backend actual:

`https://script.google.com/macros/s/AKfycbyhKiGC0ZzG2KpOc-TRoOih2qXUTsG2ckWi98Blyc1j0Fma_R0ec5QcAoysElUBvCo/exec`

Este backend trae datos de Google Sheets y esta preparado para sumar HubSpot cuando se cargue el token privado.

## HubSpot

En Apps Script, guardar el token privado de HubSpot en:

Project Settings > Script Properties

Nombre:

`HUBSPOT_PRIVATE_APP_TOKEN`

Valor:

token privado de HubSpot.

No pegar tokens dentro del HTML ni dentro del codigo publico del repositorio.
