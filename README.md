# TP_PySWeb_2026
Trip Tour es un sitio web desarrollado con HTML5, CSS3 y JavaScript que permite explorar destinos turísticos, visualizar precios, conocer agencias y contactar para reservas.
Su objetivo es ofrecer una experiencia interactiva, visualmente atractiva y accesible para usuarios interesados en viajar.

## Descripcion del Sistema
### Tecnologías utilizadas
El sistema está construido bajo una arquitectura frontend _(por ahora)_, donde cada sección del sitio se organiza en archivos HTML independientes.

Para su desarrollo se utilizaron HTML5 para la estructura semántica, CSS3 para el diseño, la responsividad y las animaciones, y JavaScript de forma mínima para pequeñas interacciones.

## Demo
https://triptourviajes.netlify.app

## Descripción del sistema

El sistema está construido bajo una arquitectura frontend, donde cada sección del sitio se organiza en archivos HTML independientes.

Para su desarrollo se utilizaron:
- HTML5 para la estructura semántica
- CSS3 para diseño, responsividad y animaciones
- JavaScript de forma mínima para pequeñas interacciones

### Funcionalidad del sistema

El sitio cuenta con múltiples secciones que combinan diseño e interactividad. 
- La página principal incluye un hero con video de fondo, navegación responsive y tarjetas de destinos con efectos visuales. Además, incorpora un carrusel de testimonios implementado únicamente con CSS.
- La sección de destinos permite filtrar contenido dinámicamente mediante selectores CSS, junto con una galería tipo masonry, y una tabla de precios responsive.
- En agencias se presentan tarjetas con efecto flip en 3D y un sistema de rating interactivo sin JavaScript.
- El blog utiliza un layout tipo revista con CSS Grid, combinando diferentes tamaños de contenido para generar jerarquía visual.
- La página de contacto incluye un formulario con validación en tiempo real, un indicador de carga y un modal de confirmación implementado con CSS.

### Diseño e interfaz

El diseño está basado en una paleta de colores inspirada en la naturaleza, utilizando tonos verdes y tierra para reforzar la temática turística. Se priorizó una interfaz limpia, con jerarquía visual clara y elementos interactivos que brindan feedback al usuario.

El sitio es completamente responsive, adaptándose a distintos tamaños de pantalla.

### Accesibilidad

Se aplicaron buenas prácticas de accesibilidad, incluyendo el uso de atributos ARIA, navegación mediante teclado, estados visibles de foco y niveles adecuados de contraste, cumpliendo estándares AA/AAA.

### Instalación y ejecución

Para ejecutar el proyecto de forma local, se debe clonar el repositorio y abrir el archivo principal en el navegador:
```bash
git clone https://github.com/julietairisgm/TP_PySWeb_2026.git

cd TP_PySWeb_2026
```

Luego, abrir index.html directamente o utilizar una extensión como Live Server en Visual Studio Code.

### Deploy

El sitio fue desplegado utilizando Netlify.

## Autor

Proyecto desarrollado como trabajo práctico de Programación y Sistemas Web de APU Sede San Pedro.
