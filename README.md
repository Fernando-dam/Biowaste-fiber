# 🌿 Portafolio Biowaste Fiber

Portfolio web profesional para **Biowaste Fiber** - Consultoría Circular e Integral de Biorresiduos.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/es/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/es/docs/Web/CSS)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat&logo=bootstrap&logoColor=white)](https://getbootstrap.com/)

---

## 📋 Descripción

Este portafolio presenta los servicios, metodología y beneficios de Biowaste Fiber de manera moderna y profesional. El diseño es totalmente responsivo y optimizado para todos los dispositivos.

### ✨ Características

- ✅ Diseño moderno y profesional con Bootstrap 5
- ✅ Totalmente responsivo (móvil, tablet, desktop)
- ✅ Navegación suave entre secciones
- ✅ Iconos ilustrativos con Bootstrap Icons
- ✅ Colores corporativos (verde) coherentes
- ✅ Animaciones y efectos hover personalizados
- ✅ Optimizado para SEO
- ✅ Fácil de personalizar y actualizar

---

## 📂 Estructura del Proyecto

```
biowaste-portfolio/
│
├── index.html              # Página principal HTML
├── styles.css              # Estilos personalizados CSS
├── README.md               # Documentación (este archivo)
│
└── images/                 # Carpeta para imágenes (crear manualmente)

```

---

## 🚀 Instalación y Uso

### Opción 1: Descarga Directa

1. Descarga los archivos `index.html`, `styles.css` y `README.md`
2. Colócalos en una carpeta
3. Abre `index.html` en tu navegador

### Opción 2: Servidor Local

```bash
# Con Python 3
python -m http.server 8000

# Con Node.js (npx)
npx http-server

# Con PHP
php -S localhost:8000
```

Luego accede a `http://localhost:8000`

---

## 🖼️ Cómo Añadir Imágenes

### 1️⃣ Crear estructura de carpetas

```bash
mkdir -p images/hero images/services images/sectors images/process images/gallery
```

### 2️⃣ Añadir imagen al Hero Section

En `index.html`, busca el comentario `<!-- Espacio para añadir imagen hero -->` y descomenta:

```html
<img src="images/hero/biowaste-hero.jpg" 
     alt="Biowaste Fiber" 
     class="img-fluid rounded shadow-lg mb-5" 
     style="max-width: 800px;">
```

### 3️⃣ Añadir imágenes a los Servicios

En cada tarjeta de servicio, busca `<!-- <img src="images/services/...">` y descomenta:

```html
<!-- Servicio 1: Gestión de Trazabilidad -->
<img src="images/services/trazabilidad.jpg" 
     class="card-img-top" 
     alt="Gestión de Trazabilidad">

<!-- Servicio 2: Monitoreo -->
<img src="images/services/monitoreo.jpg" 
     class="card-img-top" 
     alt="Monitoreo del Compostaje">

<!-- Servicio 3: Digitalización -->
<img src="images/services/digitalizacion.jpg" 
     class="card-img-top" 
     alt="Digitalización">

<!-- Servicio 4: Compostaje Regenerativo -->
<img src="images/services/regenerativo.jpg" 
     class="card-img-top" 
     alt="Compostaje Regenerativo">

<!-- Servicio 5: Capacitación -->
<img src="images/services/capacitacion.jpg" 
     class="card-img-top" 
     alt="Capacitación">
```

### 4️⃣ Añadir una sección de Galería

Inserta antes de la sección de contacto:

```html
<!-- Gallery Section -->
<section id="galeria" class="py-5 bg-white">
    <div class="container py-5">
        <h2 class="text-center display-5 fw-bold mb-5">Galería</h2>
        <div class="row g-4">
            <div class="col-md-4">
                <img src="images/gallery/proyecto-1.jpg" 
                     alt="Proyecto 1" 
                     class="img-fluid rounded shadow">
            </div>
            <div class="col-md-4">
                <img src="images/gallery/proyecto-2.jpg" 
                     alt="Proyecto 2" 
                     class="img-fluid rounded shadow">
            </div>
            <div class="col-md-4">
                <img src="images/gallery/proyecto-3.jpg" 
                     alt="Proyecto 3" 
                     class="img-fluid rounded shadow">
            </div>
            <div class="col-md-4">
                <img src="images/gallery/proyecto-4.jpg" 
                     alt="Proyecto 4" 
                     class="img-fluid rounded shadow">
            </div>
            <div class="col-md-4">
                <img src="images/gallery/proyecto-5.jpg" 
                     alt="Proyecto 5" 
                     class="img-fluid rounded shadow">
            </div>
            <div class="col-md-4">
                <img src="images/gallery/proyecto-6.jpg" 
                     alt="Proyecto 6" 
                     class="img-fluid rounded shadow">
            </div>
        </div>
    </div>
</section>
```

No olvides añadir el enlace en el menú de navegación:

```html
<li class="nav-item">
    <a class="nav-link" href="#galeria">Galería</a>
</li>
```

### 5️⃣ Añadir logotipos de clientes/partners

Crea una nueva sección después de "Sectores":

```html
<!-- Partners Section -->
<section class="py-5 bg-white">
    <div class="container py-5">
        <h2 class="text-center display-6 fw-bold mb-5">Nuestros Clientes y Partners</h2>
        <div class="row g-4 align-items-center justify-content-center">
            <div class="col-6 col-md-3 text-center">
                <img src="images/partners/partner-1.png" 
                     alt="Partner 1" 
                     class="img-fluid" 
                     style="max-height: 80px; opacity: 0.7;">
            </div>
            <div class="col-6 col-md-3 text-center">
                <img src="images/partners/partner-2.png" 
                     alt="Partner 2" 
                     class="img-fluid" 
                     style="max-height: 80px; opacity: 0.7;">
            </div>
            <div class="col-6 col-md-3 text-center">
                <img src="images/partners/partner-3.png" 
                     alt="Partner 3" 
                     class="img-fluid" 
                     style="max-height: 80px; opacity: 0.7;">
            </div>
            <div class="col-6 col-md-3 text-center">
                <img src="images/partners/partner-4.png" 
                     alt="Partner 4" 
                     class="img-fluid" 
                     style="max-height: 80px; opacity: 0.7;">
            </div>
        </div>
    </div>
</section>
```

---

## 📐 Especificaciones de Imágenes

### Tamaños Recomendados

| Tipo de Imagen | Tamaño Recomendado | Formato | Peso Máximo |
|----------------|-------------------|---------|-------------|
| **Hero** | 1920x1080px | JPG | 300KB |
| **Servicios** | 800x600px | JPG | 150KB |
| **Galería** | 1200x900px | JPG | 200KB |
| **Logos** | 400x400px | PNG | 50KB |
| **Icons** | 200x200px | PNG/SVG | 20KB |

### Herramientas de Optimización

- 🔧 [TinyPNG](https://tinypng.com/) - Comprimir imágenes PNG y JPG
- 🔧 [Squoosh](https://squoosh.app/) - Optimizador de Google
- 🔧 [ImageOptim](https://imageoptim.com/) - Para Mac
- 🔧 [RIOT](https://riot-optimizer.com/) - Para Windows

### Formatos Recomendados

- **JPG**: Para fotografías y imágenes con muchos colores
- **PNG**: Para logos, iconos y imágenes con transparencia
- **WebP**: Formato moderno con mejor compresión (navegadores modernos)
- **SVG**: Para iconos y gráficos vectoriales

---

## 🎨 Personalización

### Cambiar Colores

Edita las variables CSS en `styles.css`:

```css
:root {
    --primary-green: #198754;        /* Color principal */
    --primary-green-dark: #146c43;   /* Verde oscuro */
    --primary-green-light: #20c997;  /* Verde claro */
    --gradient-start: #198754;       /* Inicio del gradiente */
    --gradient-end: #146c43;         /* Fin del gradiente */
}
```

### Cambiar Tipografía

En `styles.css`, modifica:

```css
body {
    font-family: 'Tu-Fuente', 'Segoe UI', sans-serif;
}
```

Para usar Google Fonts, añade en `<head>` de `index.html`:

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
```

### Añadir Nuevo Servicio

Copia y pega este bloque en la sección de servicios:

```html
<div class="col-md-6 col-lg-4">
    <div class="service-card card h-100 border-0 shadow-sm">
        <img src="images/services/nuevo-servicio.jpg" class="card-img-top" alt="Nuevo Servicio">
        <div class="card-body">
            <i class="bi bi-icon-name text-success fs-1 mb-3"></i>
            <h3 class="card-title h5 fw-bold">Nombre del Servicio</h3>
            <p class="card-text text-muted">Descripción del servicio...</p>
            <ul class="list-unstyled mt-3">
                <li class="mb-2"><i class="bi bi-check-circle-fill text-success me-2"></i>Beneficio 1</li>
                <li class="mb-2"><i class="bi bi-check-circle-fill text-success me-2"></i>Beneficio 2</li>
                <li class="mb-2"><i class="bi bi-check-circle-fill text-success me-2"></i>Beneficio 3</li>
            </ul>
        </div>
    </div>
</div>
```

---

## 📱 Secciones del Portafolio

1. **🏠 Hero** - Presentación principal con llamado a la acción
2. **✨ Beneficios** - 4 beneficios clave para empresas
3. **🛠️ Servicios** - 5 servicios principales detallados
4. **📋 Proceso** - 5 pasos del proceso de trabajo
5. **🏢 Sectores** - Sectores a los que se dirige
6. **💬 CTA** - Llamado a la acción para contacto
7. **📞 Contacto** - Información de contacto
8. **⚫ Footer** - Pie de página con copyright

---

## 🌐 Deployment (Publicación)

### GitHub Pages (Gratis)

1. Sube el proyecto a un repositorio de GitHub
2. Ve a **Settings** → **Pages**
3. Selecciona la rama `main` o `master`
4. Tu sitio estará en: `https://tu-usuario.github.io/biowaste-portfolio`

### Netlify (Gratis)

1. Crea una cuenta en [Netlify](https://www.netlify.com/)
2. Arrastra la carpeta del proyecto
3. El sitio se despliega automáticamente
4. Obtén un dominio: `https://tu-sitio.netlify.app`

### Vercel (Gratis)

1. Crea una cuenta en [Vercel](https://vercel.com/)
2. Importa desde GitHub o sube los archivos
3. Deploy automático en cada cambio
4. Dominio: `https://tu-sitio.vercel.app`

### Hosting Tradicional (Pago)

Sube los archivos via FTP a servicios como:
- **Hostinger** (~2€/mes)
- **SiteGround** (~3€/mes)
- **Webempresa** (~5€/mes)

---

## 🔍 SEO y Performance

### Optimización SEO

El sitio ya incluye:
- ✅ Meta descripción
- ✅ Título descriptivo
- ✅ Etiquetas alt en imágenes
- ✅ Estructura semántica HTML5
- ✅ URLs limpias con anchors

### Mejorar Performance

1. **Comprimir imágenes** antes de subirlas
2. **Lazy loading**: Añade `loading="lazy"` a las imágenes:
   ```html
   <img src="imagen.jpg" loading="lazy" alt="Descripción">
   ```
3. **CDN**: Los recursos de Bootstrap ya vienen de CDN
4. **Minificar CSS**: Usa herramientas online para comprimir `styles.css`

---

## 🛠️ Tecnologías Utilizadas

- **HTML5** - Estructura semántica
- **CSS3** - Estilos personalizados y animaciones
- **Bootstrap 5.3.2** - Framework CSS responsive
- **Bootstrap Icons** - Librería de iconos
- **JavaScript Vanilla** - Smooth scroll y interactividad

---

## 📞 Contacto de Biowaste Fiber

- 🌐 **Web:** [biowastefiber.com](https://biowastefiber.com)
- 📱 **Instagram:** [@biowaste.fiber](https://instagram.com/biowaste.fiber)

---

## 📄 Licencia

Este portafolio ha sido creado para **Biowaste Fiber**.  
© 2025 Biowaste Fiber. Todos los derechos reservados.

---

## 🤝 Contribuir

Si encuentras algún error o quieres sugerir mejoras:

1. Reporta issues
2. Sugiere cambios
3. Comparte feedback

---

## 📚 Recursos Adicionales

### Aprende más sobre las tecnologías

- [Bootstrap Documentation](https://getbootstrap.com/docs/)
- [Bootstrap Icons](https://icons.getbootstrap.com/)
- [MDN Web Docs](https://developer.mozilla.org/)
- [CSS Tricks](https://css-tricks.com/)

### Inspiración de diseño

- [Dribbble](https://dribbble.com/)
- [Behance](https://www.behance.net/)
- [Awwwards](https://www.awwwards.com/)

---

**Versión:** 1.0.0  
**Última actualización:** Diciembre 2025  
**Desarrollado con:** ❤️ para Biowaste Fiber

---

## ⚡ Quick Start

```bash
# 1. Clonar o descargar archivos
# 2. Crear carpeta de imágenes
mkdir -p images/hero images/services images/gallery

# 3. Añadir tus imágenes
# 4. Abrir index.html en navegador
# 5. ¡Listo! 🎉
```
