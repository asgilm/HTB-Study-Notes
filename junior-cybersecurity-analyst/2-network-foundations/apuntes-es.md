# TABLA DE CONTENIDO

1. [Fundamentos de redes](#fundamentos-de-redes)
   - Network Concepts (Conceptos de redes)
     - Modelo OSI
     - Modelo TCP/IP

2. [Comunicación y Direccionamiento de red](#network-communication-and-addressing)

   
---

## Fundamentos de redes
### Network Concepts

❗MODELO OSI (Open Systems Interconnection) ❗

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

![Estructura Mundo Digital](../images/modelo-OSI-2.png)

🔍 EJEMPLO DE ENVIO DE UN ARCHIVO 🔍

❗Se envia un archivo ➡️ Capa de aplicación: Inicia la solicitud de transferencia del archivo ➡️ Capa de Presentación: Cifra el archivo ➡️ Capa Sesión: Inicia una sesión de comunicación con el receptor ➡️ Capa de Transporte: El archivo se segmenta para que no hayan errores en la transmisión ➡️ Capa de Red: Se determina la mejor ruta para transferir los datos del archivo ➡️ Capa de Enlace de Datos: Encapsula los datos en tramas para entregarlos nodo a nodo ➡️ Capa Fisica: Transmite los bits del archivo a traves de medio fisico, completando el proceso. ❗

❗MODELO TCP/IP ❗

![Estructura Mundo Digital](../images/modelo-TCP-IP.png)

❗OSI vs TCP/IP❗

![Estructura Mundo Digital](../images/OSI-vs-TCP-IP.png)

💻 Modos de transmisión
- Simplex: Solo permite comunicación unidireccional, por ejemplo como de un teclado al computador.
- Half-duplex: permite comunicación bidireccional pero no simultanea, como por ejemplo los Walkie-talkies que se debe turnar para hablar.
- Full-duplex: El modo usado en llamadas telefonicas, admite comunicación bidireccional simultanea.

---

## Network Communication and Addressing
###

---
