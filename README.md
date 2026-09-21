# GITANOS

Tienda y central de operaciones de demostración. Todo está incluido en este repositorio: HTML, CSS, JavaScript, imágenes, fuentes y datos ficticios. No requiere Node, Render, base de datos, claves de API ni servicios externos para funcionar en GitHub Pages.

## Acceso de prueba

- Email: **prueba1@gimail.com**
- Contraseña: **1234**
- En la tienda, pulsar **Ingresar**. Se puede explorar como administrador, cancha o proveedor.
- Es un acceso simulado implementado en el navegador; no protege datos reales.

## Tienda

Cinco choripanes de autor, dos cervezas artesanales, fichas de productos, carrito, checkout sin pagos, retiro/delivery simulado y resumen descargable. Quiénes somos, presupuesto de eventos, equipamiento en concesión y formularios para canchas, proveedores y consumidores.

## Central

- 14 proveedores ficticios: tres de chorizos, panadería, packaging y cerveza; dos de salsas pendientes de selección.
- Comparador de costos, proveedor activo y fichas de estándares orientativos.
- Tres predios, pedidos históricos, entregas en curso y comprobantes internos.
- Pedidos divididos automáticamente por proveedor; la entrega recibida actualiza el stock y genera el comprobante al completarse.
- Venta local con protección de reserva de combos para delivery; cerveza descontada por volumen.
- Facturación de demostración, registro de cobro y exportación CSV.
- Reclamos, eventos, solicitudes y equipamiento en concesión.
- PedidosYa simulado, con entrada y avance de pedidos.

## Datos y dispositivos

Los datos iniciales viven en `data.js` y aparecen completos al abrir la web por primera vez desde cualquier dispositivo. Las pruebas posteriores se guardan en `localStorage` de ese navegador. No se sincronizan entre dispositivos. La sesión demo usa `sessionStorage`.

Para volver a los ejemplos iniciales: pie de la tienda → **Sobre esta demo** → **Restablecer demo**. Esto solo borra las modificaciones de demostración de ese navegador.

## GitHub Pages

El sitio se sirve desde la rama `main`, carpeta `/(root)`. En GitHub: **Settings → Pages → Deploy from a branch → main → /(root) → Save**. Todas las rutas de assets son relativas para funcionar bajo `/gitanos/`; el administrador usa `#admin` y la tienda `#tienda`, sin reglas de redirección.

## Alcance de la demostración

No se envían pedidos, emails ni mensajes a personas reales. No hay cobros, facturas fiscales, autenticación de producción ni conexión real con PedidosYa. Las fichas son borradores comerciales, no recetas industriales aprobadas. Proveedores, responsables, contactos, horarios, precios, ventas, acuerdos y equipamiento son ficticios.

El Poli (Federación Flores) y Club La Palmera son nombres de predios usados como referencia, **sin relación comercial confirmada con Gitanos**. Distrito 5 Fútbol es inventado. Fuentes de referencia:

- https://www.hoysejuega.com/canchas-de-futbol/88-el-poli-federacion-flores.htm
- https://canchafija.com.ar/t/club-la-palmera
- https://integrar.pedidosya.com/es/documentation/

Las ocho fotografías se generaron con la herramienta integrada de generación de imágenes para esta demo. Las tipografías Barlow Condensed y DM Sans se incluyen en `assets/`; conservan sus licencias SIL Open Font License. El sitio no carga librerías, imágenes o fuentes desde CDNs.
