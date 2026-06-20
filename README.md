<!-- omit from toc -->
# FRP Consulting - Página Web Profesional

Sitio web moderno y responsivo para FRP Consulting, especializada en consultoría integral de servicios de salud.

## 📋 Contenido

- [Descripción](#descripción)
- [Características](#características)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Instalación](#instalación)
- [Uso](#uso)
- [Personalización](#personalización)
- [Despliegue](#despliegue)
- [Contacto](#contacto)

## 📖 Descripción

FRP Consulting es una firma de consultoría especializada en **Economía de la Salud** con expertise en **Calidad y Evaluación de Costos**. Esta página web presenta:

- **Experiencia profesional** de más de 7 años en el sector salud
- **Servicios especializados** en diseño organizacional, gestión hospitalaria y optimización de procesos
- **Logros destacados** con instituciones de renombre
- **Información de contacto** para solicitar consultas

## ✨ Características

### Diseño Profesional
- Interfaz moderna y limpia
- Colores corporativos: Azul (#2563eb) y Verde (#059669)
- Elementos visuales atractivos con animaciones suaves

### Totalmente Responsivo
- Funciona perfectamente en dispositivos móviles, tablets y desktops
- Menú hamburguesa en dispositivos móviles
- Imágenes y textos se adaptan automáticamente

### Rendimiento Optimizado
- Carga rápida
- CSS y JavaScript minificados (opcional)
- Compatible con todos los navegadores modernos

### Secciones Incluidas
1. **Navegación** - Menú fijo con acceso rápido a todas las secciones
2. **Hero** - Presentación principal con llamada a la acción
3. **Sobre Mí** - Presentación profesional y estadísticas
4. **Servicios** - 6 servicios principales ofrecidos
5. **Experiencia** - Historial con 5 instituciones principales
6. **Logros** - 6 logros destacados con iconos
7. **Contacto** - Formulario de contacto y datos de contacto
8. **Footer** - Enlaces a redes sociales

### Interactividad
- Validación de formularios
- Animaciones al hacer scroll
- Menú responsivo para móvil
- Enlaces suave entre secciones

## 🏗️ Estructura del Proyecto

```
frpnconsulting/
├── index.html           # Página HTML principal
├── css/
│   └── styles.css      # Estilos CSS
├── js/
│   └── script.js       # JavaScript para interactividad
├── images/             # Carpeta para imágenes (opcional)
├── README.md           # Este archivo
└── .gitignore          # Archivos a ignorar en git
```

## 🛠️ Tecnologías Utilizadas

- **HTML5** - Estructura semántica
- **CSS3** - Estilos avanzados, flexbox y grid
- **JavaScript (Vanilla)** - Interactividad sin dependencias externas
- **Font Awesome 6.4** - Iconos profesionales
- **Google Fonts** - Tipografía moderna

## 📦 Instalación

### Opción 1: Clonar el repositorio

```bash
git clone https://github.com/frpnsalud-png/frpnconsulting.git
cd frpnconsulting
```

### Opción 2: Usar directamente

Simplemente abre `index.html` en tu navegador web.

## 🚀 Uso

### Abrir localmente

1. Clona o descarga el repositorio
2. Abre `index.html` con tu navegador preferido
3. ¡Navega y prueba todas las funciones!

### Estructura de carpetas recomendada

Si deseas agregar imágenes:

```
images/
├── logo.png
├── team.jpg
├── office.jpg
└── certificates/
```

## 🎨 Personalización

### Cambiar Colores

Edita las variables en `css/styles.css`:

```css
:root {
    --primary-color: #2563eb;      /* Azul principal */
    --secondary-color: #059669;     /* Verde principal */
    --dark-color: #1f2937;          /* Texto oscuro */
    --light-color: #f9fafb;         /* Fondo claro */
    --gray-color: #6b7280;          /* Texto gris */
}
```

### Actualizar Información de Contacto

En `index.html`, busca la sección `#contacto` y actualiza:

```html
<p><a href="mailto:tu-email@example.com">tu-email@example.com</a></p>
<p><a href="tel:+54261234567">+54 (261) 234-5678</a></p>
<p>Tu Ciudad, Argentina</p>
```

### Agregar Redes Sociales

En el footer, actualiza los enlaces:

```html
<a href="https://linkedin.com/in/tu-perfil" target="_blank">
    <i class="fab fa-linkedin"></i>
</a>
```

### Modificar Servicios

Cada servicio está en el HTML como:

```html
<div class="service-card">
    <div class="service-icon">
        <i class="fas fa-sitemap"></i>
    </div>
    <h3>Nombre del Servicio</h3>
    <p>Descripción del servicio</p>
</div>
```

## 🌐 Despliegue

### Opción 1: GitHub Pages (Recomendado - GRATIS)

1. Ve a tu repositorio en GitHub
2. Accede a **Settings** → **Pages**
3. En "Source", selecciona `main` branch
4. Elige la carpeta raíz `/root`
5. Haz clic en **Save**
6. Tu sitio estará disponible en: `https://frpnsalud-png.github.io/frpnconsulting`

### Opción 2: Otros Servicios de Hosting

**Netlify:**
- Conecta tu repositorio de GitHub
- Elige el branch `main`
- Build command: (déjalo en blanco, no necesita compilación)
- Publish directory: (déjalo en blanco o /)

**Vercel:**
- Importa tu repositorio
- Sigue los pasos del wizard
- Tu sitio se desplegará automáticamente

**Hosting Tradicional:**
- Descarga los archivos
- Sube mediante FTP a tu servidor
- Asegúrate de que `index.html` esté en la raíz

## 📧 Contacto

Para actualizar la información de contacto en el sitio:

- **Email**: [Actualizar en `index.html`]
- **Teléfono**: [Actualizar en `index.html`]
- **Ubicación**: Mendoza, Argentina

## 📝 Notas Importantes

### Formulario de Contacto

El formulario actual muestra mensajes de éxito, pero no envía emails. Para implementar envío real:

1. **Usar un servicio como Formspree, Netlify Forms, o similar**
2. **Configurar un backend propio**
3. **Usar EmailJS para JavaScript**

**Ejemplo con Formspree:**

```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
    <!-- campos del formulario -->
</form>
```

### SEO

El sitio incluye:
- Meta descripción
- Meta keywords
- Estructura HTML semántica
- Atributos alt en imágenes (cuando las agregues)

**Mejoras SEO adicionales:**
1. Agrega Google Analytics
2. Crea un `sitemap.xml`
3. Agrega un `robots.txt`
4. Obtén un certificado SSL (GitHub Pages lo hace automáticamente)

### Performance

- Usa imágenes optimizadas (WebP cuando sea posible)
- Comprende imágenes antes de subirlas
- Considera minificar CSS/JS para producción

## 📄 Licencia

Este proyecto es de código abierto y puede ser utilizado libremente.

## 🤝 Soporte

Para reportar problemas o sugerencias, puedes abrir una issue en el repositorio de GitHub.

---

**Última actualización:** Junio 2024

**Versión:** 1.0.0
