# Ejercicios de HTML y CSS

Repositorio de prácticas básicas y progresivas de desarrollo web con HTML y CSS. Cada carpeta contiene un ejemplo independiente pensado para aprender, modificar y comparar conceptos fundamentales sin dependencias ni herramientas de compilación.

## Tecnologías utilizadas

- **HTML5**: estructura, contenido semántico y formularios.
- **CSS3**: estilos, modelo de cajas, fondos, tipografía, posicionamiento y diseño flotante.
- **Recursos estáticos**: imágenes locales en formato PNG, JPEG e ICO.
- **Sin frameworks ni paquetes**: las prácticas funcionan directamente en el navegador.

## Funcionalidades y conceptos practicados

- Primer documento HTML y jerarquía de encabezados.
- Texto, enlaces, imágenes, figuras y elementos multimedia básicos.
- Listas ordenadas, desordenadas y anidadas.
- Tablas y estilos aplicados a sus celdas.
- Formularios con campos de texto, correo electrónico y mensaje.
- Selectores, pseudoclases y propiedades visuales de CSS.
- Modelo de cajas: ancho, alto, margen, relleno y bordes.
- Posicionamiento fijo y relativo.
- Diseño con `float`, elementos flotados y `clear`.
- Fondos con imágenes, posición fija y transparencia con `rgba`.
- HTML semántico: `header`, `nav`, `section`, `article`, `aside` y `footer`.
- Metadatos para descripción, palabras clave y favicon.
- Rutas relativas, rutas absolutas y enlaces internos entre páginas.

## Prácticas incluidas

| Práctica | Contenido trabajado |
| --- | --- |
| [HolaMundo](./HolaMundo/) | Documento básico, título, cuerpo y encabezados |
| [Página Web](./P%C3%A1gina%20Web/) | Texto, enlaces, listas, definiciones, imágenes, tabla, metadatos y favicon |
| [Formulario](./Formulario/) | Formulario HTML básico |
| [Formulario con CSS](./Formulario%20con%20CSS/) | Campos estilizados, etiquetas y botón de envío |
| [Mi primer sitio con CSS](./Mi%20primer%20sitio%20con%20CSS/) | Selectores, enlaces, encabezados y estilos generales |
| [Modelo de cajas](./Modelo%20de%20cajas/) | Width, height, margin, padding y border |
| [Posicionamiento de cajas](./Posicionamiento%20de%20cajas/) | `position: fixed`, `relative` y otros tipos de posicionamiento |
| [Imagen flotada](./Imagen%20flotada/) | `float`, distribución de elementos y propiedad `clear` |
| [Imágenes](./Im%C3%A1genes/) | Inserción y contención de imágenes |
| [Fondos](./Fondos/) | Imágenes de fondo, repetición, posición, adjuntado y transparencia |
| [Texto y tipografía](./Texto%20y%20tipograf%C3%ADa/) | Color, alineación, espaciado y presentación del texto |
| [Listas](./Listas/) | Menús de navegación y listas ordenadas, desordenadas y anidadas |
| [Enlaces](./Enlaces/) | Estados `link`, `hover`, `active` y `visited` |
| [Tablas](./Tablas/) | Filas, celdas y diseño tabular |
| [Layout - Estructura de contenido](./Layout%20-%20Estructura%20de%20contenido/) | Maquetación semántica con cabecera, navegación, artículos, barra lateral y pie |

## Estructura del repositorio

```text
.
├── HolaMundo/
├── Página Web/
├── Formulario/
├── Formulario con CSS/
├── Mi primer sitio con CSS/
├── Modelo de cajas/
├── Posicionamiento de cajas/
├── Imagen flotada/
├── Imágenes/
├── Fondos/
├── Texto y tipografía/
├── Listas/
├── Enlaces/
├── Tablas/
└── Layout - Estructura de contenido/
```

Cada práctica suele estar organizada así:

```text
Ejercicio/
├── index.html          # Documento principal
├── css/
│   └── estilos.css     # Hoja de estilos
└── image/ o imágenes/  # Recursos gráficos
```

Algunas prácticas usan nombres de archivo específicos, como `HolaMundo.html`, `Formulario.html` o `Layout - Estructura de contenido.html`.

## Cómo ejecutar las prácticas

No hace falta instalar dependencias. Puedes abrir directamente el archivo HTML principal de cada carpeta desde el navegador.

Para servir todo el repositorio con una URL local, ejecuta desde la raíz:

```bash
python3 -m http.server 8000
```

Después abre [http://localhost:8000](http://localhost:8000) y navega hasta la práctica que quieras probar.

## Orden sugerido de estudio

1. Revisa `HolaMundo` y `Página Web` para conocer las etiquetas básicas.
2. Continúa con listas, enlaces, imágenes y tablas.
3. Añade CSS desde `Mi primer sitio con CSS`.
4. Practica cajas, posicionamiento, fondos y tipografía.
5. Finaliza con formularios y el layout semántico completo.

## Estado del proyecto

Este repositorio es un conjunto didáctico en proceso de aprendizaje. Los ejercicios utilizan HTML y CSS clásico, algunos nombres de clases simples y contenido Lorem Ipsum; no constituyen una aplicación completa ni un sistema de producción.
