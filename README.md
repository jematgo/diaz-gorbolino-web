# Díaz Gorbolino — sitio web estático

Landing institucional de derecho laboral argentino, con secciones diferenciadas para trabajadores y empresas. El único canal de contacto del sitio es WhatsApp.

## Antes de publicar

1. Abrí `index.html` y `styles.css` si querés revisar el contenido y el diseño.
2. Reemplazá **todas** las apariciones de `549XXXXXXXXXX` por el número real de WhatsApp del estudio, con código de país y área, sin `+`, espacios ni guiones. Ejemplo de formato: `54911XXXXXXXX` (no uses este ejemplo como número real).
3. Reemplazá los textos entre corchetes con dirección, horarios y ubicación reales, o eliminá esos bloques si todavía no están definidos.
4. Revisá que las áreas de práctica y los textos describan servicios que el estudio efectivamente presta.

## Probar en la computadora

Doble clic en `index.html` para abrirlo en el navegador. Para una vista previa local más cómoda, abrí la carpeta con Visual Studio Code y usá la extensión Live Server.

## Publicar gratis con GitHub Pages

1. Creá un repositorio nuevo en GitHub.
2. Subí directamente el contenido de esta carpeta (no el ZIP ni la carpeta contenedora): `index.html`, `styles.css`, `script.js` y `_headers`.
3. En GitHub, entrá a **Settings → Pages**.
4. En **Build and deployment**, elegí **Deploy from a branch**, rama `main` y carpeta `/ (root)`, y guardá.
5. Esperá a que GitHub genere la dirección pública.

Este sitio es estático: no necesita funciones de servidor, base de datos, formulario, Turnstile, Resend ni variables secretas. Los botones de WhatsApp abrirán el chat cuando completes el número real.

## Cloudflare Pages

También podés importar el mismo repositorio en Cloudflare Pages. Como no hay proceso de compilación, dejá el comando de build vacío y el directorio de salida como `/` si subís estos archivos a la raíz.
