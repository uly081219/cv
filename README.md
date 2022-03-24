## 🚀 Entorno de desarrollo

### 👩🏽‍🚒 Herramientas necesarias

1. [Instalar Node.js y npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)
2. Clona este proyecto: `git clone https://github.com/uly081219/cv.git`
3. Acceder a la carpeta del proyecto: `cd cv`

### 🔥 Ejecución de la aplicación

1. Instalar todas las dependecias: `npm install`
2. Construir el sitio web: `npm run build`
3. Inicar el servidor de dessarrollo: `npm run dev`

Puedes acceder al servidor mediante la url: http://localhost:8123

### 👩🏽‍🏫 Explicación del proyecto

Este proyecto pretende ser un sitio web de un currículum vitae en versión digital.

### 🗂 Estructura del proyecto

`tree -L 4 assets  src`

```
src
├── assets
│   ├── fonts
│   │   ├── OpenSans-Light.ttf
│   │   └── PlayfairDisplay-Regular.ttf
│   ├── images
│   │   └── ulyana.webp
│   ├── scripts
│   │   └── main.js
│   └── styles
│       ├── _fonts.scss
│       ├── _icons.scss
│       ├── _variables.scss
│       ├── layouts
│       │   └── _home.scss
│       └── main.scss
├── index.html
└── views
    ├── content.html
    ├── footer.html
    └── header.html

7 directories, 13 files
```

### 📡 Continuous Deployment con netlify

Cada vez que realizamos cambios en la rama main se deploya automáticamente el sitio web en la plataforma netlify

Url del proyecto: https://cranky-yonath-0d947b.netlify.app/

### 🤹 Feliz desarrollo !
