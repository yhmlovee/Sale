# Closet Sale — versión 1

Esta es una web estática pensada para un closet sale de mudanza. No necesita base de datos ni servidor.

## Antes de publicarla

1. Abre `index.html`.
2. Busca `569XXXXXXXX` y sustitúyelo por tu WhatsApp, sin `+`, espacios ni guiones.
3. En la sección `const products = [...]` añade tus productos.
4. Mete las fotos en la carpeta `images/`.
5. En cada producto, escribe el nombre exacto del archivo en `image`.

### Estados

- `available` = Disponible
- `reserved` = Reservado
- `sold` = Vendido

Para vender algo, cambia por ejemplo:

`status: "available"`

a:

`status: "sold"`

## Publicarlo gratis con GitHub Pages

1. Crea una cuenta en GitHub.
2. Crea un repositorio nuevo (por ejemplo `closet-sale`).
3. Sube `index.html`, `style.css`, `README.md` y la carpeta `images`.
4. En GitHub entra en **Settings → Pages**.
5. En **Build and deployment**, selecciona **Deploy from a branch**.
6. Elige `main` y la carpeta `/ (root)`.
7. Guarda. GitHub te mostrará la dirección pública de la web.

Puedes poner esa dirección en tu bio de TikTok.

## Fotos

Usa fotos verticales, idealmente todas con una proporción parecida. El diseño recorta las imágenes para que las tarjetas queden uniformes.

## Nota

Esta versión no cobra dentro de la web. El botón “Lo quiero” abre WhatsApp con un mensaje preparado. Para un mercadillo temporal es intencionadamente sencillo.
