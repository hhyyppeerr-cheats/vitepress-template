# Template Vitepress

Este template es un proyecto base para crear documentación, tomar notas o escribir un blog con [Vitepress](https://vitepress.vuejs.org/).

## Instalación

1. Clonar este repositorio

```bash
git clone
```

2. Instalar dependencias

```bash
npm install
```

3. Iniciar servidor de desarrollo

```bash
npm run dev
```

Listo! Ya puedes empezar a escribir tus archivos `.md`.

## Personalización

En el archivo `docs/.vitepress/config.js` puedes personalizar el título del sitio, la descripción, el idioma, el tema, etc.

## Despliegue

Usa `run build` para generar los archivos estáticos en la carpeta `dist`.

## Acciones de github

Puedes configurar una acción de github para que se ejecute cada vez que haces un push a la rama `main` y así desplegar automáticamente tu sitio en github pages.

1. En la carpeta `.github/workflows` hay un archivo llamado `deploy.yml`. Donde puedes configurar tu despliegue. Por defecto está configurado para que se ejecute cada vez que haces un push a la rama `main`, buscando la carpeta `dist`.
