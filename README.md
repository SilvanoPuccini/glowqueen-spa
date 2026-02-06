# 📘 Entrega de Proyecto CSS - GlowQueen Spa & Beauty
**Máster en Desarrollo Web Full Stack – Conquer Blocks**

---

## 👤 Alumno
**Silvano Puccini**

---

## 📚 Módulo
**CSS – Maquetación, SASS y Metodologías de Desarrollo**

---

## 🌐 Demo en vivo (GitHub Pages)
🔗 **URL pública del proyecto:** [https://silvanopuccini.github.io/glowqueen-spa/](https://silvanopuccini.github.io/glowqueen-spa/)

---

## 🎯 Objetivo del proyecto

Este trabajo corresponde a la **Tarea Entregable 1: Header Spa & Beauty** del módulo de CSS del Máster en Desarrollo Web Full Stack.

El objetivo es consolidar los conocimientos de CSS y SASS mediante la maquetación de un header-hero para una página web de tipo SPA, siguiendo fielmente el diseño proporcionado en Figma. El proyecto incluye:

* Maquetación pixel-perfect desde diseño Figma
* Uso de preprocesador SASS con arquitectura modular
* Metodología BEM para nomenclatura de clases
* Iconografía en formato SVG
* Estructura HTML5 semántica
* Estados hover en elementos interactivos
* Diseño responsive (funcionalidad extra)

---

## 🗂️ Estructura del proyecto

El proyecto sigue una **arquitectura modular SASS**, separando responsabilidades en partials independientes:

```
glowqueen-spa/
│
├── index.html
├── package.json
├── package-lock.json
└── README.md
├── css/
│   ├── style.css
│   └── style.css.map
├── scss/
│   ├── _variables.scss
│   ├── _base.scss
│   ├── _header.scss
│   ├── _hero.scss
│   └── main.scss
└── assets/
    ├── images/
    │   ├── background.png
    │   └── model.png
    ├── icons/
    │   ├── cart.svg
    │   ├── herbal.svg
    │   ├── lotus-bg.svg
    │   ├── testimony.svg
    │   ├── therapist.svg
    │   └── treatment.svg
    └── favicon/
        ├── android-chrome-192x192.png
        ├── android-chrome-512x512.png
        ├── apple-touch-icon.png
        ├── favicon-16x16.png
        ├── favicon-32x32.png
        ├── favicon.ico
        └── site.webmanifest
```

---

## 🧪 Funcionalidades implementadas

### ✅ **1. Header Completo**
- Logo con tipografía estilizada (GlowQueen)
- Navegación principal con 5 enlaces
- Estados hover con underline animado
- Iconos de búsqueda y carrito en SVG
- Botones Sign In y Sign Up

### ✅ **2. Hero Section**
- Título y subtítulo con tipografía Poppins
- Botones CTA: "Book Now" y "Watch Video"
- Imagen principal de modelo con fondo transparente
- Posicionamiento preciso sobre fondo dividido

### ✅ **3. Stats Section**
- 3 estadísticas con iconos SVG
- Contenedor con fondo blanco y sombra
- Iconos con fondo cyan circular
- Números y etiquetas estilizados

### ✅ **4. Testimonials**
- 2 tarjetas de testimonios posicionadas
- Efecto glassmorphism (backdrop-filter blur)
- Posicionamiento absoluto sobre la imagen
- Diseño diagonal superpuesto

### ✅ **5. Fondo Dividido (CSS Puro)**
- 65% color cream (#FAF8F5)
- 35% color cyan (#A9D6CB)
- 20% blanco en la parte inferior
- Flor de loto decorativa con opacidad

### ✅ **6. Responsive Design (Extra)**
- Menú hamburguesa para mobile
- Breakpoints: 1200px, 1024px, 992px, 768px, 480px
- Adaptación de grid y tipografías
- Ocultamiento de testimonials en mobile

---

## 🎨 Sistema de Diseño

### **Paleta de Colores (desde Figma):**

| Color | Hex | Uso |
|-------|-----|-----|
| Dark Blue | `#264065` | Textos principales, botones |
| Cyan | `#A9D6CB` | Acentos, fondos, iconos |
| Cream | `#FAF8F5` | Fondo principal (65%) |
| Gray | `#909090` | Textos secundarios |
| White | `#FFFFFF` | Cards, fondos, stats |
| Teal | `#5B9A9A` | Testimonial inferior |

### **Tipografía:**

| Elemento | Fuente | Peso | Tamaño |
|----------|--------|------|--------|
| Título | Poppins | Bold (700) | 48px |
| Subtítulo | Poppins | Regular (400) | 24px |
| Stats | Poppins | Medium (500) | 36px |
| Logo | Poppins | SemiBold (600) | 36px |
| Nav | Poppins | Medium (500) | 16px |
| Body | Poppins | Regular (400) | 16px |

---

## 🛠 Tecnologías utilizadas

### **Frontend:**
- **HTML5** - Estructura semántica
- **CSS3 / SCSS** - Estilos con preprocesador
- **Metodología BEM** - Nomenclatura de clases
- **Google Fonts** - Tipografía Poppins
- **SVG** - Iconografía vectorial

### **Herramientas:**
- **SASS** - Preprocesador CSS
- **Node.js / NPM** - Gestión de dependencias
- **Git** - Control de versiones
- **GitHub Pages** - Despliegue
- **Figma** - Referencia de diseño

---

## 📋 Cumplimiento de requisitos

| Requisito | Estado | Implementación |
|-----------|--------|----------------|
| **Fidelidad al diseño Figma** | ✅ COMPLETO | Maquetación pixel-perfect |
| **Uso de SASS** | ✅ COMPLETO | Arquitectura modular con partials |
| **Iconos en SVG** | ✅ COMPLETO | Todos los iconos vectoriales |
| **Semántica HTML** | ✅ COMPLETO | header, main, nav, article |
| **Estados hover** | ✅ COMPLETO | Botones, enlaces, iconos |
| **Diseño responsive (extra)** | ✅ COMPLETO | 5 breakpoints + menú mobile |

### **Cumplimiento total: 100%** ✅

---

## ⭐ Características adicionales

El proyecto **supera los requisitos** de la consigna con:

### **1. Arquitectura SASS Modular**
- Variables centralizadas (`_variables.scss`)
- Reset y estilos base (`_base.scss`)
- Componentes separados (header, hero)
- Uso de `@use` en lugar de `@import` (moderno)

### **2. Metodología BEM Consistente**
```scss
.header-auth__signup { }  // Bloque__Elemento
.nav__link--active { }    // Bloque__Elemento--Modificador
.stat__icon { }           // Componente reutilizable
```

### **3. Diseño Responsive Completo**
- Mobile-first no requerido pero implementado
- Menú hamburguesa funcional con JavaScript
- Grid adaptativo para stats
- Ocultamiento inteligente de elementos

### **4. Efectos Visuales Avanzados**
- Glassmorphism en testimonials
- Transiciones suaves (200ms ease)
- Sombras con múltiples niveles
- Hover states con transform

### **5. Fondo CSS Puro**
- Sin imágenes para el fondo dividido
- Flexbox para división de colores
- Flor decorativa con SVG inline
- Totalmente responsive

---

## 🚀 Instalación y uso local

### **1. Clonar el repositorio:**
```bash
git clone https://github.com/SilvanoPuccini/glowqueen-spa.git
cd glowqueen-spa
```

### **2. Instalar dependencias:**
```bash
npm install
```

### **3. Compilar SASS:**
```bash
# Compilar una vez
npm run sass

# Modo watch (desarrollo)
npm run watch

# Compilar minificado (producción)
npm run build
```

### **4. Abrir en navegador:**
```bash
# Abrir index.html directamente o usar servidor local
npx serve .
```

---

## 🌐 Despliegue en GitHub Pages

El proyecto está desplegado y accesible públicamente en:

🔗 **[https://silvanopuccini.github.io/glowqueen-spa/](https://silvanopuccini.github.io/glowqueen-spa/)**

### **Pasos para desplegar:**
1. Push del código a rama `main`
2. Activar GitHub Pages en Settings → Pages
3. Seleccionar rama `main` y carpeta `/ (root)`
4. Esperar 2-3 minutos para el despliegue

---

## 📱 Responsive Design

La aplicación es completamente responsive y se adapta a:

| Breakpoint | Dispositivo | Cambios |
|------------|-------------|---------|
| >1200px | Desktop grande | Layout completo |
| 1024px | Desktop | Ajuste de espaciados |
| 992px | Tablet | Grid 1 columna, imagen arriba |
| 768px | Tablet pequeña | Menú hamburguesa activo |
| 480px | Mobile | Tipografías reducidas |

---

## 🧠 Decisiones técnicas destacadas

### **¿Por qué SASS con arquitectura modular?**
- Mejor organización del código
- Variables reutilizables
- Mantenimiento más sencillo
- Escalabilidad para proyectos grandes

### **¿Por qué BEM como metodología?**
- Nomenclatura clara y predecible
- Evita conflictos de especificidad
- Código autodocumentado
- Estándar de la industria

### **¿Por qué fondo con CSS puro?**
- Mejor rendimiento (sin imágenes)
- Totalmente responsive
- Fácil de modificar
- Reduce peso del proyecto

### **¿Por qué SVG para iconos?**
- Escalables sin pérdida de calidad
- Modificables con CSS (color, tamaño)
- Menor peso que imágenes
- Mejor accesibilidad

---

## ✅ Estado del proyecto

| Aspecto | Estado |
|---------|--------|
| Funcional | ✔ |
| Desplegado en GitHub Pages | ✔ |
| Probado en múltiples navegadores | ✔ |
| Responsive en todos los dispositivos | ✔ |
| 100% de requisitos cumplidos | ✔ |
| **Listo para evaluación** | ✔ |

---

## 📝 Licencia

Este proyecto es de carácter académico y ha sido desarrollado como parte del **Máster en Desarrollo Web Full Stack** de **Conquer Blocks**.

---

## 👨‍💻 Autor

**Silvano Puccini**  
Alumno del Máster en Desarrollo Web Full Stack  
**Academia:** Conquer Blocks  
**Año:** 2026

---
