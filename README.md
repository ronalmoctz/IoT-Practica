![PackTracer Badge](https://img.shields.io/badge/PackTracer-Cisco-blue?logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxMjAiIGhlaWdodD0iNDAiIHZpZXdCb3g9IjAgMCAxMjAgNDAiIHhtbDpzcGFjZT0icHJlc2VydmUiPgogPHBhdGggZD0iTTAgMGgxMjB2NDBIMHoiIGZpbGw9Im5vbmUiLz4KIDxwYXRoIGQ9Ik0zMy41IDBhOC4xNSA4LjE1IDAgMDE4LjE1IDguMTUgOCA4IDAgMDEtOC4xNSA4LjE1QTggOCAwIDAxMjUuMzUgMGE4LjE1IDguMTUgMCAwMS44MTUgOC4xNUE4IDggMCAwMS4wNSA4LjE1QTggOCAwIDAxOC4xNSAwYTguMTUgOC4xNSAwIDAxOC4xNSA4LjE1QTggOCAwIDAxMzMuNSAwem04MCAwYTguMTUgOC4xNSAwIDAxOC4xNSA4LjE1QTggOCAwIDAxMTEwLjM1IDBhOC4xNSA4LjE1IDAgMDEuODE1IDguMTVBOCA4IDAgMDEwLjA1IDguMTVBIDggOCAwIDAxODEuNSAwYTguMTUgOC4xNSAwIDAxOC4xNSA4LjE1QTggOCAwIDAxMTEuNSAwem0tNjAgMGE4LjE1IDguMTUgMCAwMTguMTUgOC4xNUE4IDggMCAwMTM5LjM1IDBhOC4xNSA4LjE1IDAgMDEuODE1IDguMTVBOCA4IDAgMDEyLjA1IDguMTVBIDggOCAwIDAxMTQuNSAwYTguMTUgOC4xNSAwIDAxOC4xNSA4LjE1QTggOCAwIDAxNTQuNSAwWiIgZmlsbD0iIzAwYjhiNSIvPgo8L3N2Zz4=)


# Universidad Politécnica de Francisco I. Madero

## Programa Educativo:
**Ingeniería en Sistemas Computacionales**

---

### Nombre de la Asignatura:
**Interconexión de Redes**

>[!NOTE]
>Esta documetacion es solo para registro de mi actividad.
---

### Trabajo:
**Práctica IoT**

> [!IMPORTANT]
> El archivo es solo para usos practicos por favor no te lo piratees.

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

![DHCP](https://www.dropbox.com/scl/fi/iym2o64sj1rwvei9npzr1/dhcp.png?rlkey=8d65agmijg0ho4ndzqd5pk0v2&st=ve2m0um6&raw=1)


---

## Configuración de Red

- **Protocolo DHCP:** Configurado para repartir 252 IP útiles automáticamente.
- **Conexión:** El servidor está conectado a un switch 2960 como puente hacia el router inalámbrico.
- **Red inalámbrica:** Configuración de un AP en 2.4 GHz, con seguridad WPA2 Personal.

---

## Gestión de Dispositivos IoT

1. **Conexión de dispositivos:** Configuración para permitir la conexión de dispositivos IoT al servidor.
    ![IoT Configuration](https://www.dropbox.com/scl/fi/vl8emnn9ba5j0z5s0anzh/IoTconfig.png?rlkey=sjc1u0sjudzqbs0uf7yox63s0&st=7xxqes30&raw=1)

2. **Gestión remota:** Configuración de usuario y contraseña para administración remota desde el navegador.
   ![Pass and Name](https://www.dropbox.com/scl/fi/h1h61nr0dxks2l62jwc3a/pass-name.png?rlkey=kbshj5j94s5y7gdgjp2yuxy9q&st=b4jokxiw&raw=1)


3. **Visualizacion via ip:192.168.0.2**
 
   ![View IP](https://www.dropbox.com/scl/fi/bx6iurjnku020l3k20t2h/view-ip.png?rlkey=5b00ak1gyh0anaj3vh8y9gnvg&st=lqca9fn5&raw=1)

---

## Topología de la Casa Inteligente

### Sistemas Implementados:
1. **Sistemas para incendios:**
   - Detección de fuego y activación de extintores y alarmas.
   ![Sistema de Incendio](https://www.dropbox.com/scl/fi/919fh5tdhv9uyii1h2cgc/Sis-incendio.png?rlkey=iyysss9ozyi2mt6b7y875q3jx&st=dd0wr24t&raw=1)


2. **Sistema de RFID:**
   - Identificación por tarjeta para abrir puertas y garaje.
     
       ![Automatic Door](https://www.dropbox.com/scl/fi/hnub9u6bxgaysdz8l0v9r/automatic-door.png?rlkey=2k71x38be2suhytu8zp181st9&st=vr0a5x28&raw=1)


3. **Sistema de alarma y detección de movimiento:**
   - Activación de cámaras y alarmas en caso de intrusión.
    ![Auto Garage](https://www.dropbox.com/scl/fi/5sbnu8m5wo23uajznfy68/auto-garage.png?rlkey=51j415g5mgjzut312ebn8lqf8&st=rgp5ekqo&raw=1)

---

## Conclusión
La práctica permitió aplicar conocimientos de Python y JavaScript en dispositivos IoT con arduino y entornos simulados, proporcionando una experiencia enriquecedora.
> [!CAUTION]
> Cuidado al modificar lo valores de algunos dispositivos puede desconfigurar la simulacion
---

