# Concytec Conecta - Ventanilla Única Digital de CTI (Perú)

Prototipo web interactivo y Single Page Application (SPA) responsive desarrollado con estándares estrictos de **GovTech**, el **Design System oficial GOB.PE**, accesibilidad **WCAG 2.1 nivel AA** y una **experiencia de usuario (UX) dinámica e iconográficamente enriquecida**.

---

## 🚀 Inicio Rápido

El proyecto está diseñado en una arquitectura modular, resiliente y autocontenida:
- Funciona inmediatamente abriendo el archivo localmente (`file:///`) en cualquier navegador web.
- Todos los iconos vectoriales SVG están embebidos y optimizados, asegurando que se visualicen correctamente incluso en intranets gubernamentales que bloqueen CDNs.

Para ejecutarlo:
1. Haz doble clic sobre el archivo `index.html`.
2. O bien ejecuta en PowerShell:
   ```powershell
   Start-Process "C:\Users\fflores\Documents\TDOCUMENTOS\2026\Concytec Conecta\index.html"
   ```

---

## ✨ Novedades de UX y Enriquecimiento Iconográfico

1. **Sistema Iconográfico Vectorial Exclusivo (`SERVICE_ICONS`):**
   - Cada servicio cuenta con un icono específico de doble tono dentro de contenedores geométricos suaves (`rounded-2xl`).
   - Todos los chips de categoría cuentan con iconos distintivos (🎓 Acreditación, 💼 Fondos, 📚 Literatura, 🏢 Empresas Ley 30309, 🔬 Infraestructura, 🌱 Formación STEAM).
   - Metadatos enriquecidos con iconos de público destinatario, costos reales y estado de ventanilla.
2. **Dinamismo Visual y Microinteracciones Fluidas:**
   - **Hero con Malla Científica y Orbes Flotantes:** Gradientes radiales interactivos (`floatOrb1`, `floatOrb2`) y tarjeta de búsqueda flotante con resplandor cyan (`shadow-glow-cyan`).
   - **Tarjetas de Perfil Interactivas ("Navega según tu rol"):** Iconografía 3D pastel, micro-animación de elevación al hover (`hover:-translate-y-1 hover:shadow-card-hover`), indicador de conteo de trámites y aro de selección activo.
   - **Métricas de Impacto en Formato Bento Grid:** 4 tarjetas translúcidas de cristal esmerilado (`backdrop-blur-md`) con iconos y cifras destacadas.
   - **Banner Dinámico del Asistente Guiado:** Llamado a la acción con gradiente azul noche y botón de inicio del recomendador en 3 pasos.
3. **Accesibilidad WCAG 2.1 AA:**
   - Atrapamiento de foco (Focus Trap) en todos los modales con tecla Escape.
   - Combobox predictivo accesible por teclado con flechas ↑ / ↓ y Enter.
   - Textos con tamaño mínimo de 12px y contraste reforzado (Slate 600 / Slate 800).
   - Compatibilidad completa con `@media (prefers-reduced-motion: reduce)`.
4. **Sincronización de Estado en la URL:**
   - Guarda los filtros en tiempo real en la barra de direcciones (`?rol=...&cat=...&q=...`) permitiendo compartir búsquedas y navegar con los botones del navegador.

---

## 📂 Archivos del Proyecto

- `index.html`: Prototipo interactivo completo con diseño dinámico.
- `services.json`: Dataset estructurado de los 10 servicios oficiales.
- `convocatorias.json`: Convocatorias activas con cálculo dinámico de días.
- `favicon.svg` / `icon-concytec-conecta.svg`: Isotipo vectorial oficial.
- `README.md`: Documentación técnica.
