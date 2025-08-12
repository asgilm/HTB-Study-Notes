# TABLA DE CONTENIDO

1. [Fundamentos de redes](#fundamentos-de-redes)
   - Network Concepts (Conceptos de redes)
     - Modelo OSI
   
---

## Fundamentos de redes
### Network Concepts

❗MODELO OSI (Open Systems Interconnection)

![Estructura Mundo Digital](../images/modelo-OSI.jpg)

- Capa 1 - Fisica: Cables ethernet, Hubs, repetidores etc.
- Capa 2 - Enlace: Switches, usan MAC address
- Capa 3 - Red: Es responsable del direccionamiento logico y determina rutas, Routers operan en esta capa, **Direcciones IP (Internet Protocol)**
- Capa 4 - Transporte: TCP (Transmission Control Protocol) y UDP (User Datagram Protocol)
     - TCP: Garantiza transmisión confiable y conexiones con recuperación de errores.
     - UDP: No se conecta con nadie, pero es mas rapido, aunque no garantiza la entrega.
- Capa 5 - Sesión: Establece, mantiene y cierra conexiones.
- Capa 6 - Presentación: Muestra los datos transferidos, esto incluye el cifrado y descifrado de datos, si se comprimen los datos o la conversión de datos (Todo para que sea legible al final)
- Capa 7 - Aplicación: Todo lo que se puede acceder atraves de una aplicación, acceder a archivos, transferirlos, modificarlos, verlos etc. **DNS, HTTP, FTP, SMTP**

![Estructura Mundo Digital](../images/modelo-OSI-2.jpg)

---
