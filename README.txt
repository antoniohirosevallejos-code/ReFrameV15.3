Reframe Flow by Content Flow — V11

Contenido: index.html, style.css, app.js, icono y demo-conversion.webp.

Cambios V11:
- Demo de portada sustituida por la imagen panorámica aprobada por el usuario, optimizada a WebP.
- Quitada la flecha del botón de portada “Ir a la herramienta”.
- Eliminada la línea redundante “Sin cortar lo importante” debajo del botón.
- Acción principal renombrada a “Adaptar video”.
- Textos de renderizado en español coherente: “Preparando la herramienta…”, “Adaptando video” y formatos “Vertical”, “Cuadrado” y “Horizontal”.
- Conservado el procesamiento local, selección de formato, recorte opcional, miniaturas estáticas de resultados y descarga MP4.

Importante: la imagen de portada es una ilustración demostrativa, no una salida generada en tiempo real por la herramienta. Probar el paquete en el navegador y en el dispositivo objetivo antes de publicarlo. El motor FFmpeg se carga desde internet.


Cambios V13: imagen de demostración antes del botón principal; flecha restaurada únicamente en el enlace de navegación; estado de renderizado más claro y visualmente bloqueado sin cubrir el progreso ni el botón de cancelación. Basada en V12.

V15.1: demo previews now use the same original image fitted without cropping or distortion over a blurred fill background; showcase vertical padding is balanced; source preview pauses immediately when rendering starts.

V15.3: regenerated all four showcase assets from the user-supplied clean original image. Each frame uses the same undistorted full image centered over a zoomed, blurred fill derived from that image; no green line is baked into any image. Removed unused demo-conversion.webp (not referenced by index.html, app.js, or style.css).
