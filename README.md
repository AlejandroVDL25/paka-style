# Paka Style

Tienda de moda urbana **Paka Style** (Estilo & Flow en toda ocasión). Página web de una sola pieza: catálogo, filtros, carrito y pedido por WhatsApp.

- Catálogo, tallas y carrito funcionan en el navegador.
- Los pedidos se cierran por WhatsApp; la página no cobra ni descuenta existencias.
- Archivo principal: `index.html`.

## Dos ajustes rápidos dentro de `index.html`
Busca estas dos cadenas (Ctrl+F) y cámbialas con cuidado, sin tocar nada más:
- `"demoNotice":true` → ponlo en `false` cuando ya tengas tus productos reales (quita el aviso de vista previa).
- `"shareUrl":""` → entre las comillas pon el enlace público de tu tienda (empieza con `https://`) para activar el botón "Compartir esta pieza".

Para cambiar productos, precios o existencias, edita el bloque de datos `<script type="application/json" id="paka-data">` o pide que lo regeneren.
