# Horu's Ocarina 1.5 · versión web instalable

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

## Actualizar la web en GitHub
1. Entra en tu repositorio en github.com.
2. Pulsa **Add file → Upload files** y arrastra **todo el contenido** de esta carpeta
   (`index.html`, `sw.js`, `manifest.webmanifest`, `NOVEDADES.md`, `LEEME.md` y la carpeta `icons`).
3. Escribe un mensaje, por ejemplo «Versión 1.5», y pulsa **Commit changes**.
4. En uno o dos minutos la web se actualiza. Si alguien no ve los cambios, que recargue la página
   (o cierre y abra la app instalada).

Quien ya usaba la app verá una vez la ventana **Novedades de la versión 1.5**. Se puede volver a
abrir en cualquier momento pulsando **ver 1.5**, arriba a la izquierda.
