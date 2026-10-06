# Política de privacidad — Patueli

**Última actualización: 6 de octubre de 2026**

Patueli ("la app") es una aplicación para Android que registra tus compras a partir de las notificaciones de tus aplicaciones bancarias y las organiza por categoría para que lleves el control de tus gastos del mes.

Esta política explica qué información maneja la app, cómo la usa y qué control tienes sobre ella.

## 1. Resumen en una frase

**Todo lo que la app lee y guarda queda en tu teléfono.** La app no tiene servidores, no requiere cuenta de usuario y no envía tus datos a internet ni a terceros.

## 2. Qué datos procesa la app

### 2.1 Notificaciones (permiso "Acceso a notificaciones")

Para detectar compras, la app usa el permiso de Android **acceso a notificaciones** (`BIND_NOTIFICATION_LISTENER_SERVICE`). Con él, la app recibe el texto de las notificaciones que muestran otras aplicaciones y:

- Analiza el texto para reconocer si corresponde a una **compra con tarjeta** o a una **transferencia** de una aplicación bancaria o fintech (por ejemplo Banco de Chile, BancoEstado, Santander, BCI, Scotiabank, Falabella CMR, Tenpo, MACH, Mercado Pago).
- Si lo es, extrae y guarda **monto, nombre del comercio, fecha y hora, tipo de movimiento, medio de pago (crédito/débito/prepago) y el texto original de la notificación**.
- Si la notificación **no** es una compra ni una transferencia (promociones, avisos de seguridad, mensajes de otras apps), se descarta y **no se guarda**. Únicamente para las notificaciones de bancos conocidos que no se reconocen, la app guarda las últimas 50 en tu teléfono (sección "Notificaciones no reconocidas" en Ajustes) para que puedas registrarlas a mano o descartarlas.

La app **no lee** el contenido de tus mensajes, correos, chats ni de ninguna otra aplicación con otro fin que el descrito, y no guarda notificaciones que no sean de aplicaciones bancarias o fintech.

### 2.2 Datos que ingresas tú

Gastos que agregas a mano (monto y nombre), categorías que corriges, presupuesto mensual y preferencias de la app.

### 2.3 Datos que la app NO recopila

- No pide ni almacena credenciales bancarias, números de tarjeta completos ni claves.
- No accede a tus contactos, ubicación, cámara, micrófono, archivos ni historial de navegación.
- No usa identificadores publicitarios ni herramientas de analítica o seguimiento.
- No contiene publicidad.

## 3. Dónde se guardan los datos y quién tiene acceso

- Los datos se guardan en una base de datos **local y privada** de la app en tu teléfono, a la que otras aplicaciones no tienen acceso.
- La app **no envía datos a internet**. No existe un servidor de Patueli ni una cuenta en la nube.
- El permiso de internet que aparece en la ficha de la app lo requiere una librería del sistema (Google Play services) y no se usa para transmitir tus datos.

### 3.1 Copias de seguridad

Puedes exportar tus movimientos a un archivo JSON en la carpeta que elijas, y opcionalmente activar un backup automático nocturno en esa carpeta. **Ese archivo contiene tus movimientos y el texto de las notificaciones originales, sin cifrar**: trátalo como información personal. Tú decides dónde guardarlo y con quién compartirlo.

Además, Android puede incluir los datos de la app en la copia de seguridad del dispositivo asociada a tu cuenta de Google (función "Copia de seguridad" de Android), según la configuración de tu teléfono. Esa copia está sujeta a la política de privacidad de Google.

## 4. Compartir datos

La app solo comparte información cuando **tú lo decides explícitamente**: al usar "Compartir" en un movimiento, al exportar un backup o al usar "Reportar formato" en una notificación no reconocida (que abre el selector de apps de Android para que elijas por dónde enviarla). En ningún caso la app comparte datos de forma automática.

## 4.1 Suscripción y pagos

Patueli ofrece una prueba gratuita de 7 días (que empieza con la primera compra registrada) y después un plan de pago mensual o anual. El pago se realiza exclusivamente a través de **Google Play Billing**: la app nunca ve ni almacena datos de tu tarjeta ni de tu cuenta de pago. Google Play nos entrega únicamente un identificador de la compra para saber si tu plan está activo; ese identificador se guarda en tu teléfono. El historial de compras está sujeto a la política de privacidad de Google Play.

## 5. Permisos que solicita la app y para qué

| Permiso | Uso |
|---|---|
| Acceso a notificaciones | Detectar compras y transferencias en las notificaciones de tus apps bancarias. Es la función principal de la app. |
| Notificaciones (POST_NOTIFICATIONS) | Avisarte cuando te acercas o superas tu presupuesto mensual, recordarte cuotas y avisarte si el backup automático dejó de funcionar. |
| Inicio tras reinicio | Volver a programar esas alarmas cuando el teléfono se reinicia. |

Puedes revocar el acceso a notificaciones en cualquier momento desde **Ajustes de Android → Notificaciones → Acceso a notificaciones**. La app seguirá funcionando con los datos ya guardados y con los gastos que agregues a mano.

## 6. Conservación y eliminación

Los datos se conservan en tu teléfono hasta que los borres. Puedes:

- Eliminar movimientos uno a uno desde la app.
- Borrar todos los datos con **Ajustes → Eliminar toda la data**.
- Desinstalar la app, lo que elimina su base de datos local (los archivos de backup que hayas exportado a tus carpetas no se borran automáticamente).

## 7. Menores de edad

La app no está dirigida a menores de 13 años y no recopila conscientemente información de ellos.

## 8. Cambios a esta política

Si la app incorpora en el futuro alguna función que cambie la forma en que se manejan los datos (por ejemplo, sincronización en la nube), esta política se actualizará y la fecha de "Última actualización" cambiará. Los cambios relevantes se informarán dentro de la app.

## 9. Contacto

Para preguntas sobre privacidad: **alexisveracataldo@gmail.com**.
