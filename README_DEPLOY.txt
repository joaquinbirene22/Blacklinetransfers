Blackline Transfers — Publish v3.1
Fecha de build: 2025-10-29 19:27

Contenido:
- index.html (optimizado con metas sociales, Schema.org TransportationService + FAQPage, mejora de formulario a WhatsApp, accesibilidad y i18n)
- /assets/og.jpg (1200x630)
- favicon.ico

Cómo publicar (rápido):
1) Netlify
   - Cree un sitio nuevo y arrastre la carpeta completa "blackline_publish_v3_1".
   - Configure dominio temporal (ej: https://blackline-transfers.netlify.app).
   - Luego agregue su dominio final y HTTPS.
2) Cloudflare Pages
   - Cree un proyecto y suba esta carpeta.
   - Asigne dominio y active compresión/HTTP3.
3) Vercel
   - "Import Project" -> "Other" -> Suba carpeta -> Deploy.

Google Sites (limitado):
- Insertar -> "Incorporar" -> pestaña "Insertar código" -> pegue SOLO el contenido del <body> interno.
- Las metas del <head> y JSON-LD no impactarán en SEO dentro de Sites. Para SEO serio, prefiera hosting propio.

Ajuste de dominio:
- Edite en index.html:
  - <link rel="canonical" href="/">  -> reemplazar por su URL final (https://su-dominio.com/).
  - <link rel="alternate" ...>      -> idem.
  - <meta property="og:image" ...>  -> puede dejar ruta relativa /assets/og.jpg si aloja en raíz.

Contacto institucional (WhatsApp):
- Usando +54 221 314 9313 (configurable en el script al final del archivo).

Sugerencia:
- Cree también una versión /en si desea multi-idioma real. El script ya detecta lang="en" si lo configura en <html lang="en">.