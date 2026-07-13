# Maquetación adaptativa y accesible

Proyecto desarrollado como parte del ejercicio práctico **Maquetación Adaptativa y Accesible - Implementación Vanilla I** de IT Academy.

La aplicación reproduce visualmente la página de inicio de sesión del servicio oficial de venta de entradas del Musée du Louvre. 

El objetivo principal del ejercicio es practicar la creación de layouts con HTML y CSS sin utilizar frameworks ni librerías externas.

## Demo

La página está publicada en Netlify:

[Ver la aplicación desplegada](https://stirring-selkie-84fb14.netlify.app/)

## Repositorio

[Ver el repositorio en GitHub](https://github.com/alefelipin/maquetacion-itacademy)

Rama utilizada para esta implementación: feature/vanilla-implementation

## Objetivos del ejercicio

- Practicar CSS Grid para construir layouts complejos.
- Utilizar Flexbox para alinear y distribuir elementos dentro de los componentes.
- Aplicar una estructura HTML semántica.
- Reproducir un diseño de referencia mediante HTML y CSS.
- Organizar correctamente los archivos y recursos del proyecto.
- Aplicar buenas prácticas básicas de accesibilidad y maquetación.
- Publicar una aplicación web estática.

## Características principales

- Cabecera con navegación principal.
- Área de identificación de usuario.
- Campos para correo electrónico y contraseña.
- Sección de preguntas frecuentes.
- Pie de página con información y enlaces del museo.
- Uso combinado de CSS Grid y Flexbox.
- Imágenes con textos alternativos.
- Estructura creada con elementos semánticos como `header`, `nav`, `main`, `section` y `footer`.
- Despliegue mediante Netlify.

> Este proyecto es una reproducción educativa de una interfaz existente. No está relacionado oficialmente con el Musée du Louvre y el formulario no realiza una autenticación real.

## Tecnologías utilizadas

- **HTML5:** estructura y contenido de la página.
- **CSS3:** maquetación, estilos visuales y distribución de los elementos.
- **CSS Grid:** organización del layout general y de la sección de acceso.
- **Flexbox:** alineación de la navegación y de diferentes elementos internos.
- **Git y GitHub:** control de versiones y alojamiento del código.
- **Netlify:** despliegue de la aplicación web.

No se utilizan frameworks de CSS, librerías de JavaScript ni dependencias externas.

## Estructura del proyecto

```text
maquetacion-itacademy/
├── index.html
├── src/
│   ├── assets/
│   │   ├── icons/
│   │   ├── img/
│   │   └── logos/
│   └── css/
│       └── style.css
├── recommendations/
├── .gitignore
└── README.md
```

### Archivos principales

- `index.html`: contiene la estructura y el contenido de la página.
- `src/css/style.css`: contiene los estilos y la maquetación.
- `src/assets/img/`: almacena las imágenes principales.
- `src/assets/icons/`: contiene los iconos utilizados en la interfaz.
- `src/assets/logos/`: contiene los logotipos del pie de página.
- `recommendations/`: incluye documentación y recomendaciones proporcionadas para el ejercicio.


En la implementación se han aplicado algunas medidas básicas de accesibilidad:

- Uso de elementos HTML semánticos.
- Uso del tipo `password` para ocultar visualmente la contraseña.
- Textos comprensibles en botones y enlaces.
- Jerarquía de encabezados para organizar el contenido.

Como mejoras futuras se pueden incorporar:

- Etiquetas `label` asociadas explícitamente a los campos del formulario.
- Un elemento `form` para agrupar correctamente los controles de acceso.

## Diseño adaptable

La distribución de la página se ha construido utilizando CSS Grid y Flexbox.

Para completar una estrategia totalmente mobile-first se pueden añadir:

- Estilos base orientados a pantallas pequeñas.
- Media queries para tablets y pantallas de escritorio.
- Anchuras máximas para evitar que el contenido se extienda demasiado.
- Reorganización vertical del formulario y del pie de página en dispositivos móviles.
- Imágenes adaptables mediante `max-width: 100%`.


## Autor

Desarrollado por [alefelipin](https://github.com/alefelipin) como ejercicio formativo de IT Academy.

## Estado del proyecto

Versión correspondiente a la primera implementación realizada con HTML y CSS Vanilla.
