# CV Portfolio - Carlos Abraham Bravo Jara

🚀 **Portafolio web moderno e innovador** para Carlos Abraham Bravo Jara, Analista Programador Computacional especializado en desarrollo Backend Java.

## 🌟 Vista Previa

Este portafolio presenta un diseño moderno y responsivo que incluye:

- **Información personal y profesional completa**
- **Timeline interactivo de experiencia laboral**
- **Visualización de habilidades técnicas**
- **Secciones de educación y certificaciones**
- **Modo oscuro/claro**
- **Animaciones suaves y efectos visuales**
- **Completamente responsivo para todos los dispositivos**

## 🛠️ Tecnologías Utilizadas

- **HTML5** - Estructura semántica
- **CSS3** - Estilos modernos con variables CSS, gradientes y animaciones
- **JavaScript ES6+** - Interactividad y funcionalidades avanzadas
- **Font Awesome** - Iconos profesionales
- **Google Fonts (Inter)** - Tipografía moderna

## ✨ Características

### 🎨 Diseño y UX
- ✅ Diseño responsivo para móviles, tablets y desktop
- ✅ Modo oscuro/claro con persistencia en localStorage
- ✅ Animaciones CSS suaves y transiciones
- ✅ Efectos hover interactivos
- ✅ Esquema de colores profesional (azules, grises, blancos)
- ✅ Tipografía moderna y legible

### 🧩 Funcionalidades
- ✅ Navegación suave entre secciones
- ✅ Menú hamburguesa para dispositivos móviles
- ✅ Timeline interactivo de experiencia laboral
- ✅ Barras de progreso animadas para habilidades
- ✅ Indicador de navegación activa
- ✅ Fondo de partículas animado
- ✅ Efectos de scroll y animaciones de entrada
- ✅ Optimización de rendimiento

### 📱 Secciones Incluidas
1. **Header/Navegación** - Menú fijo con toggle de tema
2. **Hero/Inicio** - Presentación personal con información clave
3. **Sobre Mí** - Perfil profesional y competencias
4. **Experiencia** - Timeline detallado de trabajos anteriores
5. **Habilidades** - Tecnologías y herramientas dominadas
6. **Educación** - Formación académica
7. **Cursos** - Certificaciones y formación continua
8. **Contacto** - Información de contacto y enlaces
9. **Footer** - Información adicional y redes sociales

## 🚀 Instalación y Uso

### Requisitos Previos
- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- Servidor web local (opcional, para desarrollo)

### Instalación

1. **Clonar el repositorio:**
   ```bash
   git clone https://github.com/CharlieBravo90Byte/cabj-cv-portafolio.git
   cd cabj-cv-portafolio
   ```

2. **Abrir directamente en el navegador:**
   ```bash
   # Opción 1: Abrir archivo directamente
   open index.html
   
   # Opción 2: Usar servidor local simple
   python -m http.server 8000
   # Luego visitar: http://localhost:8000
   
   # Opción 3: Con Node.js
   npx serve .
   ```

3. **Para desarrollo con Live Server (VS Code):**
   - Instalar la extensión "Live Server"
   - Hacer clic derecho en `index.html`
   - Seleccionar "Open with Live Server"

### 🌐 Despliegue

#### GitHub Pages
```bash
# El sitio se puede desplegar fácilmente en GitHub Pages
# 1. Ir a Settings > Pages en el repositorio
# 2. Seleccionar source: Deploy from a branch
# 3. Seleccionar rama: main
# 4. El sitio estará disponible en: https://charliebravo90byte.github.io/cabj-cv-portafolio/
```

#### Netlify
```bash
# Arrastrar la carpeta del proyecto a netlify.com
# O conectar el repositorio de GitHub para depliegue automático
```

#### Vercel
```bash
# Conectar el repositorio en vercel.com
# O usar CLI: vercel --prod
```

## 📁 Estructura del Proyecto

```
cabj-cv-portafolio/
├── 📄 index.html          # Página principal
├── 🎨 style.css           # Estilos CSS
├── ⚡ script.js           # JavaScript funcional
├── 📖 README.md           # Documentación
└── 📁 assets/             # Recursos (futuro)
    ├── 🖼️ images/         # Imágenes
    └── 📄 docs/           # Documentos
```

## 🎯 Personalización

### Cambiar Información Personal
Editar las siguientes secciones en `index.html`:

```html
<!-- Datos personales -->
<h1>Tu Nombre Completo</h1>
<p>Tu Profesión</p>

<!-- Información de contacto -->
<a href="mailto:tu@email.com">tu@email.com</a>
<a href="tel:+56123456789">+56 1 2345 6789</a>
```

### Modificar Colores y Tema
Editar variables CSS en `style.css`:

```css
:root {
    --primary-color: #3b82f6;    /* Color principal */
    --secondary-color: #1e40af;   /* Color secundario */
    --accent-color: #06b6d4;      /* Color de acento */
    /* ... más variables */
}
```

### Agregar Nuevas Secciones
1. Añadir HTML en `index.html`
2. Añadir estilos en `style.css`
3. Actualizar navegación si es necesario

## 🔧 Desarrollo

### Scripts Disponibles

```bash
# Validar HTML
npx html-validate index.html

# Validar CSS
npx stylelint style.css

# Validar JavaScript
npx eslint script.js

# Optimizar imágenes (futuro)
npx imagemin-cli assets/images/* --out-dir=assets/images/optimized/
```

### Mejores Prácticas Implementadas

- ✅ **Semántica HTML5** para accesibilidad
- ✅ **CSS Variables** para mantenimiento fácil
- ✅ **Mobile First** responsive design
- ✅ **Progressive Enhancement** JavaScript
- ✅ **Performance** optimizado
- ✅ **SEO** meta tags incluidos
- ✅ **Accesibilidad** ARIA labels
- ✅ **Cross-browser** compatibilidad

## 📈 Performance

### Métricas Objetivo
- ⚡ **First Contentful Paint**: < 1.5s
- ⚡ **Largest Contentful Paint**: < 2.5s
- ⚡ **Cumulative Layout Shift**: < 0.1
- ⚡ **First Input Delay**: < 100ms

### Optimizaciones Implementadas
- Lazy loading de imágenes
- CSS crítico inline
- JavaScript modular
- Compresión de assets
- Cache del navegador

## 🤝 Contribuir

1. **Fork** el proyecto
2. Crear una **rama** para tu feature (`git checkout -b feature/nueva-caracteristica`)
3. **Commit** tus cambios (`git commit -m 'Agregar nueva característica'`)
4. **Push** a la rama (`git push origin feature/nueva-caracteristica`)
5. Abrir un **Pull Request**

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

## 👨‍💻 Autor

**Carlos Abraham Bravo Jara**
- 📧 Email: [ca.bravoj29@gmail.com](mailto:ca.bravoj29@gmail.com)
- 💼 LinkedIn: [Carlos Bravo Jara](https://www.linkedin.com/in/carlosbravo-jara-90872555/)
- 📱 Teléfono: [+56 9 4819 2023](tel:+56948192023)

---

## 🙏 Agradecimientos

- **Font Awesome** por los iconos
- **Google Fonts** por la tipografía Inter
- **CSS Gradient** por inspiración en gradientes
- **Community** por feedback y sugerencias

---

**⭐ Si te gusta este proyecto, no olvides darle una estrella en GitHub!**