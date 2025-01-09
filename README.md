![PackTracer Badge](https://img.shields.io/badge/PackTracer-Cisco-blue?logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxMjAiIGhlaWdodD0iNDAiIHZpZXdCb3g9IjAgMCAxMjAgNDAiIHhtbDpzcGFjZT0icHJlc2VydmUiPgogPHBhdGggZD0iTTAgMGgxMjB2NDBIMHoiIGZpbGw9Im5vbmUiLz4KIDxwYXRoIGQ9Ik0zMy41IDBhOC4xNSA4LjE1IDAgMDE4LjE1IDguMTUgOCA4IDAgMDEtOC4xNSA4LjE1QTggOCAwIDAxMjUuMzUgMGE4LjE1IDguMTUgMCAwMS44MTUgOC4xNUE4IDggMCAwMS4wNSA4LjE1QTggOCAwIDAxOC4xNSAwYTguMTUgOC4xNSAwIDAxOC4xNSA4LjE1QTggOCAwIDAxMzMuNSAwem04MCAwYTguMTUgOC4xNSAwIDAxOC4xNSA4LjE1QTggOCAwIDAxMTEwLjM1IDBhOC4xNSA4LjE1IDAgMDEuODE1IDguMTVBOCA4IDAgMDEwLjA1IDguMTVBIDggOCAwIDAxODEuNSAwYTguMTUgOC4xNSAwIDAxOC4xNSA4LjE1QTggOCAwIDAxMTEuNSAwem0tNjAgMGE4LjE1IDguMTUgMCAwMTguMTUgOC4xNUE4IDggMCAwMTM5LjM1IDBhOC4xNSA4LjE1IDAgMDEuODE1IDguMTVBOCA4IDAgMDEyLjA1IDguMTVBIDggOCAwIDAxMTQuNSAwYTguMTUgOC4xNSAwIDAxOC4xNSA4LjE1QTggOCAwIDAxNTQuNSAwWiIgZmlsbD0iIzAwYjhiNSIvPgo8L3N2Zz4=)


# Universidad Politécnica de Francisco I. Madero

## Programa Educativo:
**Ingeniería en Sistemas Computacionales**

---

### Nombre de la Asignatura:
**Interconexión de Redes**

>.[!NOTE].
>Esta documetacion es solo para registro de mi actividad.
---

### Trabajo:
**Práctica IoT**

> .[!IMPORTANT].
> La archivo es solo para usos practicos por favor no te lo piratees.

---

### Nombre del Docente:
**Lic. Alicia León Martínez**

---

### Nombre del Alumno:
**Ronaldo Moctezuma Cabañas**

**Matrícula:** 2117031343  
**Grupo:** 6SCG1  
**Fecha:** Martes 25 de julio del 2023  

---

## Introducción al Mundo IoT


Durante el curso de introducción a las IoT (Internet of Things), abordamos entornos y aplicaciones de IoT. En esta práctica, emulamos un entorno “realista” utilizando herramientas de Cisco. Configuramos dispositivos IoT para conectarse y ser gestionados mediante sensores, controladores y actuadores.

![Implemenacion DHCP](/Cisco/assets/dhcp.png")

---

## Configuración de Red

- **Protocolo DHCP:** Configurado para repartir 252 IP útiles automáticamente.
- **Conexión:** El servidor está conectado a un switch 2960 como puente hacia el router inalámbrico.
- **Red inalámbrica:** Configuración de un AP en 2.4 GHz, con seguridad WPA2 Personal.

---

## Gestión de Dispositivos IoT

1. **Conexión de dispositivos:** Configuración para permitir la conexión de dispositivos IoT al servidor.
    ![Configuracion IoT -> Server](/Cisco/assets/IoTconfig.png")
2. **Gestión remota:** Configuración de usuario y contraseña para administración remota desde el navegador.
   ![Password y SSID](/Cisco/assets/pass-name.png")

3. **Visualizacion via ip:192.168.0.2**
   ![Visualizacion via web](/Cisco/assets/view-ip.png")
---

## Topología de la Casa Inteligente

### Sistemas Implementados:
1. **Sistemas para incendios:**
   - Detección de fuego y activación de extintores y alarmas.
   ![Sistema para incendios](/Cisco/assets/Sis-incendio.png")

2. **Sistema de RFID:**
   - Identificación por tarjeta para abrir puertas y garaje.
   ![Puerta con tarjeta](/Cisco/assets/automatic-door.png")

3. **Sistema de alarma y detección de movimiento:**
   - Activación de cámaras y alarmas en caso de intrusión.
    ![Garage automatico](/Cisco/assets/auto-garage.png")
---

## Conclusión
La práctica permitió aplicar conocimientos de Python en dispositivos IoT y entornos simulados, proporcionando una experiencia enriquecedora.

---

