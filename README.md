# 📋 Navegador de Gestiones TSR - MAPFRE

Sistema web de gestión para Proveedores Patrimoniales MAPFRE. Aplicación Progressive Web App (PWA) con funcionalidad offline y diseño responsive.

![TSR MAPFRE](icon-512.png)

## 🚀 Características

- ✅ **PWA Instalable**: Funciona como app nativa en móvil y PC
- ✅ **Modo Offline**: Service Worker con cache inteligente
- ✅ **Responsive**: Diseño adaptable a móvil, tablet y desktop
- ✅ **13 Tipos de Gestiones**: Desde altas/bajas hasta formación
- ✅ **Formularios Interactivos**: Generación automática de correos
- ✅ **Búsqueda Rápida**: Filtrado inteligente de gestiones
- ✅ **Integración SharePoint**: Enlaces directos a documentación corporativa

## 📱 Instalación

### Opción 1: GitHub Pages (Recomendado)

1. Haz fork de este repositorio
2. Ve a **Settings** > **Pages**
3. En **Source**, selecciona `main` branch
4. Guarda y espera 1-2 minutos
5. Accede a: `https://TU-USUARIO.github.io/NOMBRE-REPO/`

### Opción 2: Servidor Local

```bash
# Clonar repositorio
git clone https://github.com/TU-USUARIO/navegador-tsr.git
cd navegador-tsr

# Servir con Python
python -m http.server 8000

# Abrir en navegador
http://localhost:8000
```

### Opción 3: Netlify / Vercel

1. Conecta tu repositorio GitHub
2. Deploy automático
3. URL personalizada disponible

## 🎯 Uso

### Desktop / Laptop
1. Abre la URL en Chrome, Edge o Firefox
2. Busca gestiones con el buscador
3. Haz clic en una tarjeta para ver detalles
4. Completa formularios y genera correos

### Móvil (Instalar como App)
1. Abre la URL en Chrome/Safari
2. **Android**: Menú (⋮) > "Añadir a pantalla de inicio"
3. **iOS**: Compartir > "Añadir a pantalla de inicio"
4. Usa como app nativa con icono TSR

## 📂 Estructura del Proyecto

```
navegador-tsr/
├── index.html          # Aplicación principal (protegida)
├── manifest.json       # Configuración PWA
├── sw.js              # Service Worker (cache offline)
├── icon-192.png       # Icono 192x192
├── icon-512.png       # Icono 512x512
├── favicon.ico        # Icono pestaña navegador
└── README.md          # Este archivo
```

## 🛠️ Tecnologías

- **HTML5**: Estructura semántica
- **CSS3**: Responsive design con Grid y Flexbox
- **JavaScript ES6+**: Lógica de aplicación
- **Service Workers**: Funcionalidad offline
- **PWA**: Instalable en dispositivos

## 🔒 Seguridad

- ✅ Copyright visible
- ✅ Acceso mediante enlaces a SharePoint corporativo (requiere autenticación MAPFRE)
- ⚠️ Uso exclusivo para personal interno autorizado

## 📊 Gestiones Disponibles

1. **Altas, Bajas y Contratos** - Gestión de proveedores
2. **Cambios de Guardia** - Sustituciones programadas
3. **Altas/Bajas Temporales** - Gestión de ausencias
4. **Zonas y Preasignaciones** - Distribución territorial
5. **Facturaciones y Tarifas** - Gestión económica
6. **Gestión Legal** - Contratos, embargos, demandas
7. **Documentación CAE/PRL** - 6Conecta
8. **Imagen Corporativa** - Rotulación, ropa, carnés
9. **Incidencias Aplicaciones** - INFOCOL, APPCOL
10. **Formación Proveedores** - Reciclaje profesional
11. **Consultas Red Comercial** - Soporte agentes
12. **Equipamiento Tecnológico** - SAU y dispositivos

## 🎨 Personalización

### Cambiar Colores Corporativos

Edita `index.html` y busca:
```css
color: #E4002B;  /* Rojo MAPFRE */
background: #E4002B;
```

### Modificar Iconos

Reemplaza los archivos:
- `icon-192.png` (192x192 px)
- `icon-512.png` (512x512 px)
- `favicon.ico` (16x16 o 32x32 px)

## 📱 Compatibilidad

| Navegador | Desktop | Móvil | PWA |
|-----------|---------|-------|-----|
| Chrome    | ✅      | ✅    | ✅  |
| Edge      | ✅      | ✅    | ✅  |
| Firefox   | ✅      | ✅    | ⚠️  |
| Safari    | ✅      | ✅    | ⚠️  |

⚠️ = Funcionalidad PWA limitada

## 🐛 Problemas Conocidos

- **Caracteres especiales**: Si aparecen símbolos raros, verifica que el servidor envíe `charset=UTF-8`
- **Cache persistente**: Si no ves cambios, borra cache del navegador
- **iOS PWA**: Algunas funciones limitadas en iOS Safari

## 📄 Licencia

© 2025 MAPFRE - Todos los derechos reservados.

Este código es propiedad de MAPFRE y está protegido por derechos de autor.  
Uso exclusivo para personal autorizado de MAPFRE.

## 👥 Soporte

Para soporte técnico o reportar problemas:
- 📧 Email: tsrdesoporte@mapfre.com
- 📱 Interno: Contacta con tu TSR territorial

## 🔄 Actualizaciones

**v1.0.0** (Enero 2025)
- ✅ Lanzamiento inicial
- ✅ 13 tipos de gestiones
- ✅ PWA completa con funcionamiento offline
- ✅ Responsive design
- ✅ Integración con SharePoint corporativo

---

**Desarrollado para MAPFRE TSR** | Sistema de Gestión de Proveedores Patrimoniales
