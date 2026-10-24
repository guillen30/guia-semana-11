# Página personal

Sitio estático desarrollado con HTML y CSS. Incluye una presentación, una sección de intereses y enlaces a recursos de desarrollo web.

## Uso

Abrir `index.html` en un navegador. No requiere instalación ni compilación. Los estilos y la imagen se cargan desde archivos locales; los enlaces externos necesitan conexión a Internet.

## Estructura

```text
index.html              Contenido y estructura de la página
styles.css              Estilos y distribución adaptable
assets/escritorio.svg   Ilustración del escritorio
```

## Contenido y diseño

La página se divide en presentación, información personal, intereses y sitios favoritos. El menú permite desplazarse entre secciones y el pie incluye un enlace para volver al inicio.

El HTML utiliza `header`, `nav`, `main`, `section` y `footer` para organizar el contenido. Los títulos siguen una jerarquía de `h1` a `h3`, y los intereses se agrupan en una lista. La ilustración tiene texto alternativo.

En escritorio, la presentación se distribuye en dos columnas y los intereses en tres tarjetas. En pantallas de hasta 700 píxeles, el contenido pasa a una columna. Los enlaces muestran un contorno al recibir el foco del teclado y el desplazamiento suave se desactiva cuando está activada la preferencia de movimiento reducido.

## Comprobaciones

- Vistas de 1440 × 1000 y 390 × 844 píxeles sin desbordamiento horizontal.
- Carga de la ilustración local.
- Destinos válidos para los enlaces internos.
- Navegación a la sección de enlaces y regreso al inicio.

