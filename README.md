# 🌱 Biowaste Fiber - Documentación Técnica Completa

## 📋 Índice
1. [Descripción General](#descripción-general)
2. [Estructura del Proyecto](#estructura-del-proyecto)
3. [Tecnologías Utilizadas](#tecnologías-utilizadas)
4. [Características Principales](#características-principales)
5. [Documentación del HTML](#documentación-del-html)
6. [Documentación del CSS](#documentación-del-css)
7. [Funcionalidades JavaScript](#funcionalidades-javascript)
8. [Responsive Design](#responsive-design)
9. [Instalación y Uso](#instalación-y-uso)
10. [Optimizaciones](#optimizaciones)
11. [Mantenimiento](#mantenimiento)
12. [Contacto y Soporte](#contacto-y-soporte)

---

## 🎯 Descripción General

**Biowaste Fiber** es una landing page profesional para una consultoría especializada en gestión circular e integral de biorresiduos. El sitio web presenta servicios de compostaje, trazabilidad de residuos orgánicos y soluciones sostenibles para diversos sectores.

### Objetivo del Sitio
Promover soluciones de economía circular mediante la gestión eficiente de biorresiduos, ofreciendo servicios de consultoría, capacitación y digitalización de procesos de compostaje.

### Características Clave
- 🌍 **Sostenibilidad**: Enfoque en economía circular
- 💼 **Profesional**: Diseño limpio y corporativo
- 📱 **Responsive**: Funciona en todos los dispositivos
- ⚡ **Rápido**: Optimizado para carga veloz
- ♿ **Accesible**: Cumple estándares WCAG

---

## 📁 Estructura del Proyecto

```
biowaste-fiber/
│
├── index.html          # Estructura principal del sitio (HTML5)
├── styles.css          # Estilos personalizados (CSS3)
├── README.md           # Documentación (este archivo)
│
└── img/                # Directorio de imágenes
    ├── bio.JPG        # Imagen hero principal (gestión de biorresiduos)
    ├── logo2.jpg      # Logo de la empresa
    └── compostaj.JPG  # Imagen de proceso de compostaje
```

### Descripción de Archivos

**index.html** (Archivo principal)
- Estructura semántica HTML5
- 10 secciones principales
- Meta tags para SEO
- Enlaces a CDN de Bootstrap

**styles.css** (Hoja de estilos)
- Variables CSS personalizadas
- Sistema de imágenes responsive
- Animaciones y transiciones
- Media queries para diferentes dispositivos

**img/** (Carpeta de recursos visuales)
- Imágenes optimizadas para web
- Formato JPG para fotografías
- Naming descriptivo

---

## 🛠️ Tecnologías Utilizadas

### Frontend Stack

| Tecnología | Versión | Propósito |
|-----------|---------|-----------|
| HTML5 | Latest | Estructura semántica |
| CSS3 | Latest | Estilos y animaciones |
| JavaScript | ES6+ | Interactividad (scroll suave) |
| Bootstrap | 5.3.2 | Framework responsive |
| Bootstrap Icons | 1.11.1 | Iconografía vectorial |

### CDN Externos

```html
<!-- Bootstrap CSS -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">

<!-- Bootstrap Icons -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.1/font/bootstrap-icons.css">

<!-- Bootstrap JS Bundle (incluye Popper) -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
```

### Ventajas de usar CDN
- ✅ Carga más rápida por caché compartido
- ✅ Menor tamaño del proyecto
- ✅ Actualizaciones automáticas de seguridad
- ✅ Alta disponibilidad y redundancia

---

## ✨ Características Principales

### Diseño y UX

| Característica | Descripción |
|---------------|-------------|
| **Responsive Design** | Adaptable a móviles (320px+), tablets y escritorio |
| **Animaciones Suaves** | Transiciones CSS en hover y scroll |
| **Scroll Suave** | Navegación fluida entre secciones con JavaScript |
| **Lazy Loading** | Carga diferida de imágenes para mejor performance |
| **SEO Optimizado** | Meta tags, estructura semántica, alt en imágenes |
| **Accesibilidad** | Navegación por teclado, contraste adecuado, focus states |

### Paleta de Colores

```css
/* Colores Principales */
Verde Principal:    #198754  /* Identidad de marca */
Verde Oscuro:       #146c43  /* Hover states */
Verde Claro:        #20c997  /* Acentos */

/* Colores de Texto */
Texto Oscuro:       #212529  /* Texto principal */
Texto Gris:         #6c757d  /* Texto secundario */

/* Fondos */
Fondo Claro:        #f8f9fa  /* Secciones alternas */
Fondo Blanco:       #ffffff  /* Secciones principales */
Fondo Oscuro:       #1a1a1a  /* Footer */
```

### Tipografía

```css
Familia: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif
Tamaño base: 16px
Peso: 400 (normal), 500 (medium), 700 (bold)
```

---

## 📄 Documentación del HTML (index.html)

### Estructura General del Documento

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <!-- Metadatos y recursos -->
</head>
<body>
    <!-- Navegación -->
    <!-- Hero Section -->
    <!-- Benefits Section -->
    <!-- Services Section -->
    <!-- Process Section -->
    <!-- Sectors Section -->
    <!-- CTA Section -->
    <!-- Contact Section -->
    <!-- Footer -->
    <!-- Scripts -->
</body>
</html>
```

---

### 1. HEAD - Metadatos y Recursos

```html
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Biowaste Fiber - Consultoría Circular e Integral de Biorresiduos. Soluciones sostenibles para la gestión de residuos orgánicos.">
    <title>Biowaste Fiber</title>
    
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    
    <!-- Bootstrap Icons -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.1/font/bootstrap-icons.css">
    
    <!-- Custom CSS -->
    <link rel="stylesheet" href="styles.css">
</head>
```

**Funciones Clave:**

**charset="UTF-8"**
- Codificación universal para caracteres especiales
- Permite acentos, ñ, símbolos especiales

**viewport**
- `width=device-width`: Ancho igual al dispositivo
- `initial-scale=1.0`: Zoom inicial al 100%
- Esencial para responsive design

**meta description**
- Descripción para motores de búsqueda (SEO)
- 155 caracteres aproximadamente
- Aparece en resultados de Google

**title**
- Título de la pestaña del navegador
- Importante para SEO y bookmarks

---

### 2. NAVBAR - Barra de Navegación

```html
<nav class="navbar navbar-expand-lg navbar-light bg-white shadow-sm">
    <div class="container">
        <a class="navbar-brand d-flex align-items-center" href="#inicio">
            <i class="bi bi-flower2 text-success fs-3 me-2"></i>
            <span class="fw-bold">BIOWASTE FIBER</span>
        </a>
    </div>
</nav>
```

**Clases Bootstrap Utilizadas:**

| Clase | Función |
|-------|---------|
| `navbar` | Componente de navegación base |
| `navbar-expand-lg` | Expande en pantallas grandes |
| `navbar-light` | Esquema de colores claro |
| `bg-white` | Fondo blanco |
| `shadow-sm` | Sombra pequeña |
| `container` | Contenedor responsive centrado |
| `d-flex` | Flexbox para alinear elementos |
| `align-items-center` | Alineación vertical centrada |

**Icono de Marca:**
- `bi-flower2`: Icono de flor (naturaleza/sostenibilidad)
- `text-success`: Color verde de Bootstrap
- `fs-3`: Tamaño de fuente nivel 3
- `me-2`: Margen derecho de 0.5rem

**Características:**
- ✅ Logo con icono y texto
- ✅ Diseño limpio y profesional
- ✅ Responsive (colapsa en móviles si se añaden links)
- ✅ Sombra sutil para separación visual

---

### 3. HERO SECTION - Sección Principal

```html
<section id="inicio" class="hero-section">
    <div class="container">
        <div class="row align-items-center min-vh-100">
            <div class="col-lg-12 text-center text-white">
                <h1 class="display-3 fw-bold mb-4 animate-fade-in">
                    Haz que tus biorresiduos trabajen por ti
                </h1>
                
                <div class="img-container">
                    <img src="/img/bio.JPG" 
                         alt="Gestión de biorresiduos" 
                         class="hero-image"
                         loading="lazy">
                </div>
            </div>
        </div>
    </div>
    <div class="hero-wave">
        <svg viewBox="0 0 1440 120" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M0 120L60 110C120 100 240 80 360 70C480 60 600 60 720 65C840 70 960 80 1080 85C1200 90 1320 90 1380 90L1440 90V120H1380C1320 120 1200 120 1080 120C960 120 840 120 720 120C600 120 480 120 360 120C240 120 120 120 60 120H0Z" fill="white"/>
        </svg>
    </div>
</section>
```

**Elementos Principales:**

**1. Contenedor Principal**
- `min-vh-100`: Altura mínima del 100% del viewport
- `align-items-center`: Centrado vertical
- `text-center`: Texto centrado
- `text-white`: Texto blanco sobre fondo verde

**2. Título (H1)**
- `display-3`: Tamaño de título grande
- `fw-bold`: Peso de fuente negrita
- `mb-4`: Margen inferior de 1.5rem
- `animate-fade-in`: Animación personalizada de entrada

**3. Imagen Hero**
- `loading="lazy"`: Carga diferida para performance
- `alt`: Texto alternativo para accesibilidad
- Clase personalizada `.hero-image` con estilos en CSS

**4. Wave SVG**
- Elemento decorativo en la parte inferior
- Crea transición suave hacia la siguiente sección
- `viewBox="0 0 1440 120"`: Dimensiones del SVG
- Path con forma de ola
- `fill="white"`: Relleno blanco para transición

**Propósito:**
- 🎯 Primera impresión del sitio
- 🎯 Comunicar el mensaje principal
- 🎯 Captar atención del usuario
- 🎯 Establecer identidad de marca

---

### 4. BENEFITS SECTION - Sección de Beneficios

```html
<section class="py-4 bg-white" id="beneficios">
    <div class="container py-3">
        <h2 class="text-center display-5 fw-bold mb-4">Beneficios</h2>
        <div class="row g-3">
            <!-- 4 tarjetas de beneficios -->
        </div>
    </div>
</section>
```

**Estructura de cada Tarjeta:**

```html
<div class="col-md-6 col-lg-3">
    <div class="benefit-card text-center p-3 h-100">
        <div class="icon-circle mb-2">
            <i class="bi bi-shield-check fs-2"></i>
        </div>
        <h3 class="h6 fw-bold mb-2">Cumplimiento Legal</h3>
        <p class="text-muted mb-0">Adaptación a normativas europeas y locales en biorresiduos</p>
    </div>
</div>
```

**Los 4 Beneficios:**

**1. Cumplimiento Legal** 🛡️
- Icono: `bi-shield-check` (escudo con check)
- Mensaje: Adaptación a normativas europeas y locales
- Color: Verde

**2. Economía Circular** ♻️
- Icono: `bi-arrow-repeat` (flechas circulares)
- Mensaje: Convierte el coste del residuo en rentabilidad
- Color: Verde

**3. Reputación Positiva** 🏆
- Icono: `bi-award` (medalla)
- Mensaje: Fortalece imagen corporativa
- Color: Verde

**4. Ahorro Económico** 🐷
- Icono: `bi-piggy-bank` (alcancía)
- Mensaje: Reducción de la tasa municipal
- Color: Verde

**Grid Responsive:**
- `col-md-6`: 2 columnas en tablets
- `col-lg-3`: 4 columnas en desktop
- `g-3`: Gap de 1rem entre columnas
- `h-100`: Altura 100% para cards uniformes

**Características Visuales:**
- Iconos circulares con gradiente verde
- Hover effect con elevación
- Texto centrado
- Esquinas redondeadas

---

### 5. SERVICES SECTION - Sección de Servicios

```html
<section id="servicios" class="py-4 bg-light">
    <div class="container py-3">
        <h2 class="text-center display-5 fw-bold mb-3">Servicios</h2>
        <p class="text-center text-muted mb-4">Soluciones integrales para la gestión sostenible de biorresiduos</p>
        
        <div class="row g-3">
            <!-- 5 tarjetas de servicios -->
        </div>
    </div>
</section>
```

**Estructura de Tarjeta de Servicio:**

```html
<div class="col-md-6 col-lg-4">
    <div class="service-card card h-100 border-0 shadow-sm">
        <div class="card-body p-3">
            <i class="bi bi-bar-chart-line text-success fs-2 mb-2"></i>
            <h3 class="card-title h6 fw-bold mb-2">Gestión de la Trazabilidad</h3>
            <p class="card-text text-muted mb-2">Descripción del servicio...</p>
            <ul class="list-unstyled mt-2 mb-0">
                <li class="mb-1">
                    <i class="bi bi-check-circle-fill text-success me-2"></i>
                    Beneficio 1
                </li>
                <!-- Más beneficios -->
            </ul>
        </div>
    </div>
</div>
```

**Los 5 Servicios Principales:**

**1. Gestión de la Trazabilidad** 📊
- **Icono:** `bi-bar-chart-line`
- **Descripción:** Sistemas sostenibles para trazar desde el origen hasta la transformación
- **Beneficios:**
  - Reduce costes de gestión
  - Cumple normativa ambiental
  - Convierte residuos en valor

**2. Acompañamiento y Monitoreo del Compostaje** 💧
- **Icono:** `bi-droplet`
- **Descripción:** Seguimiento claro y sostenible con control de calidad
- **Beneficios:**
  - Visita y registro
  - Control de parámetros
  - Análisis y mejoras continuas

**3. Digitalización del Compostaje** 🌡️
- **Icono:** `bi-thermometer-half`
- **Descripción:** Tecnología IoT para monitoreo en tiempo real
- **Beneficios:**
  - Control total del proceso
  - Informes automáticos
  - Datos verificables

**4. Compostaje Regenerativo** ⚙️
- **Icono:** `bi-gear`
- **Descripción:** Estrategias de economía circular para regenerar suelos
- **Beneficios:**
  - Captura carbono atmosférico
  - Evita pérdidas de nutrientes
  - Regenera el suelo

**5. Capacitación y Formación Inclusiva** 👥
- **Icono:** `bi-people`
- **Descripción:** Programas educativos para empresas e instituciones
- **Beneficios:**
  - Certificaciones sostenibles
  - Mejora desempeño ambiental
  - Fortalece imagen corporativa

**Grid Responsive:**
- Desktop: 3 columnas (primera fila: 3 cards, segunda fila: 2 cards)
- Tablet: 2 columnas
- Móvil: 1 columna

**Logo al Final:**
```html
<div class="img-container">
    <img src="/img/logo2.jpg" 
         alt="Biowaste Fiber Logo" 
         class="logo-image"
         loading="lazy">
</div>
```

---

### 6. PROCESS SECTION - Pasos del Proceso

```html
<section id="proceso" class="py-4 bg-white">
    <div class="container py-3">
        <h2 class="text-center display-5 fw-bold mb-4">Pasos para elaborar un sistema de Biorresiduos</h2>
        
        <div class="row g-3">
            <!-- 5 pasos -->
        </div>
    </div>
</section>
```

**Estructura de cada Paso:**

```html
<div class="col-12">
    <div class="process-step d-flex align-items-center p-3 rounded">
        <div class="step-number">01</div>
        <div class="step-content ms-3">
            <h3 class="h6 fw-bold mb-1">Título del Paso</h3>
            <p class="text-muted mb-0">Descripción del paso</p>
        </div>
    </div>
</div>
```

**Los 5 Pasos del Proceso:**

**Paso 01: Diagnóstico Inicial** 🔍
- Identificación de fuentes y tipos de biorresiduos
- Estimación de volúmenes
- Definición de objetivos

**Paso 02: Diseño del Sistema** 📐
- Selección del método de tratamiento
- Definición de flujos internos
- Elección de equipos adecuados

**Paso 03: Implementación y Capacitación** 🚀
- Instalación del sistema
- Capacitación del personal
- Puesta en marcha del proceso

**Paso 04: Monitoreo y Control de Proceso** 📈
- Medición de parámetros
- Registro periódico de datos
- Supervisión técnica continua

**Paso 05: Evaluación y Mejora Continua** ✅
- Análisis de indicadores
- Informes técnicos
- Certificación de buenas prácticas

**Características Visuales:**
- Números circulares verdes (01-05)
- Borde izquierdo verde de 4px
- Gradiente de fondo horizontal
- Hover effect con desplazamiento lateral
- Layout horizontal (desktop) / vertical (móvil)

---

### 7. SECTORS SECTION - Sectores de Aplicación

```html
<section id="sectores" class="py-4 bg-light">
    <div class="container py-3">
        <h2 class="text-center display-5 fw-bold mb-3">Apliquemos una Solución Circular</h2>
        <p class="text-center text-muted mb-4">Diversos sectores en el cual se pueden implementar soluciones personalizadas</p>
        
        <div class="row g-3">
            <!-- 6 sectores -->
        </div>
    </div>
</section>
```

**Los 6 Sectores Objetivo:**

**1. Gestores de biorresiduos** ♻️
- Icono: `bi-recycle`
- Empresas especializadas en gestión de residuos

**2. Industria alimentaria** 🍳
- Icono: `bi-egg-fried`
- Procesadores y productores de alimentos

**3. Hoteles / Restaurantes** 🏢
- Icono: `bi-building`
- Sector HORECA (hoteles, restaurantes, catering)

**4. Comedores escolares** 📚
- Icono: `bi-book`
- Instituciones educativas

**5. Huertos urbanos y rurales** 🌸
- Icono: `bi-flower1`
- Agricultura urbana y comunitaria

**6. Agricultores y viveros** 🌳
- Icono: `bi-tree`
- Producción agrícola profesional

**Grid Responsive:**
- Desktop: 6 columnas
- Tablet: 4 columnas (3 filas de 2)
- Móvil: 2 columnas (3 filas de 2)

**Características:**
- Cards compactas
- Iconos grandes y expresivos
- Texto breve y descriptivo
- Hover con cambio de borde a verde

---

### 8. CTA SECTION - Llamada a la Acción

```html
<section class="cta-section py-4 text-white text-center">
    <div class="container py-3">
        <h2 class="display-5 fw-bold mb-3">Logremos un impacto real</h2>
        <p class="mb-0">Gestiona tus residuos y genera valor</p>
    </div>
</section>
```

**Propósito:**
- Motivar al usuario a tomar acción
- Reforzar el mensaje principal
- Transición hacia la sección de contacto

**Características Visuales:**
- Gradiente verde de fondo (135deg)
- Pattern de puntos SVG semitransparente
- Texto blanco centrado
- Sin botones (diseño minimalista)

---

### 9. CONTACT SECTION - Información de Contacto

```html
<section id="contacto" class="py-5 bg-white">
    <!-- Imagen de proceso -->
    <div class="img-container">
        <img src="/img/compostaj.JPG" 
             alt="Proceso de compostaje" 
             class="contact-image"
             loading="lazy">
    </div>
    
    <div class="container py-5">
        <div class="row justify-content-center">
            <div class="col-lg-6 text-center">
                <h2 class="display-5 fw-bold mb-5">Contacto</h2>
                <div class="contact-info">
                    <!-- Sitio Web -->
                    <div class="mb-4">
                        <i class="bi bi-globe fs-2 text-success mb-3 d-block"></i>
                        <h5 class="fw-bold">Sitio Web</h5>
                        <a href="https://biowastefiber.com" target="_blank" class="text-success fs-5">
                            biowastefiber.com
                        </a>
                    </div>
                    
                    <!-- Instagram -->
                    <div class="mb-4">
                        <i class="bi bi-instagram fs-2 text-success mb-3 d-block"></i>
                        <h5 class="fw-bold">Instagram</h5>
                        <a href="https://instagram.com/biowaste.fiber" target="_blank" class="text-success fs-5">
                            @biowaste.fiber
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>
```

**Elementos de Contacto:**

**1. Sitio Web** 🌐
- URL: https://biowastefiber.com
- Icono: `bi-globe`
- `target="_blank"`: Abre en nueva pestaña

**2. Instagram** 📱
- Usuario: @biowaste.fiber
- Icono: `bi-instagram`
- Link directo al perfil

**Características:**
- Imagen de proceso de compostaje arriba
- Layout centrado
- Iconos grandes y llamativos
- Links con hover effect (escala 1.05)
- Color verde consistente con la marca

---

### 10. FOOTER - Pie de Página

```html
<footer class="bg-dark text-white py-4">
    <div class="container text-center">
        <div class="d-flex align-items-center justify-content-center mb-3">
            <i class="bi bi-flower2 fs-4 me-2"></i>
            <span class="fs-5 fw-bold">BIOWASTE FIBER</span>
        </div>
        <p class="text-muted mb-0">© 2025 Biowaste Fiber. Expertos en gestión sostenible de biorresiduos.</p>
    </div>
</footer>
```

**Elementos:**
- Logo con icono de flor
- Nombre de la empresa
- Copyright © 2025
- Tagline: "Expertos en gestión sostenible de biorresiduos"

**Características:**
- Fondo oscuro (#1a1a1a)
- Texto blanco y gris
- Centrado
- Diseño minimalista

---

### 11. SCRIPTS - JavaScript

```html
<!-- Bootstrap JS -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>

<!-- Smooth Scroll -->
<script>
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
        anchor.addEventListener('click', function (e) {
            e.preventDefault();
            const target = document.querySelector(this.getAttribute('href'));
            if (target) {
                const navbarHeight = document.querySelector('.navbar').offsetHeight;
                const targetPosition = target.offsetTop - navbarHeight;
                window.scrollTo({
                    top: targetPosition,
                    behavior: 'smooth'
                });
            }
        });
    });
</script>
```

**Orden de carga:**
1. Bootstrap JS (incluye Popper.js)
2. Smooth scroll personalizado

---

## 🎨 Documentación del CSS (styles.css)

### Estructura del Archivo CSS

```
styles.css
│
├── Variables de Color (:root)
├── Reset y Base
├── Sistema de Imágenes Responsive
├── Navbar
├── Hero Section
├── Benefit Cards
├── Service Cards
├── Process Steps
├── Sector Cards
├── CTA Section
├── Contact Section
├── Footer
├── Buttons
├── Utilities
├── Responsive Adjustments (Media Queries)
├── Animations
├── Scroll Padding
├── Custom Scrollbar
├── Accessibility
└── Print Styles
```

---

### 1. Variables CSS (Custom Properties)

```css
:root {
    --primary-green: #198754;
    --primary-green-dark: #146c43;
    --primary-green-light: #20c997;
    --gradient-start: #198754;
    --gradient-end: #146c43;
    --text-dark: #212529;
    --text-muted: #6c757d;
    --bg-light: #f8f9fa;
}
```

**Ventajas de Variables CSS:**
- ✅ **Mantenimiento fácil**: Cambiar colores en un solo lugar
- ✅ **Consistencia**: Mismos colores en todo el sitio
- ✅ **Legibilidad**: Nombres descriptivos vs códigos hex
- ✅ **Escalabilidad**: Fácil añadir temas (dark mode)

**Uso de Variables:**
```css
.elemento {
    color: var(--primary-green);
    background: var(--bg-light);
}
```

---

### 2. Reset y Base

```css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    color: var(--text-dark);
    overflow-x: hidden;
    padding-top: 0 !important;
    font-size: 16px;
    max-width: 1400px;
    margin: 0 auto;
}

html {
    scroll-behavior: smooth;
}
```

**Propósito del Reset:**
- Elimina márgenes y padding por defecto
- `box-sizing: border-box`: Incluye padding/border en el ancho total
- Previene scroll horizontal (`overflow-x: hidden`)

**Tipografía Base:**
- Fuente: Segoe UI (sistema)
- Tamaño: 16px (base estándar)
- Color: Variable `--text-dark`

**Contenedor Principal:**
- `max-width: 1400px`: Limita ancho máximo
- `margin: 0 auto`: Centrado horizontal

---

### 3. Sistema de Imágenes Responsive

#### A. Regla Base para Todas las Imágenes

```css
img {
    max-width: 100%;
    height: auto;
    display: block;
}
```

**Explicación:**
- `max-width: 100%`: Nunca excede el ancho del contenedor
- `height: auto`: Mantiene proporción de aspecto
- `display: block`: Elimina espacio debajo de la imagen

#### B. Contenedor Universal

```css
.img-container {
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 1.5rem auto;
    padding: 0 1rem;
}
```

**Propósito:**
- Centra imágenes horizontal y verticalmente
- Añade margen superior e inferior
- Padding lateral para móviles

#### C. Imagen Hero

```css
.hero-image {
    width: 100%;
    max-width: 800px;
    height: auto;
    border-radius: 15px;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
    margin: 0 auto 2rem;
}
```

**Breakpoints:**
```css
/* Desktop grande */
@media (max-width: 1200px) {
    .hero-image {
        max-width: 700px;
    }
}

/* Tablet */
@media (max-width: 992px) {
    .hero-image {
        max-width: 600px;
    }
}

/* Móvil */
@media (max-width: 768px) {
    .hero-image {
        max-width: 100%;
        margin: 0 0 2rem;
    }
}
```

#### D. Imagen del Logo

```css
.logo-image {
    width: 100%;
    max-width: 600px;
    height: auto;
    margin: 3rem auto;
    display: block;
}
```

#### E. Imagen de Contacto

```css
.contact-image {
    width: 100%;
    max-width: 900px;
    height: auto;
    border-radius: 15px;
    margin: 2rem auto;
    box-shadow: 0 5px 20px rgba(0, 0, 0, 0.1);
}
```

---

### 4. Navbar Styles

```css
.navbar {
    transition: all 0.3s ease;
    position: relative !important;
}

.navbar-brand {
    font-size: 1.5rem;
    font-weight: 700;
    transition: transform 0.3s ease;
}

.navbar-brand:hover {
    transform: scale(1.05);
}
```

**Nav Links con Animación:**

```css
.nav-link {
    font-weight: 500;
    position: relative;
    transition: color 0.3s ease;
    padding: 0.5rem 1rem !important;
}

.nav-link::after {
    content: '';
    position: absolute;
    bottom: 0;
    left: 50%;
    width: 0;
    height: 2px;
    background-color: var(--primary-green);
    transform: translateX(-50%);
    transition: width 0.3s ease;
}

.nav-link:hover::after {
    width: 80%;
}
```

**Efecto:**
- Línea verde que crece desde el centro
- Transición suave de 0.3 segundos
- Solo en hover

---

### 5. Hero Section Styles

#### Gradiente de Fondo

```css
.hero-section {
    background: linear-gradient(135deg, var(--gradient-start) 0%, var(--gradient-end) 100%);
    position: relative;
    min-height: 100vh;
    display: flex;
    align-items: center;
    padding-top: 0;
    margin-top: 0;
}
```

**Desglose:**
- `linear-gradient(135deg, ...)`: Gradiente diagonal
- `min-height: 100vh`: Altura mínima de pantalla completa
- `display: flex`: Flexbox para centrar contenido
- `align-items: center`: Centrado vertical

#### Wave SVG

```css
.hero-wave {
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    overflow: hidden;
    line-height: 0;
}

.hero-wave svg {
    position: relative;
    display: block;
    width: calc(100% + 1.3px);
    height: 120px;
}
```

**Función:**
- Posicionamiento absoluto en la parte inferior
- `overflow: hidden`: Oculta desbordamiento
- `width: calc(100% + 1.3px)`: Elimina gap en algunos navegadores

#### Animación FadeIn

```css
.animate-fade-in {
    animation: fadeIn 1s ease-in;
}

@keyframes fadeIn {
    from {
        opacity: 0;
        transform: translateY(30px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}
```

**Efecto:**
- Aparece gradualmente
- Se desplaza 30px hacia arriba
- Duración: 1 segundo
- Easing: ease-in

---

### 6. Benefit Cards

```css
.benefit-card {
    background: white;
    border-radius: 15px;
    transition: all 0.3s ease;
    border: 1px solid #e9ecef;
}

.benefit-card:hover {
    transform: translateY(-10px);
    box-shadow: 0 10px 30px rgba(25, 135, 84, 0.15);
}
```

**Efectos Hover:**
- Elevación de 10px
- Sombra verde suave (15% opacidad)
- Transición suave

#### Icon Circle

```css
.icon-circle {
    width: 60px;
    height: 60px;
    background: linear-gradient(135deg, #d1f4e0 0%, #e8f8f0 100%);
    border-radius: 50%;
    display: inline-flex;
    align-items: center;
    justify-content: center;
    color: var(--primary-green);
    margin: 0 auto;
}
```

**Características:**
- Círculo perfecto de 60x60px
- Gradiente verde claro de fondo
- Flexbox para centrar icono
- Color verde para el icono

---

### 7. Service Cards

```css
.service-card {
    transition: all 0.3s ease;
    border-radius: 15px;
    overflow: hidden;
}

.service-card:hover {
    transform: translateY(-10px);
    box-shadow: 0 15px 40px rgba(0, 0, 0, 0.1);
}

.service-card i {
    display: block;
}
```

**Diferencias con Benefit Cards:**
- Sombra más pronunciada (40px blur)
- Mismo efecto de elevación
- `overflow: hidden` para contener contenido

---

### 8. Process Steps

```css
.process-step {
    background: linear-gradient(to right, #f0fdf4 0%, #ffffff 100%);
    border-left: 4px solid var(--primary-green);
    transition: all 0.3s ease;
}

.process-step:hover {
    background: linear-gradient(to right, #e8f8f0 0%, #f8f9fa 100%);
    transform: translateX(10px);
}
```

**Características:**
- Gradiente horizontal (verde claro → blanco)
- Borde izquierdo verde de 4px
- Hover: Desplazamiento lateral de 10px
- Hover: Cambio de gradiente más oscuro

#### Step Number Circle

```css
.step-number {
    width: 50px;
    height: 50px;
    background: var(--primary-green);
    color: white;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 1.3rem;
    font-weight: bold;
    flex-shrink: 0;
    box-shadow: 0 4px 15px rgba(25, 135, 84, 0.3);
}
```

**Propiedades Clave:**
- `flex-shrink: 0`: No se encoge en flexbox
- Sombra verde difuminada
- Texto blanco centrado
- Tamaño fijo 50x50px

---

### 9. Sector Cards

```css
.sector-card {
    background: white;
    border-radius: 15px;
    transition: all 0.3s ease;
    border: 2px solid #e9ecef;
}

.sector-card:hover {
    border-color: var(--primary-green);
    transform: translateY(-5px);
    box-shadow: 0 8px 25px rgba(25, 135, 84, 0.15);
}

.sector-card i {
    display: block;
}
```

**Características:**
- Borde gris por defecto
- Hover: Borde verde
- Elevación menor (5px) que otras cards
- Sombra verde suave

---

### 10. CTA Section

```css
.cta-section {
    background: linear-gradient(135deg, var(--gradient-start) 0%, var(--gradient-end) 100%);
    position: relative;
}

.cta-section::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: url('data:image/svg+xml,<svg width="60" height="60" xmlns="http://www.w3.org/2000/svg"><rect width="60" height="60" fill="none"/><circle cx="30" cy="30" r="1.5" fill="rgba(255,255,255,0.1)"/></svg>');
    opacity: 0.5;
}

.cta-section .container {
    position: relative;
    z-index: 1;
}
```

**Técnica de Pattern:**
- Pseudo-elemento `::before` con SVG inline
- Pattern de puntos blancos semitransparentes
- `z-index: 1` en el contenido para estar encima

---

### 11. Contact Section

```css
.contact-info {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 3rem;
    flex-wrap: wrap;
}

.contact-item {
    min-width: 200px;
}

.contact-info a {
    text-decoration: none;
    transition: all 0.3s ease;
    display: inline-block;
    font-size: 16px !important;
}

.contact-info a:hover {
    transform: scale(1.05);
    color: var(--primary-green-dark) !important;
}
```

**Layout:**
- Flexbox centrado
- Gap de 3rem entre elementos
- `flex-wrap: wrap` para responsive
- Links con escala en hover

---

### 12. Responsive Adjustments

#### Media Query 768px (Tablets)

```css
@media (max-width: 768px) {
    .hero-section h1 {
        font-size: 2.5rem;
    }
    
    .hero-section p.lead {
        font-size: 1.2rem;
    }
    
    .step-number {
        width: 40px;
        height: 40px;
        font-size: 1.1rem;
    }
    
    .process-step {
        flex-direction: column;
        text-align: center;
    }
    
    .step-content {
        margin-top: 0.5rem;
        margin-left: 0 !important;
    }
    
    .contact-info {
        gap: 2rem;
    }
}
```

**Cambios Principales:**
- Títulos más pequeños
- Process steps en columna vertical
- Números de paso más pequeños
- Gaps reducidos

#### Media Query 576px (Móviles)

```css
@media (max-width: 576px) {
    .hero-section h1 {
        font-size: 2rem;
    }
    
    .display-5 {
        font-size: 2rem;
    }
    
    .icon-circle {
        width: 50px;
        height: 50px;
    }
    
    .contact-info {
        gap: 1.5rem;
    }
}
```

**Optimizaciones Móvil:**
- Títulos aún más pequeños
- Iconos reducidos
- Espaciado mínimo

---

### 13. Animaciones CSS

#### Slide In Up

```css
@keyframes slideInUp {
    from {
        opacity: 0;
        transform: translateY(50px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

.animate-slide-up {
    animation: slideInUp 0.8s ease-out;
}
```

#### Pulse

```css
@keyframes pulse {
    0%, 100% {
        opacity: 1;
    }
    50% {
        opacity: 0.5;
    }
}

.pulse {
    animation: pulse 2s cubic-bezier(0.4, 0, 0.6, 1) infinite;
}
```

---

### 14. Custom Scrollbar

```css
::-webkit-scrollbar {
    width: 10px;
}

::-webkit-scrollbar-track {
    background: #f1f1f1;
}

::-webkit-scrollbar-thumb {
    background: var(--primary-green);
    border-radius: 5px;
}

::-webkit-scrollbar-thumb:hover {
    background: var(--primary-green-dark);
}
```

**Nota:** Solo funciona en navegadores Webkit (Chrome, Safari, Edge)

---

### 15. Accesibilidad

```css
a:focus,
button:focus {
    outline: 2px solid var(--primary-green);
    outline-offset: 2px;
}
```

**Propósito:**
- Mejora navegación por teclado
- Outline verde visible
- Offset de 2px para claridad

---

### 16. Print Styles

```css
@media print {
    .navbar,
    .cta-section,
    footer {
        display: none;
    }
    
    .hero-section {
        background: white;
        color: black;
        min-height: auto;
    }
}
```

**Optimizaciones:**
- Oculta elementos de navegación
- Remueve gradientes
- Ajusta colores para impresión

---

## ⚙️ Funcionalidades JavaScript

### Smooth Scroll

```javascript
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault();
        const target = document.querySelector(this.getAttribute('href'));
        if (target) {
            const navbarHeight = document.querySelector('.navbar').offsetHeight;
            const targetPosition = target.offsetTop - navbarHeight;
            window.scrollTo({
                top: targetPosition,
                behavior: 'smooth'
            });
        }
    });
});
```

**Paso a Paso:**

1. **Seleccionar todos los links con #**
```javascript
document.querySelectorAll('a[href^="#"]')
```

2. **Prevenir comportamiento por defecto**
```javascript
e.preventDefault();
```

3. **Obtener elemento target**
```javascript
const target = document.querySelector(this.getAttribute('href'));
```

4. **Calcular posición compensando navbar**
```javascript
const navbarHeight = document.querySelector('.navbar').offsetHeight;
const targetPosition = target.offsetTop - navbarHeight;
```

5. **Scroll suave**
```javascript
window.scrollTo({
    top: targetPosition,
    behavior: 'smooth'
});
```

**Beneficios:**
- ✅ Navegación fluida
- ✅ Compensa altura del navbar
- ✅ Compatible con todos los navegadores modernos
- ✅ Mejora UX significativamente

---

## 📱 Responsive Design

### Breakpoints Principales

| Dispositivo | Ancho | Breakpoint | Columnas |
|------------|-------|------------|----------|
| Móvil XS | < 576px | Extra Small | 1 col |
| Móvil SM | 576px - 767px | Small | 2 cols |
| Tablet MD | 768px - 991px | Medium | 2-3 cols |
| Tablet LG | 992px - 1199px | Large | 3-4 cols |
| Desktop XL | ≥ 1200px | Extra Large | 4-6 cols |

### Estrategia Mobile-First

```css
/* Base: Móvil */
.elemento {
    font-size: 1rem;
    padding: 0.5rem;
}

/* Tablet */
@media (min-width: 768px) {
    .elemento {
        font-size: 1.2rem;
        padding: 1rem;
    }
}

/* Desktop */
@media (min-width: 1200px) {
    .elemento {
        font-size: 1.5rem;
        padding: 1.5rem;
    }
}
```

### Grid Bootstrap Responsive

```html
<!-- 1 col móvil, 2 cols tablet, 4 cols desktop -->
<div class="col-12 col-md-6 col-lg-3">
    <!-- Contenido -->
</div>
```

---

## 🚀 Instalación y Uso

### Requisitos Previos

- ✅ Navegador moderno (Chrome 90+, Firefox 88+, Safari 14+, Edge 90+)
- ✅ Servidor web local (opcional pero recomendado)
- ✅ Conexión a internet (para CDN de Bootstrap)

### Opción 1: Uso Directo

```bash
# Paso 1: Descargar archivos
# Paso 2: Abrir index.html en navegador
```

⚠️ **Nota:** Algunas funcionalidades pueden no funcionar correctamente al abrir directamente el archivo HTML (rutas relativas, CORS).

### Opción 2: Servidor Local (Recomendado)

#### Con Python 3:
```bash
# Navegar a la carpeta del proyecto
cd /ruta/al/proyecto

# Iniciar servidor
python -m http.server 8000

# Abrir en navegador: http://localhost:8000
```

#### Con Node.js:
```bash
# Instalar http-server globalmente
npm install -g http-server

# Iniciar servidor
http-server -p 8000

# Abrir en navegador: http://localhost:8000
```

#### Con PHP:
```bash
# Iniciar servidor
php -S localhost:8000

# Abrir en navegador: http://localhost:8000
```

#### Con VS Code (Live Server):
1. Instalar extensión "Live Server"
2. Click derecho en index.html
3. "Open with Live Server"

---

## 🎨 Personalización

### Cambiar Colores

**Paso 1:** Editar variables en `styles.css`

```css
:root {
    --primary-green: #TU_COLOR;        /* Color principal */
    --primary-green-dark: #TU_COLOR;   /* Color oscuro */
    --primary-green-light: #TU_COLOR;  /* Color claro */
}
```

**Ejemplo - Cambiar a azul:**
```css
:root {
    --primary-green: #0d6efd;
    --primary-green-dark: #0a58ca;
    --primary-green-light: #6ea8fe;
}
```

### Añadir Nuevo Servicio

```html
<div class="col-md-6 col-lg-4">
    <div class="service-card card h-100 border-0 shadow-sm">
        <div class="card-body p-3">
            <i class="bi bi-NOMBRE_ICONO text-success fs-2 mb-2"></i>
            <h3 class="card-title h6 fw-bold mb-2">Título del Servicio</h3>
            <p class="card-text text-muted mb-2">Descripción del servicio</p>
            <ul class="list-unstyled mt-2 mb-0">
                <li class="mb-1">
                    <i class="bi bi-check-circle-fill text-success me-2"></i>
                    Beneficio 1
                </li>
                <li class="mb-1">
                    <i class="bi bi-check-circle-fill text-success me-2"></i>
                    Beneficio 2
                </li>
            </ul>
        </div>
    </div>
</div>
```

### Cambiar Imágenes

1. Reemplazar archivos en `/img/`
2. Mantener mismos nombres o actualizar rutas en HTML

**Optimización de imágenes:**
```bash
# Comprimir con TinyPNG
https://tinypng.com

# O usar ImageOptim (Mac)
https://imageoptim.com

# O usar Squoosh (Web)
https://squoosh.app
```

### Añadir Nueva Sección

```html
<section id="nueva-seccion" class="py-5 bg-light">
    <div class="container">
        <h2 class="text-center display-5 fw-bold mb-4">Título</h2>
        <!-- Contenido -->
    </div>
</section>
```

---

## ⚡ Optimizaciones

### Performance

#### 1. Lazy Loading
```html
<img src="imagen.jpg" loading="lazy" alt="Descripción">
```

#### 2. Minificar CSS (Producción)
```bash
# Con cssnano
npm install -g cssnano-cli
cssnano styles.css styles.min.css

# Con clean-css
npm install -g clean-css-cli
cleancss -o styles.min.css styles.css
```

#### 3. Comprimir Imágenes
- **WebP:** Formato moderno (30% más ligero que JPG)
- **TinyPNG:** Compresión sin pérdida visible
- **Responsive images:** Usar `srcset` para múltiples tamaños

```html
<img 
    srcset="imagen-small.jpg 400w,
            imagen-medium.jpg 800w,
            imagen-large.jpg 1200w"
    sizes="(max-width: 600px) 400px,
           (max-width: 1000px) 800px,
           1200px"
    src="imagen-medium.jpg"
    alt="Descripción">
```

#### 4. Preload Fuentes Críticas
```html
<link rel="preload" href="font.woff2" as="font" type="font/woff2" crossorigin>
```

---

### SEO

#### Meta Tags Completos

```html
<head>
    <!-- Básicos -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Descripción de 155 caracteres">
    <meta name="keywords" content="biorresiduos, compostaje, economía circular">
    <meta name="author" content="Biowaste Fiber">
    
    <!-- Open Graph (Facebook) -->
    <meta property="og:title" content="Biowaste Fiber">
    <meta property="og:description" content="Consultoría Circular">
    <meta property="og:image" content="https://tudominio.com/img/og-image.jpg">
    <meta property="og:url" content="https://tudominio.com">
    <meta property="og:type" content="website">
    
    <!-- Twitter Card -->
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Biowaste Fiber">
    <meta name="twitter:description" content="Consultoría Circular">
    <meta name="twitter:image" content="https://tudominio.com/img/twitter-card.jpg">
    
    <!-- Favicon -->
    <link rel="icon" type="image/png" href="/favicon.png">
</head>
```

#### Sitemap.xml

```xml
<?xml version="1.0" encoding="UTF-8"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
    <url>
        <loc>https://biowastefiber.com/</loc>
        <lastmod>2025-01-01</lastmod>
        <priority>1.0</priority>
    </url>
</urlset>
```

#### Robots.txt

```txt
User-agent: *
Allow: /

Sitemap: https://biowastefiber.com/sitemap.xml
```

---

### Accesibilidad (WCAG 2.1)

#### Checklist

- ✅ Contraste adecuado (mínimo 4.5:1 para texto)
- ✅ Alt text en todas las imágenes
- ✅ Navegación por teclado funcional
- ✅ Focus states visibles
- ✅ Etiquetas semánticas HTML5
- ✅ ARIA labels donde necesario
- ✅ Textos escalables (rem/em vs px)

#### Atributos ARIA Recomendados

```html
<!-- Navegación -->
<nav aria-label="Navegación principal">

<!-- Botones -->
<button aria-label="Cerrar menú">×</button>

<!-- Imágenes decorativas -->
<img src="deco.png" alt="" role="presentation">

<!-- Íconos con significado -->
<i class="bi bi-phone" aria-hidden="true"></i>
<span class="sr-only">Teléfono</span>
```

---

## 🐛 Troubleshooting

### Problema: Imágenes no se cargan

**Solución:**
```bash
# Verificar ruta
❌ src="img/bio.jpg"  # Ruta relativa
✅ src="/img/bio.JPG" # Ruta absoluta desde raíz

# Verificar extensión (case-sensitive)
❌ bio.jpg
✅ bio.JPG
```

### Problema: Bootstrap no funciona

**Solución:**
1. Verificar conexión a internet
2. Abrir consola del navegador (F12)
3. Buscar errores 404
4. Verificar orden de carga de scripts

### Problema: Scroll suave no funciona

**Solución:**
```javascript
// Verificar que el JavaScript esté al final del body
// Verificar que los IDs coincidan con los hrefs

// Debug:
console.log(document.querySelector('#inicio')); // Debe devolver elemento
```

### Problema: Responsive no funciona

**Solución:**
```html
<!-- Verificar meta viewport -->
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<!-- Limpiar caché -->
Ctrl + Shift + R (Windows/Linux)
Cmd + Shift + R (Mac)
```

---

## 📊 Testing

### Herramientas Recomendadas

| Herramienta | Propósito | URL |
|------------|-----------|-----|
| Lighthouse | Auditoría completa | Chrome DevTools |
| PageSpeed Insights | Velocidad | https://pagespeed.web.dev |
| WAVE | Accesibilidad | https://wave.webaim.org |
| Responsive Viewer | Responsive testing | Extensión Chrome |
| GTmetrix | Performance | https://gtmetrix.com |

### Objetivos de Lighthouse

- 🎯 Performance: 90+
- 🎯 Accessibility: 95+
- 🎯 Best Practices: 90+
- 🎯 SEO: 95+

### Testing Checklist

**Desktop:**
- ✅ Chrome (últimas 2 versiones)
- ✅ Firefox (últimas 2 versiones)
- ✅ Safari (última versión)
- ✅ Edge (últimas 2 versiones)

**Mobile:**
- ✅ iOS Safari (iPhone)
- ✅ Chrome Android
- ✅ Samsung Internet

**Responsive:**
- ✅ 320px (iPhone SE)
- ✅ 375px (iPhone 12)
- ✅ 768px (iPad)
- ✅ 1024px (iPad Pro)
- ✅ 1920px (Desktop Full HD)

---

## 🔄 Mantenimiento

### Actualizar Bootstrap

```html
<!-- Verificar última versión en: https://getbootstrap.com -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.x.x/dist/css/bootstrap.min.css" rel="stylesheet">
```

### Backup Regular

```bash
# Crear backup
tar -czf biowaste-backup-$(date +%Y%m%d).tar.gz .

# O con Git
git add .
git commit -m "Backup $(date +%Y-%m-%d)"
```

### Checklist de Mantenimiento Mensual

- ✅ Verificar links rotos
- ✅ Actualizar contenido
- ✅ Revisar analytics
- ✅ Optimizar imágenes nuevas
- ✅ Backup de archivos
- ✅ Actualizar dependencias

---

## 📝 Licencia y Créditos

### Recursos Utilizados

- **Bootstrap 5.3.2:** MIT License
- **Bootstrap Icons:** MIT License
- **Imágenes:** Propiedad de Biowaste Fiber

### Autoría

- **Diseño y Desarrollo:** Biowaste Fiber Team
- **Año:** 2025
- **Versión:** 1.0.0

---

## 📞 Contacto y Soporte

### Información de Contacto

- 🌐 **Web:** https://biowastefiber.com
- 📱 **Instagram:** @biowaste.fiber
- 📧 **Email:** info@biowastefiber.com

### Soporte Técnico

Para problemas técnicos o consultas sobre el sitio web:
1. Revisar esta documentación
2. Consultar sección de Troubleshooting
3. Contactar al equipo de desarrollo

---

## 🎓 Recursos Adicionales

### Documentación Externa

- [Bootstrap Docs](https://getbootstrap.com/docs/5.3/getting-started/introduction/)
- [Bootstrap Icons](https://icons.getbootstrap.com/)
- [MDN Web Docs](https://developer.mozilla.org
