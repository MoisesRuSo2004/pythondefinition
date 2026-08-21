# Python | Minería de Datos II

> Una página web estática, clara y responsive para presentar los conceptos esenciales del lenguaje de programación Python.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Responsive](https://img.shields.io/badge/diseño-responsive-1f6feb?style=flat-square)

## Descripción

Este pequeño proyecto presenta una introducción visual a Python, con un enfoque pensado para el aprendizaje y la consulta rápida. El contenido explica qué es Python, su origen, su naturaleza, sus capacidades y cuatro características fundamentales.

La interfaz utiliza una composición limpia con navegación interna, bloques de contenido, jerarquía tipográfica y adaptación para pantallas pequeñas.

## Contenido de la página

La web está organizada en tres secciones principales:

| Sección | Contenido |
| --- | --- |
| **Inicio** | Presentación general de Python y un resumen de sus ventajas. |
| **Definiciones** | Definición, origen, naturaleza y capacidad del lenguaje. |
| **Características** | Python interpretado, de tipado dinámico, multiparadigma y multiplataforma. |

El pie de página identifica la asignatura **Minería de Datos II** y cierra la experiencia con una frase temática.

## Estructura del proyecto

```text
.
├── index.html   # Estructura y contenido de la página
├── style.css    # Diseño visual, distribución y responsive
└── README.md    # Documentación del proyecto
```

## Tecnologías utilizadas

- **HTML5** para la estructura semántica del documento.
- **CSS3** para estilos, variables de diseño, cuadrículas y media queries.
- **Google Fonts** para cargar la familia tipográfica Inter.
- **CSS Grid** para organizar el hero, las definiciones y las características.
- **Navegación con anclas** para desplazarse entre secciones sin JavaScript.

## Diseño y experiencia

- Paleta basada en azules, blancos y tonos oscuros para reforzar la temática tecnológica.
- Encabezado fijo con efecto de transparencia y desenfoque.
- Sección hero con presentación y tarjeta de resumen.
- Tarjetas de contenido con bordes suaves y sombras ligeras.
- Desplazamiento suave entre las secciones.
- Diseño responsive: las cuadrículas pasan a una sola columna en pantallas de hasta `820px`.
- Navegación adaptable para dispositivos móviles.

## Cómo ejecutar el proyecto

No es necesario instalar paquetes ni configurar un servidor.

### Opción 1: abrir directamente

Haz doble clic en `index.html` para abrir la página en el navegador.

### Opción 2: servidor local

Desde la carpeta del proyecto, ejecuta uno de estos comandos:

```bash
# Con Python
python -m http.server 8000
```

Después visita [http://localhost:8000](http://localhost:8000).

También puedes utilizar la extensión **Live Server** de Visual Studio Code para obtener recarga automática durante la edición.

## Personalización

### Cambiar el contenido

Edita `index.html` para modificar:

- El título de la pestaña y los textos de cada sección.
- Los enlaces del menú y sus identificadores (`id`).
- Las definiciones y características mostradas.
- La información del pie de página.

### Cambiar el aspecto visual

Edita `style.css`. Las variables principales se encuentran al inicio del archivo:

```css
:root {
    --bg: #f4f7fb;
    --primary: #1f6feb;
    --primary-dark: #114ea8;
    --text: #1d2433;
    --muted: #5f6f89;
}
```

Desde ese bloque puedes ajustar rápidamente la paleta, mientras que las reglas `@media` permiten adaptar el diseño a nuevos tamaños de pantalla.

## Objetivo académico

El proyecto sirve como una introducción sencilla a Python y, al mismo tiempo, como ejemplo de una página web estática estructurada con HTML semántico y CSS moderno. Puede utilizarse como base para añadir ejemplos de código, una línea de tiempo del lenguaje o nuevos temas de Minería de Datos II.

## Autoría

Proyecto educativo desarrollado para **Minería de Datos II**.
