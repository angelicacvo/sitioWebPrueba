# sitioWebPrueba
Sitio web personal creado para prueba final Riwi

## Propósito del proyecto:
Un sitio web personal, para mostrar tus habilidades en proyectos y permitir que los visitantes te contacten.

## Requisitos:
1. Estructura HTML:
a. Crear un archivo index.html con estructura semántica (uso de <header>, <nav>,
<main>, <footer>).
b. Incluir una sección de presentación personal, un portafolio con al menos tres
proyectos y una sección de contacto.
2. Estilos CSS:
a. Utilizar un archivo externo styles.css para los estilos.
b. Aplicar colores, sombras, tipografía personalizada y transiciones.
3. Diseño responsivo:
a. Implementar Flexbox y Grid para la disposición de elementos.
b. Adaptar el diseño a tres tamaños de pantalla: escritorio (1024px+), tablet (768px) y
móvil (480px).
4. Interactividad:
a. Agregar transiciones suaves para botones y enlaces.
b. Incorporar efectos al interactuar con elementos del portafolio (hover).

## 🏗️ Estructura del Proyecto

```
📂 MiPortafolio/
 ├── 📁 assets/      # Contiene imágenes y estilos
 ├── 📄 index.html   # Página principal
 ├── 📄 projects.html # Listado de proyectos
 ├── 📄 contact.html # Página de contacto
 ├── 📄 styles.css   # Archivo principal de estilos
 ├── 📄 README.md    # Este archivo
```

## 📌 Temas Abordados

### 🔹 HTML5 Semántico
Uso etiquetas semánticas (`header`, `nav`, `main`, `article`, `section`, `footer`) para mejorar accesibilidad.

### 🎨 CSS: Selectores y Buenas Prácticas
- Empleo selectores avanzados para aplicar estilos.
- Manejo la **especificidad** para evitar conflictos en los estilos.

### 🔄 Diseño Responsivo con Flexbox y Grid
- **Flexbox** para distribución de elementos en **una dimensión**.
- **Grid** para estructurar layouts en **dos dimensiones**.

### 📱 Media Queries para Adaptabilidad
- Ajuste de estilos en función del tamaño de la pantalla.
- Optimización de contenido para dispositivos móviles y de escritorio.

## Explicación del código:

Se utilizaron 3 archivos principales: index.thml, contact.html y projects.html, en los cuales se divió el body por selectores, tales como header, main y selectores, dentro del archivo main se dividieron fragmentos por medio de divs para facilitar la implementación del display grid, estas se llamaron main-items, según el archivo para facilitar los estilos en el archivo css, también se utilizaron cards para la implementación de los proyectos y la visualización de estos. En el archivo CSS se utilizaron selectores, :root para la optimización del código, se configraron los márgenes y los paddings y se llamaron a lasvariables locales según el uso que se le fuera a dar. Se implementó un carrusel como parte del contact para una muestra visual de los proyectos realizados para otros.

## 🔧 Instalación y Uso

Para ver el portafolio en tu máquina local:
```bash
git clone [URL del repositorio]
cd [nombre-del-repositorio]
```
Luego, abre `index.html` en tu navegador.

#Maquetación:
![Prototipo_figma](https://github.com/user-attachments/assets/5bd55a76-e7da-4fd2-a8a7-46fe41aae883)

Enlace al figma:
https://www.figma.com/design/3oSxuWp8iDmL10vdDCH6o7/Sin-t%C3%ADtulo?node-id=0-1&m=dev&t=qZUZ04HlS3PfyfW3-1




