# 🏗️ Reformas Integrales Barcelona · Grupo CNLPRO

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/danalle190196-rgb/reformas)

Sitio web oficial y landing page de alta conversión para **Grupo CNLPRO**, especializado en reformas integrales, cocinas, baños, fachadas SATE y rehabilitación en Barcelona y comarcas.

- **Repositorio GitHub:** [github.com/danalle190196-rgb/reformas](https://github.com/danalle190196-rgb/reformas)
- Construido según las especificaciones de diseño en [`DESIGN.md`](./DESIGN.md) y la referencia visual [`screen.png`](./screen.png).

---

## 🚀 Cómo abrir y probar la web

Este proyecto está construido en **HTML5 estándar + Tailwind CSS + Vanilla JavaScript**, por lo que **no requiere instalar Node.js, Python ni servidores**.

1. **Abrir directamente:** Haz doble clic en el archivo [`index.html`](./index.html) para abrirlo en tu navegador favorito (Chrome, Edge, Firefox, Safari).
2. **Con VS Code:** Si usas Visual Studio Code, puedes hacer clic derecho en `index.html` y seleccionar **"Open with Live Server"**.

---

## ✨ Características y Funcionalidades Implementadas

### 1. 📱 Integración directa con WhatsApp (Generación de Leads)
- **Formulario Rápido del Hero:** Toma el nombre, teléfono, metros cuadrados y tipo de reforma y genera automáticamente un mensaje estructurado en WhatsApp listo para enviar.
- **Calculadora de Costes en Tiempo Real:** Calcula el rango de precio según tipo de obra (Piso completo, cocina, baño, local), metros cuadrados (slider dinámico) y nivel de calidades (Estándar, Premium, Lujo). Incluye un botón para **enviar el presupuesto desglosado a WhatsApp**.
- **Formulario de Contacto Detallado:** Incluye campos completos, selección de servicio, campo de notas del proyecto, casilla obligatoria de RGPD y envío a WhatsApp.
- **Botón Flotante de WhatsApp:** Visible en todo momento en la esquina inferior derecha con mensaje y tooltip de soporte inmediato.
- **Barra Móvil Inferior Fija:** En dispositivos móviles, ofrece botones rápidos de llamada directa telefónica (`936 94 03 38`) y chat de WhatsApp.

### 2. 🔄 Comparador Interactivo "Antes y Después"
- Permite alternar en tiempo real entre el estado original de la obra (antes) y el resultado arquitectónico finalizado (después) con etiquetas y fotos en alta definición.

### 3. ❓ Acordeón de Preguntas Frecuentes (FAQ)
- 8 preguntas técnicas habituales sobre plazos, presupuesto cerrado, licencias con el Ayuntamiento de Barcelona, garantías oficiales (Seguro RC de 1.000.000 € y REA) y formas de pago.
- Animación fluida de apertura/cierre.

### 4. 🎥 Testimonio en Vídeo Modal
- Tarjeta interactiva con previsualización del caso de éxito de reforma en Gràcia que abre un modal emergente con detalles y llamada a la acción.

### 5. ⚖️ Cumplimiento Legal y RGPD
- Modales interactivos para **Aviso Legal**, **Política de Privacidad** y **Política de Cookies**.
- **Banner de Cookies:** Guarda la preferencia del usuario en `localStorage` para no volver a molestar tras ser aceptado o rechazado.

### 6. 📱 Menú Móvil Responsive
- Menú desplegable tipo cajón (drawer) accesible mediante botón de hamburguesa en pantallas móviles y tablets.

---

## 🛠️ Cómo Personalizar Datos

Todos los textos y números se encuentran centralizados en [`index.html`](./index.html):

| Dato | Dónde cambiarlo |
|---|---|
| **Número de WhatsApp** | Busca `34936940338` y reemplázalo por tu número con código de país (ej. `34612345678`). |
| **Teléfono fijo / oficina** | Busca `936940338` o `936 94 03 38` para cambiar las llamadas telefónicas. |
| **Correo electrónico** | Busca `info@reformasintegralesbarcelona.es`. |
| **Nombre de empresa** | Busca `Grupo CNLPRO` o `Reformas Integrales Barcelona`. |

---

## 🌐 Cómo Publicar la Web en Internet (Gratis)

Puedes alojar esta web en minutos con cualquiera de estas opciones gratuitas:
1. **Netlify:** Arrastra la carpeta `refprmas` directamente a [netlify.com/drop](https://app.netlify.com/drop).
2. **Vercel:** Conecta tu repositorio o sube la carpeta con `npx vercel`.
3. **GitHub Pages:** Sube los archivos a un repositorio de GitHub y activa GitHub Pages en *Settings > Pages*.
4. **Hosting tradicional (cPanel / Hostinger / DonDominio):** Sube el archivo `index.html` a la carpeta `public_html`.
