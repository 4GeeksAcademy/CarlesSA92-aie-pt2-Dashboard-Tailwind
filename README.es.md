# HTML + Tailwind CSS v4 (CLI local)

Proyecto inicial para construir una web usando solo HTML y Tailwind CSS v4 con compilación local.

> Tienes un video tutorial sobre [cómo usar esta plantilla para crear tu primer sitio web aquí](https://youtu.be/dfbDCMu_p-0).

## Reglas del proyecto

- Usa exclusivamente HTML y Tailwind CSS.
- No uses React, Vue, Angular, Svelte ni frameworks de UI en JavaScript.
- Usa Tailwind CSS v4.
- No uses `cdn.tailwindcss.com` ni `@tailwindcss/browser`.

## ¿Qué hacer a continuación?

Crea un archivo `index.html` con [la estructura básica de HTML](https://4geeks.com/es/lesson/what-is-html-learn-html-es#estructura-de-pgina) y ve el resultado en vivo corriendo un servidor web utilizando el siguiente comando:

```bash
$ pip3 install flask && python3 server.py
```

- Puedes crear tantos archivos HTML cómo desees.
- También puedes crear archivos CSS e importarlos en tu página web utilizando una etiqueta `<link>` ubicándola entre las etiquetas `<head></head>`, de la siguiente manera:

```html
<head>
  ...
  <link rel="stylesheet" type="text/css" href="styles.css">
  ...
</head>
```

- Instala dependencias y compila Tailwind en local:

```bash
npm install
npm run build
```

- Para desarrollo con recarga de estilos:

```bash
npm run dev
```

- Enlaza la hoja compilada en el HTML:

```html
<head>
  ...
  <link rel="stylesheet" href="./src/output.css">
  ...
</head>
```


## Agradecimientos

Esta y otras plantillas son utilizadas para [aprender a programar](https://4geeksacademy.com/es/aprender-a-programar/aprender-a-programar-desde-cero) por parte de los alumnos de 4Geeks Academy [Coding Bootcamp](https://4geeksacademy.com/us/coding-bootcamp). 

Realizado por [Alejandro Sánchez](https://twitter.com/alesanchezr) y muchos otros contribuyentes. 

Conoce más sobre nuestros [Cursos de Programación](https://4geeksacademy.com/es/curso-de-programacion-desde-cero/?lang=es) para convertirte en [Full Stack Developer](https://4geeksacademy.com/es/desarrollador-full-stack/desarrollador-full-stack), o nuestro [Data Science Bootcamp](https://4geeksacademy.com/es/coding-bootcamps/curso-datascience-machine-learning).
