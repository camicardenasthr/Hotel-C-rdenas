# Hotel Cárdenas — sitio web

Sitio web estático responsive para Hotel Cárdenas, Cartagena de Indias.

## Publicar con GitHub Pages
1. En GitHub, abre **Settings → Pages**.
2. En **Build and deployment**, selecciona **Deploy from a branch**.
3. Selecciona la rama `main` y la carpeta `/ (root)`; guarda.
4. GitHub publicará el sitio en `https://camicardenasthr.github.io/Hotel-C-rdenas/` cuando termine el despliegue.

## Configuración necesaria antes de recibir clientes
- **WhatsApp:** en `index.html`, reemplaza el valor vacío de `WHATSAPP_NUMBER` por el número oficial con código de país y solo dígitos (ej. `573001234567`).
- **Concierge IA:** el chat incluido es una experiencia demostrativa con respuestas guiadas. Para un concierge con IA generativa real 24/7 se necesita un backend/API (por ejemplo, una función serverless) y una clave de proveedor guardada como secreto del servidor; nunca se debe exponer una clave en el navegador.
- **Reservas:** el formulario prepara una consulta y la dirige a WhatsApp. No consulta inventario ni confirma disponibilidad en tiempo real.
- **Tarifas:** precios de referencia en COP por habitación/noche, sujetos a temporada, disponibilidad, impuestos y validación comercial.

## Inventario de habitaciones
- 34 King Signature: una cama King.
- 33 Double Queen: dos camas Queen.
- 33 Suite Cárdenas: suite con una cama King.
- Total: 100 habitaciones.

## Tarifas iniciales orientativas
- King Signature: desde $520.000 COP.
- Double Queen: desde $620.000 COP.
- Suite Cárdenas: desde $890.000 COP.

Diseño editorial en tonos verde profundo, marfil y dorado; tipografías Playfair Display y DM Sans.
