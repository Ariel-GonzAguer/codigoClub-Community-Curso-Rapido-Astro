# Curso Rápido e Introductorio a Astro 🚀

Este proyecto es un curso rápido e introductorio a Astro, un metaframework moderno para crear sitios web orientados al contenido. A lo largo del curso, haremos un blog sobre café utilizando Astro y sus características.

Para poder  seguir el curso, es necesario tener conocimientos básicos de HTML, CSS y JavaScript. Se usará un poco de React, pero no se requiere experiencia previa en React. También se usarán archivos Markdown para escribir el contenido de los posts.

## Enlaces a páginas relevantes 🛰️

- [Tutorial de Astro](https://docs.astro.build/es/tutorial/0-introduction/) - en español.
- [Markdown](https://www.markdownguide.org/getting-started/) - en inglés.
- [Ejemplo de sitio ya terminado con más funcionalidades](https://astro0.netlify.app/) En este ejemplo uso content-collections, que es una de las características más interesantes de Astro, TypeScript, componentes React **y** Preact, componentes Astro que utilizan componentes de terceros, hooks personalizados y manejo del estado global con Zustand.

## Estructura del Proyecto 🪐

- **src/**: Contiene el código fuente del proyecto.
  - **components/**: Componentes reutilizables de Astro.
  - **pages/**: Páginas del sitio web.
  - **styles/**: Archivos CSS para estilos globales y específicos.
  - **scripts/**: Archivos JavaScript para interactividad.
- **public/**: Archivos públicos accesibles desde el navegador.
  - **imagenes/**: Imágenes utilizadas en el sitio.
- **.vscode/**: Configuración de Visual Studio Code.
- **astro.config.mjs**: Configuración de Astro.
- **tsconfig.json**: Configuración de TypeScript.
- **package.json**: Dependencias y scripts del proyecto.

## Instalación 🌟

1. Clona el repositorio:
   ```sh
   git clone https://github.com/Ariel-GonzAguer/codigoClub-Community-Curso-Rapido-Astro
   ```
2. Navega al directorio del proyecto:
  ```sh
   cd codigoClub-Community-Curso-Rapido-Astro/
  ```
3. Instala las dependencias:
   ```sh
   npm install
   ```
4. Inicia el servidor de desarrollo:
   ```sh
   npm run dev
   ```

El sitio estará disponible en http://localhost:4321. En caso de no estar disponible, puede tomar el puerto 4322.

5. Para generar el sitio para producción:
   ```sh
   npm run build
   ```

## Créditos 👨🏼‍🚀
Inspirado en el tutorial oficial de Astro.