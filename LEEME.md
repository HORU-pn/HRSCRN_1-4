# Horu's Ocarina 1.2 · versión web instalable

Esta carpeta es la app lista para publicar en internet y añadirla como app en el móvil.

## Contenido
- `index.html`: la app completa.
- `manifest.webmanifest`: nombre, colores e icono de la app instalada.
- `icons/`: iconos para la pantalla de inicio (Android, iPhone e iPad).
- `sw.js`: permite instalarla y abrirla sin conexión.

## Publicarla (elige una opción)
**Netlify Drop (lo más rápido):** entra en https://app.netlify.com/drop y arrastra esta carpeta
entera. Te da un enlace `https://…netlify.app`.

**GitHub Pages:** sube estos archivos a un repositorio público y activa
Settings → Pages → Deploy from a branch → main / (root).

Sube siempre la carpeta completa: si solo subes `index.html`, no se podrá instalar.

## Qué ve quien la abre en el móvil
- **Android (Chrome):** un aviso con **Añadir** (la instala), **Recordármelo más tarde** y
  **No volver a mostrar**.
- **iPhone / iPad (Safari):** un aviso que explica cómo hacerlo: botón **Compartir** →
  **Añadir a pantalla de inicio**. Apple no permite que una web se instale sola.
- Cuando ya está instalada, o en un PC, el aviso no aparece.

Abriendo el HTML desde Descargas o WhatsApp no se puede instalar: los móviles solo lo permiten
con webs publicadas en `https://`.
