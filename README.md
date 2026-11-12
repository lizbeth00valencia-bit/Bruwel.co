# BRUWEL — tienda online (primera versión)

Tienda web responsive creada con React + Vite. Incluye navegación, categorías, búsqueda, ordenamiento por precio, tarjetas de producto, carrito y preparación del pedido para WhatsApp.

## Requisitos
- Node.js 20 o superior
- Git (opcional, para subirlo a GitHub)

## Ejecutar en tu computador
1. Descomprime la carpeta.
2. Abre una terminal dentro de `bruwel-store`.
3. Ejecuta `npm install`.
4. Ejecuta `npm run dev`.
5. Abre en el navegador la dirección local que muestra Vite (normalmente `http://localhost:5173`).

## Configurar WhatsApp
Abre `src/config.js` y cambia `WHATSAPP_NUMBER` por el número de BRUWEL con indicativo, solo números. Ejemplo de Colombia: `573001234567`.

## Importante sobre esta primera versión
- Los productos y precios son datos de demostración: reemplázalos por tu catálogo real antes de publicar.
- Las fotografías actuales son imágenes de muestra alojadas externamente; después incorporaremos tus fotografías.
- El carrito arma un mensaje y abre WhatsApp; no procesa pagos ni confirma inventario.
- Todavía no guarda clientes, pedidos ni reseñas en una base de datos. La siguiente etapa será conectar Supabase y crear el panel privado de administración.
- No se muestran testimonios inventados: la sección de opiniones explica que se activará con reseñas reales.
- El formulario de marketing y el almacenamiento de datos se incorporarán cuando definamos el aviso de privacidad y el consentimiento correspondiente.

## Publicar gratis
Puedes subir esta carpeta a un repositorio GitHub y conectarlo con Vercel, o usar GitHub Pages con la configuración adecuada para Vite. El alojamiento gratuito puede tener límites de uso y condiciones del proveedor.
