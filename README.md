# **🌐 Comunicación de Redes: Fundamentos y Protocolos**
Este repositorio documenta los principios esenciales de la **comunicación digital**, explorando cómo los **datos** viajan entre **dispositivos** mediante **protocolos estandarizados** y cómo diagnosticar problemas comunes en el desarrollo de **software**.

"La comunicación de redes permite que equipos y aplicaciones compartan información de forma eficiente en **Internet** y **redes locales**."

## **🚀 Conceptos Base de Redes** 
La base de la comunicación moderna se divide principalmente en dos **protocolos de transporte**:

## **TCP** (**Transmission Control Protocol**)
Protocolo orientado a la **conexión** que verifica la entrega de **paquetes**.

**Seguridad:** Garantiza que los datos lleguen completos y en orden.

**Uso común:** Transferencia de archivos, **transacciones**, correos electrónicos y **APIs REST**.

**Características:** Es más lento debido a los mecanismos de confirmación (**ACK**), pero altamente confiable.

## **UDP** (**User Datagram Protocol**)
Protocolo sin **conexión** que envía datos directamente sin verificación.

**Velocidad:** Extremadamente rápido al no requerir confirmaciones.

**Uso común:** Videollamadas, juegos online, transmisiones en vivo y consultas **DNS**.

**Características:** No garantiza el orden ni la entrega, priorizando la fluidez.

## 🔌 Puertos y Servicios
Un **puerto** es un número (0-65535) que identifica un **servicio** específico dentro de un **dispositivo**. Mientras la **IP** indica a qué equipo llegar, el **puerto** indica a qué **aplicación** entregar la información.

**80 / 443:** Tráfico web (**HTTP / HTTPS**).

**22:** Acceso remoto seguro (**SSH**).

**5432 / 3306:** **Bases de datos** (**PostgreSQL / MySQL**).

**3000:** Puerto común para desarrollo local (**Node.js / React**).

## 🛠️ Protocolos de Aplicación y Desarrollo
**HTTP** y **HTTPS**

**HTTP:** Reglas para el intercambio de mensajes entre **cliente** y **servidor**.

**HTTPS:** Versión segura que utiliza cifrado **TLS/SSL** para proteger **datos sensibles**.

### **Conceptos de API**
**REST:** Estilo de arquitectura para diseñar **APIs** utilizando métodos **HTTP** (**GET, POST, PUT, DELETE**).

**Endpoint:** **URL** específica que representa un **recurso** o acción dentro de una **API**.

## **🚨 Debugging:** Errores Comunes de Conexión
Identificar el error es el primer paso para resolverlo:

**Port already in use:** Otro **proceso** está ocupando el **puerto** solicitado.

**Connection refused:** El **servidor** no está activo o escuchando en el **puerto** indicado.

**Timeout:** El **servidor** tarda demasiado en responder; puede ser un problema de **red** o de carga.

## **🍕 Analogía del Restaurante**
Para comprender estos conceptos técnicos, podemos visualizarlos en un entorno cotidiano:

**TCP:** Es como pedir con un mesero que confirma cada plato antes de traerlo.

**UDP:** Es como gritar el pedido directo a la cocina; es rápido, pero nadie confirma si se escuchó bien.

**Puerto:** Es el número de mesa que indica exactamente dónde debe llegar el servicio.

**HTTP:** Son las reglas de cortesía y el menú que definen cómo se pide y se sirve la comida.

## **🧠 Conceptos Avanzados**
El proyecto también aborda la importancia de la **seguridad** mediante **TLS/SSL**, la estructura de las peticiones mediante **fetch()** en el **frontend** y la gestión de respuestas en formato **JSON**.

Desarrollado para el fortalecimiento de habilidades técnicas en **infraestructura** y desarrollo por ***Manuel Labrador***.
