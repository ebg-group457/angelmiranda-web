# angelmiranda.co
Sitio estático (HTML/CSS) listo para GitHub Pages. Archivos: index.html, styles.css, favicon.svg, CNAME. Buscar "[por confirmar]" para datos pendientes.

## Banner de inicio (carrusel)
Las fotos del banner están en `index.html`, dentro de `<div class="slides">`. Para agregar una:
1. Suba la foto a `img/` (JPG, ~1600 px de ancho, < 300 KB).
2. Copie una línea `<figure class="slide">` y cambie `src`, `alt` y el `<figcaption>` (opcional, nombre del proyecto). Use `loading="lazy"` en todas menos la primera; solo la primera lleva la clase `on`.
Los puntos de navegación se generan solos. Rota cada 5 s, pausa al pasar el mouse, permite deslizar en celular y respeta "reducir movimiento".
