# Taller Chic@

Landing local de chapa y pintura. HTML, CSS y JavaScript vanilla, sin compilación ni dependencias de ejecución. Abrir `index.html` con Live Server.

## Diseño actual

Versión simplificada: fondo claro, acento naranja, portada directa y cuatro secciones (presentación, chapa y pintura, el taller y ubicación). Cuatro fotografías diferentes y aparición por opacidad, sin capas, máscaras ni titulares cinematográficos.

## Contenido

Solo se publican los datos facilitados: Taller Chic@, chapa y pintura, El Bosque, Cádiz, 11670. No se incorporan servicios adicionales ni canales de contacto no confirmados.

Se consultaron las referencias públicas de Localitybiz y CoParking el 29 de octubre de 2026. Reproducen «Unnamed Road» y no permiten confirmar una dirección postal exacta. Se utiliza una búsqueda de Google Maps por nombre y localidad, sin coordenadas ni marcador propio.

Las fotografías locales son ilustrativas, no trabajos del negocio. Autores, fuentes y licencia en `recursos.html`. Fuentes locales bajo SIL OFL en `assets/FONT-LICENSE.txt`.

Ambas páginas HTML incluyen una única etiqueta `noindex, nofollow`. Mantenerla si en el futuro se sube el proyecto a un repositorio. Repositorio: https://github.com/pabloldl/tallerchica. La subida del código no configura ningún despliegue.

## Verificación realizada

- Chrome headless mediante Playwright, servida por HTTP local: 375, 768, 1440 y 1920 px. Sin desbordamiento horizontal, cuatro imágenes cargadas en cada tamaño y anclas internas válidas.
- Menú móvil: apertura, cierre con Escape y cierre al navegar.
- Movimiento reducido: los revelados no se inicializan.
- Sin errores de JavaScript en la navegación; `node --check script.js` correcto.
- Una única etiqueta robots en cada HTML, revisada también en el navegador.
- Revisión visual de capturas completas de 375 y 1440 px.

No se ha probado en un iPhone físico ni en Safari. No se ha comprobado el resultado de la búsqueda en la aplicación Google Maps. Herramientas y capturas de comprobación en `.qa/`, excluida mediante `.gitignore`; no son necesarias para ejecutar la web.


