# Straight to Heaven - Centro de Innovación y Software

Proyecto de desarrollo web creado para la Solemne 01. Consiste en un sitio web corporativo de 7 páginas para una empresa que ofrece servicios de vanguardia, incluyendo bienes raíces espaciales, inversiones en la NYSE, exchange de criptomonedas y venta de patentes de servidores.

## Características del Proyecto

* **Cumplimiento de Rúbrica:** 7 páginas en total interconectadas.
* **Integración Mixta:** 2 páginas desarrolladas con el framework Bootstrap 5 (`index.html` y `equipo.html`) y 5 páginas desarrolladas con HTML5 semántico y CSS3 puro.
* **Coherencia Visual:** Diseño unificado a través de variables CSS globales, manteniendo la misma paleta de colores y estructura en todo el sitio.
* **Formulario Estructurado:** Página de contacto con validación básica de HTML5.
* **Despliegue en Contenedores:** Configurado para ejecutarse a través de Docker utilizando un servidor Nginx.

## Tecnologías Utilizadas

* HTML5 Semántico
* CSS3 (Variables, Flexbox)
* Bootstrap 5.3.3 (vía CDN)
* Docker (Nginx Alpine)

## Estructura de Archivos

```text
/
├── css/
│   └── styles.css
├── index.html        (Bootstrap)
├── equipo.html       (Bootstrap)
├── nosotros.html     (CSS Puro)
├── servicios.html    (CSS Puro)
├── recursos.html     (CSS Puro)
├── contacto.html     (CSS Puro)
├── faq.html          (CSS Puro)
├── Dockerfile
└── .dockerignore
