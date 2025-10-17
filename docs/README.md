# 📁 Documentación HTML

Esta carpeta contiene las versiones HTML de toda la documentación del proyecto de Sistema de Control de Asistencia.

## 📄 Archivos Disponibles

| Archivo | Descripción | Tamaño |
|---------|-------------|--------|
| `index.html` | **Índice principal** - Página de navegación con acceso a todos los documentos | 5.5 KB |
| `00-RESUMEN-EJECUTIVO.html` | Resumen ejecutivo con panorama general de las 3 propuestas | 16 KB |
| `01-PROPUESTA-A-HIBRIDA.html` | Propuesta A: Solución híbrida (biométrico + WhatsApp) | 51 KB |
| `02-PROPUESTA-B-COMERCIAL.html` | Propuesta B: Equipos comerciales certificados | 27 KB |
| `03-PROPUESTA-C-WHATSAPP.html` | Propuesta C: 100% WhatsApp (⭐ Recomendada) | 32 KB |
| `04-COMPARATIVA.html` | Comparativa detallada de las 3 propuestas | 25 KB |
| `05-RECOMENDACIONES.html` | Recomendaciones y próximos pasos | 3.5 KB |

## 🚀 Cómo Usar

### Opción 1: Abrir en Navegador (Recomendado)

1. Abre `index.html` en tu navegador web preferido
2. Navega por los diferentes documentos usando los enlaces
3. Todos los diagramas Mermaid y tablas se renderizarán correctamente

### Opción 2: Servidor Local (Para GitHub Pages)

```bash
# Usando Python (recomendado)
cd html
python3 -m http.server 8000

# O usando Node.js
npx serve .

# Luego abre: http://localhost:8000
```

### Opción 3: Desplegar en GitHub Pages

Estos archivos están listos para ser desplegados en GitHub Pages:

1. Copia el contenido de `/html` a la raíz o a `/docs`
2. Configura GitHub Pages en Settings > Pages
3. Selecciona la rama y carpeta correspondiente
4. ¡Listo! Tus documentos estarán públicos

## ✨ Características

- **Diagramas Interactivos**: Todos los diagramas Mermaid se renderizan dinámicamente
- **Tablas Responsivas**: Diseño adaptable para móviles y escritorio
- **Estilos GitHub**: Usa GitHub Markdown CSS para consistencia visual
- **Sin Dependencias**: Todo funciona con CDNs públicos
- **Accesibilidad**: Imágenes con alt text, enlaces con títulos
- **SEO-Friendly**: Metadata adecuada en cada página

## 🎨 Tecnologías Utilizadas

- **GitHub Markdown CSS**: Estilos consistentes con GitHub
- **Mermaid.js**: Renderizado de diagramas (flowcharts, gantt)
- **HTML5**: Estructura semántica
- **CSS3**: Estilos responsive y modernos

## 📊 Diagramas Incluidos

Cada documento incluye múltiples diagramas Mermaid:
- ✅ Flowcharts de procesos
- ✅ Diagramas de arquitectura
- ✅ Cronogramas Gantt
- ✅ Diagramas de decisión

## 🔗 Navegación

La página `index.html` proporciona:
- Vista de tarjetas (cards) con cada documento
- Descripción breve de cada propuesta
- Enlaces directos a cada sección
- Guía de navegación recomendada

## 💡 Notas Técnicas

- Los archivos fueron generados automáticamente desde markdown usando `markdown2`
- Los bloques Mermaid se procesan en tiempo de renderizado del navegador
- Compatible con todos los navegadores modernos (Chrome, Firefox, Safari, Edge)
- No requiere JavaScript habilitado (excepto para diagramas Mermaid)

## 🐛 Resolución de Problemas

### Los diagramas no se muestran

**Solución**: Asegúrate de tener conexión a internet para cargar Mermaid.js desde CDN

### Las tablas se ven mal

**Solución**: Verifica que GitHub Markdown CSS se cargue correctamente desde el CDN

### Errores de CORS

**Solución**: Usa un servidor local (ver Opción 2 arriba) en lugar de abrir archivos directamente

## 📝 Actualización de Documentos

Para regenerar los archivos HTML desde los markdown:

```bash
# Ejecutar el script de conversión
python3 scripts/convert-md-to-html.py
```

## 📞 Soporte

Si encuentras algún problema con los documentos HTML:
1. Verifica que todos los archivos estén presentes
2. Intenta abrir en un navegador diferente
3. Revisa la consola del navegador para errores
4. Contacta al equipo técnico

---

**Última actualización**: Octubre 2025  
**Versión**: 1.0  
**Generado por**: Script automatizado Python + markdown2
