# firefoxCustomization

Una configuración CSS personalizada para transformar Firefox en un entorno de navegación estético y funcional. Diseñado para usuarios de Linux que buscan un flujo de trabajo integrado y visualmente cohesivo.

## Características
* **Glassmorphism UI:** Efectos de transparencia y desenfoque (blur) inspirados en macOS.
* **Integración:** Optimizado para entornos de escritorio Linux (ideal para Cinnamon/GTK).
* **Limpieza:** Barra de herramientas simplificada y optimización de espacio para pestañas.
* **Flexibilidad:** Estilos aplicables a través de `userChrome.css` (UI) y `userContent.css` (web content).

## Instalación

1. **Localizar tu perfil:**
   Escribe `about:support` en la barra de direcciones de Firefox y busca la ruta de **Carpeta del perfil**.

2. **Habilitar personalización:**
   * Abre la carpeta de tu perfil.
   * Crea una carpeta llamada `chrome` (si no existe).
   * En `about:config`, asegúrate de que `toolkit.legacyUserProfileCustomizations.stylesheets` esté establecido en `true`.

3. **Instalar los estilos y Configuracion:**
   Copia los archivos `userChrome.css` y `userContent.css` dentro de la carpeta `chrome` recién creada.

4. **Reiniciar:**
   Reinicia el navegador para aplicar los cambios.

## Dependencias sugeridas
* Para obtener el efecto de desenfoque nativo en Linux, se recomienda utilizar un compositor de ventanas con soporte para *blur* (como `picom` o el gestor nativo de Cinnamon u otra distribuciones).

## Contribuciones
Los Pull Requests son bienvenidos. Si tienes ajustes específicos para otras distribuciones o entornos, no dudes en compartirlos.

---
*Diseñado por mrrat0*
