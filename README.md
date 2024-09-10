# Plastigesa EIRL - Página Web

Este proyecto fue creado para **Plastigesa EIRL**, una empresa dedicada a la fabricación y comercialización de productos plásticos. La página web fue desarrollada utilizando tecnologías modernas como **Astro**, **Tailwind CSS**, **PNPM**, **Flowbite**, y **Glide.js** para ofrecer una experiencia rápida y eficiente.

Puedes visitar el sitio en [Plastigesa](https://plastigesa.netlify.app/).

<div align="center">
<a href="https://plastigesa.netlify.app/">
<img src="./public/mokup.png">
</a>
<p></p>
</div>

<div align="center">

![Astro Badge](https://img.shields.io/badge/Astro-FF3E00?logo=astro&logoColor=fff&style=flat)
![Tailwind CSS Badge](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?logo=tailwindcss&logoColor=fff&style=flat)
![Flowbite Badge](https://img.shields.io/badge/Flowbite-0284c7?logo=flowbite&logoColor=fff&style=flat)
![pnpm](https://img.shields.io/badge/pnpm-f9ad00?logo=pnpm&logoColor=f9ad00&color=gray)



</div>

## 🚀 Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

## 🚀 Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Card.astro
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

Los archivos `.astro` o `.md` en `src/pages/` son las rutas de las páginas.

Los componentes se encuentran en `src/components/`, donde usamos Astro junto Tailwind.

Los recursos estáticos como imágenes están en la carpeta `public/`.`

## 🧞 Comandos

Para ejecutar el proyecto, usa los siguientes comandos desde la raíz:

| Command                    | Action                                                         |
| :------------------------  | :------------------------------------------------------------- |
| `pnpm install`             | Instala las dependencias                                       |
| `pnpm run dev`             | Inicia el servidor de desarrollo en `localhost:4321`           |
| `pnpm run build`           | Construye el sitio para producción en `./dist/`                |
| `pnpm run preview`         | Previsualiza el sitio antes de desplegarlo                     |
| `pnpm run astro ...`       | Ejecuta comandos de la CLI de Astro `astro add`, `astro check` |
| `pnpm run astro -- --help` | Muestra la ayuda de la CLI de Astro                            |
