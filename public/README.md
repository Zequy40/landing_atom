# Landing Page AtomDigital - Instrucciones de Instalación

## 📁 Estructura de Archivos

```
tu-proyecto-astro/
├── src/
│   └── pages/
│       └── index.astro          # Tu landing page
└── public/
    └── atom-logo-dark.png       # Logo de AtomDigital
```

## 🚀 Instalación

1. **Coloca el archivo `index.astro`** en la carpeta `src/pages/` de tu proyecto Astro

2. **Coloca el logo `atom-logo-dark.png`** en la carpeta `public/` de tu proyecto

3. **Personaliza el número de WhatsApp** (IMPORTANTE):
   - Abre `index.astro`
   - Busca la línea que contiene: `https://wa.me/34YOUR_PHONE_NUMBER`
   - Reemplaza `34YOUR_PHONE_NUMBER` con tu número real
   - Ejemplo: `https://wa.me/34612345678` (incluye código de país sin +)

## 🎨 Colores de Marca

- **Principal**: `#8900B0` (Púrpura AtomDigital)
- **Secundario**: `#e9e9e9` (Gris claro)
- **Acento claro**: `#A740D0` (Púrpura claro para hover)
- **Acento soft**: `#F3E5FF` (Púrpura muy suave para fondos)

## 🔤 Tipografías

- **Títulos**: IBM Plex Sans (700 weight)
- **Texto**: Inter (400, 500, 600 weights)

## 📱 WhatsApp Button

El botón flotante de WhatsApp está configurado con un mensaje pre-escrito:
```
"Hola! Quiero información sobre el paquete de automatización para mi clínica dental"
```

Para cambiar el mensaje:
1. Busca el atributo `href` del elemento con clase `whatsapp-button`
2. Modifica el texto después de `?text=`
3. Recuerda usar `%20` para espacios

## ✨ Características

- ✅ Diseño minimalista y moderno
- ✅ Responsive (mobile-first)
- ✅ Animaciones suaves on-scroll
- ✅ WhatsApp flotante con pulse animation
- ✅ Optimizado para conversión
- ✅ Sin dependencias externas (excepto Google Fonts)
- ✅ Colores y tipografía de marca AtomDigital

## 🛠️ Comandos Astro

```bash
# Desarrollo
npm run dev

# Build para producción
npm run build

# Preview del build
npm run preview
```

## 📝 Notas Importantes

1. El logo en el footer tiene `filter: invert(1)` para que se vea blanco sobre fondo oscuro
2. Todas las fuentes se cargan desde Google Fonts
3. El scroll es suave (smooth scroll) entre secciones
4. Las animaciones se activan cuando los elementos entran en viewport
5. El botón de WhatsApp está fijo en la esquina inferior derecha

## 💡 Personalización Adicional

Para cambiar el email de contacto en el CTA final:
- Busca: `mailto:contacto@atomdigital.com`
- Cámbialo por tu email real

---

**Desarrollado por AtomDigital** 
Especialistas en automatización para clínicas dentales
