# GeneaPro - Suite Genealógica Profesional

GeneaPro es una aplicación web interactiva que permite transformar texto estructurado (formatos jerárquicos como `1.`, `1.1.`, `1.1.2.`) en árboles genealógicos visuales e interactivos.

## Características Principales
* **Parseador Automático:** Convierte texto pegado desde un documento de Word (`.docx`) o Bloc de notas en estructuras de datos genealógicas de forma inteligente.
* **Visualización D3.js:** Explora el árbol genealógico de manera gráfica con soporte de zoom, colapso de ramas, y búsqueda inteligente de familiares.
* **Fichas Detalladas:** Panel lateral interactivo para ver la biografía completa de los miembros.
* **Exportación Múltiple:** Exporta tu trabajo en PNG, SVG vectorial, Estructura JSON, GEDCOM y HTML interactivo autónomo.

## Uso
Esta herramienta es 100% *Client-Side* (todo ocurre en tu navegador, garantizando la privacidad de tus datos). No se envían datos a ningún servidor externo.

Visita la versión en vivo alojada en GitHub Pages:
👉 **[Enlace a tu GitHub Pages aquí]**

## Versiones Disponibles en este Repositorio
1. **`index.html`**: Versión principal y ultra ligera. Utiliza CDNs para cargar el diseño (Requiere conexión a internet para renderizar los iconos y tipografías).
2. **`GeneaPro_Offline.html`**: Versión "Stand-alone" de peso completo con todas las librerías empaquetadas en un solo archivo. Ideal para descargar, llevar en una memoria USB y utilizar en zonas sin acceso a internet.

## Tecnologías Utilizadas
* HTML5, CSS3, JavaScript (ES6)
* [Tailwind CSS](https://tailwindcss.com/) (Diseño)
* [D3.js](https://d3js.org/) (Gráficos interactivos)
* [Mammoth.js](https://github.com/mwilliamson/mammoth.js) (Extracción de texto local)
