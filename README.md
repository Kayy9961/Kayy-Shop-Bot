# Kayy Shop - Bot de Discord 🚀

## 📌 Descripción

**Kayy Shop** es un bot de Discord automatizado diseñado para gestionar la compra de seguidores, likes, visitas y espectadores en directo para redes sociales como **Instagram** y **TikTok**. Además, ofrece un avanzado sistema de automatización de pagos y pedidos, asegurando que los usuarios reciban sus servicios sin necesidad de intervención manual.

Este bot permite a los usuarios:
- Abrir tickets dentro de Discord.
- Seleccionar su servicio.
- Realizar el pago.
- Recibir el pedido sin esperas ni procesos complicados.

---

## 🔧 Sistema de Automatización de Pedidos

### ✅ Generación Automática de Pedidos
- **Selección de la plataforma:** Instagram o TikTok.
- **Tipo de servicio:** Seguidores, likes, visitas o espectadores en directo.
- **Visualización automática de precios:** Según el servicio y la cantidad seleccionada.
- **Generación instantánea:** Enlace de pago con instrucciones detalladas.

### ✅ Verificación Automática de Pagos
- **Integración con PayPal:** Detección automática de pagos mediante IMAP y análisis de correos electrónicos.
- **Validación:** Verificación de la cantidad pagada y la nota adjunta.
- **Confirmación instantánea:** El pedido se procesa sin intervención manual.

### ✅ Procesamiento y Entrega de Pedidos
- **Envío automático:** Solicitud enviada al proveedor tras la confirmación del pago.
- **Uso de APIs externas:** Gestión eficiente de los pedidos.
- **Actualización en tiempo real:** Confirmación y estado del pedido actualizado dentro del ticket de soporte.

### ✅ Seguimiento y Confirmación de Pedidos
- **Historial de pedidos:** Disponible en el canal del ticket.
- **Cierre automático:** El ticket se cierra una vez completado el pedido.
- **Notificaciones:** Si el pedido no se completa en el tiempo estimado, el bot notifica a los administradores para revisión manual.

---

## 🌟 Características Adicionales

### 🎥 Espectadores en Directo en TikTok
- **Selección de duración y cantidad:** Personalización del servicio.
- **Procesamiento automatizado:** Tras la confirmación del pago.
- **Integración con proveedores:** Entrega rápida y segura.

### 💱 Sistema de Exchange Automatizado
- **Intercambio de métodos de pago:** PayPal, Bizum, Litecoin, Paysafecard.
- **Cálculo automático:** Tasas y comisiones según el método seleccionado.
- **Transferencia automática:** Confirmación y traspaso del saldo.

### 🎮 Compra de Bits para Twitch
- **Opciones disponibles:** Desde 5000 hasta 50000 bits.
- **Métodos de pago:** PayPal o Litecoin con validación automática.
- **Entrega inmediata:** Tras la verificación del pago.

---

## 💻 Tecnologías Utilizadas
- **Python** con [discord.py](https://discordpy.readthedocs.io/) para la gestión del bot.
- **BeautifulSoup4:** Extracción de datos de PayPal.
- **AsyncIO:** Manejo de procesos asíncronos.
- **IMAPLib:** Verificación automática de pagos en correos electrónicos.
- **Requests:** Interacción con APIs externas para realizar pedidos automáticamente.
