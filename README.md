# Era de la Educación Experimental

## 📚 Descripción del Proyecto

Página web de GitHub Pages que documenta el progreso y todas las versiones del paper **"Era de la Educación Experimental"**, un trabajo en profundidad sobre la educación experimental y su impacto en la transformación educativa moderna.

## 🎯 Características

✨ **Diseño Moderno y Responsivo**
- Interfaz limpia y profesional
- Totalmente responsive (móvil, tablet, desktop)
- Animaciones suaves y transiciones elegantes

📊 **Timeline Interactivo**
- Visualización clara de todas las versiones
- Changelog detallado de cada versión
- Categorización de cambios (Nuevo, Mejorado, Corregido)

📈 **Panel de Progreso**
- Barra de progreso visual
- Estadísticas del proyecto
- Información de actualización

🎨 **Componentes Destacados**
- Sección de características principales
- Galería de descargas
- Estadísticas del proyecto
- Footer informativo

## 📁 Estructura de Archivos

```
/
├── index.html          # Página principal
├── styles.css          # Estilos CSS
├── data.json          # Datos de versiones (para actualizaciones futuras)
├── README.md          # Este archivo
└── .github/
    └── workflows/
        └── deploy.yml # (Opcional) Workflow de GitHub Actions
```

## 🚀 Cómo Usar

### 1. Clonar o descargar el repositorio

```bash
git clone https://github.com/tu-usuario/paper-name.git
cd paper-name
```

### 2. Activar GitHub Pages

1. Ve a **Settings** de tu repositorio
2. Navega a **Pages** en el menú lateral
3. En "Source", selecciona **main** (o la rama que uses)
4. Selecciona la carpeta raíz o `/docs`
5. Haz clic en **Save**

La página estará disponible en: `https://tu-usuario.github.io/paper-name`

### 3. Personalizar Contenido

#### Editar Información Básica
En `index.html`, actualiza:
- Título y subtítulo en la sección `<header>`
- Información en el footer

#### Añadir o Modificar Versiones
Actualiza el HTML directamente en `index.html` en la sección "Historial de Versiones", o usa `data.json` para mantener datos centralizados.

**Plantilla para nueva versión:**
```html
<div class="timeline-item">
    <div class="timeline-marker"></div>
    <div class="timeline-content">
        <div class="version-header">
            <h3>Versión X.X</h3>
            <span class="date-badge">Fecha aquí</span>
        </div>
        <p class="version-status">Estado</p>
        <div class="improvements">
            <h4>Mejoras implementadas:</h4>
            <ul class="improvement-list">
                <li><span class="badge new">Nuevo</span> Cambio aquí</li>
            </ul>
        </div>
    </div>
</div>
```

#### Cambiar Colores del Tema
En `styles.css`, modifica las variables CSS:
```css
:root {
    --primary-color: #2563eb;      /* Color principal */
    --secondary-color: #8b5cf6;    /* Color secundario */
    --success-color: #10b981;      /* Verde */
    --danger-color: #ef4444;       /* Rojo */
}
```

## 🎨 Personalización de Colores

### Paletas Recomendadas

**Azul Profesional (actual):**
```
Primary: #2563eb
Secondary: #8b5cf6
```

**Verde Educativo:**
```
Primary: #10b981
Secondary: #06b6d4
```

**Púrpura Innovador:**
```
Primary: #7c3aed
Secondary: #ec4899
```

**Naranja Dinámico:**
```
Primary: #f97316
Secondary: #f59e0b
```

## 📊 Actualizar Estadísticas

Encuentra y edita en `index.html`:
```html
<p class="stat-number">6</p>  <!-- Número de versiones -->
```

## 🔗 Enlaces Importantes

### Agregar Links de Descarga
En la sección de "Descargas", actualiza los `href`:
```html
<a href="ruta-a-tu-pdf.pdf" class="download-card">
```

### Enlazar a GitHub
```html
<a href="https://github.com/tu-usuario/repo" class="download-card">
```

## 📱 Responsive Design

La página se adapta automáticamente a:
- 📱 Móvil (< 480px)
- 📱 Tablet (480px - 768px)
- 🖥️ Desktop (> 768px)

## 🛠️ Tecnologías Utilizadas

- **HTML5** - Estructura semántica
- **CSS3** - Estilos modernos con Grid y Flexbox
- **Google Fonts** - Tipografía profesional
- **Responsive Design** - Mobile-first approach

## ♿ Accesibilidad

✓ Contraste de colores WCAG AA compliant
✓ Navegación por teclado
✓ Estructura semántica HTML5
✓ Meta tags para SEO

## 🎯 Tips para Mantener la Página

1. **Actualiza regularmente** - Agrega nuevas versiones cuando haya cambios significativos
2. **Mantén consistencia** - Usa el mismo formato para todas las versiones
3. **Sé descriptivo** - Explica qué cambió en cada versión
4. **Verifica links** - Asegúrate que los downloads funcionen
5. **Prueba responsive** - Abre en diferentes dispositivos

## 📝 Ejemplo de Commit

```bash
git add .
git commit -m "docs: Agregar versión 3.2 con análisis comparativo"
git push origin main
```

## 🐛 Troubleshooting

### La página no aparece en GitHub Pages
- Verifica que el repositorio sea público
- Espera 5 minutos después de activar Pages
- Revisa la sección "Pages" en Settings

### Los estilos no cargan
- Comprueba que `styles.css` esté en el directorio raíz
- Limpia el caché del navegador (Ctrl+Shift+R)

### Las fuentes no se ven correctamente
- Verifica conexión a internet
- Los Google Fonts necesitan acceso a internet

## 📄 Licencia

Todos los derechos reservados © 2025-2026

---

**Hecho con ❤️ para documentar y compartir el conocimiento**
