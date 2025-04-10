# 🛒 Sistema de Venta de Productos Ecológicos  
**Documento de Requerimientos del Cliente**

---

## 🧭 Propósito del Sistema

El propósito principal del sistema es permitir la venta digital de productos ecológicos, brindando una experiencia eficiente, segura y accesible tanto para usuarios como para administradores.

---

## 👥 Usuarios del Sistema

Los principales perfiles de usuario serán:

- **Administrador**
- **Personal de servicio al cliente**
- **Encargado de pedidos**
- **Personal de mantenimiento**

---

## ✅ Requerimientos Funcionales

### 👤 Gestión de Usuarios

**3. ¿Qué acciones deben poder hacer los usuarios?**  
Los usuarios podrán:
- Escoger productos
- Añadir o eliminar productos del carrito
- Modificar el contenido del carrito de compras

**4. ¿Deben registrarse o iniciar sesión? ¿Qué datos deben ingresar?**  
Sí, los usuarios deben registrarse o iniciar sesión.  
Campos requeridos:
- Nombre
- Ciudad
- Dirección
- Correo electrónico
- Número de celular
- Número de identificación
- País
- Contraseña

**5. ¿Qué niveles de acceso existen?**  
- **Administrador:** Acceso completo a todas las funcionalidades de la plataforma  
- **Servicio al cliente:** Acceso a redes sociales y chat de la aplicación  
- **Encargado de pedidos:** Acceso exclusivo a la gestión de pedidos  
- **Mantenimiento:** Acceso técnico restringido según necesidad operativa

---

### 📦 Gestión de Productos

**6. ¿Qué productos se ofrecerán?**  
El sistema ofrecerá productos ecológicos variados.

**7. ¿Cómo es el proceso de compra?**  
El proceso incluye:
1. Ingreso al sistema (previo registro/inicio de sesión)
2. Selección de productos
3. Añadir productos al carrito
4. Modificar o eliminar productos del carrito
5. Realizar el pago

**8. ¿Se mostrará un historial de compras?**  
Sí, cada usuario podrá consultar su historial completo de compras y pagos.

---

### ⚙️ Funciones Administrativas

**9. ¿Qué tareas podrá realizar el administrador?**  
El administrador tendrá las siguientes funciones:
- Gestión de usuarios
- Visualización de estadísticas
- Generación de reportes
- Revisión de condiciones de envío

---

### 🔔 Comunicación y Notificaciones

**10. ¿Qué tipo de notificaciones debe enviar el sistema?**  
El sistema debe enviar notificaciones en los siguientes casos:
- Confirmación de compra
- Actualización del estado de envío
- Recuperación de contraseña  
Canales sugeridos: **WhatsApp y correo electrónico**

---

## 🛠️ Requerimientos No Funcionales

**11. ¿En qué dispositivos debe funcionar el sistema?**  
El sistema debe ser accesible desde:
- Computadoras (PC)
- Teléfonos celulares
- Tablets

**12. ¿En qué horario estará disponible?**  
El sistema debe estar disponible las 24 horas del día, los 7 días de la semana.

**13. ¿Qué tan importante es la velocidad del sistema?**  
Es muy importante. Se espera que las páginas carguen rápidamente y que el sistema sea eficiente en todo momento.

**14. ¿Qué nivel de seguridad se requiere?**  
Se necesita un **alto nivel de seguridad** debido al manejo de información sensible como datos personales y detalles de pago.  
No se debe compartir información con terceros.

**15. ¿Debe integrarse con otras plataformas?**  
Sí. El sistema debe integrarse con:
- **WhatsApp** (comunicación)
- **Correo electrónico** (notificaciones)
- **PSE** (pasarela de pagos)
