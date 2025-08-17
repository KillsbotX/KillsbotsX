# WRO KillBot X 2025

Bienvenid@ al repositorio del equipo **KillBot X** para la World Robot Olympiad (WRO) 2025. Aquí encontrarás documentación, código fuente, fotos, videos de nuestro robot autonomo.

> **Estado:** en desarrollo iterativo. Si notas alguna inconsistencia entre documentos, por favor abre un *issue*.

---

## Resumen del Proyecto

**KillBot X** es un vehículo autónomo que completa vueltas en un circuito cerrado manteniendo trayectoria estable mediante **giroscopio** y control fino de motores. Emplea visión/computación (cuando corresponde), sensores de distancia y detección de color para evitar paredes/obstáculos y reaccionar a marcadores del reto.

- **Chasis:** LEGO Technic
- **Controlador:** LEGO Mindstorms EV3
- **Sensores clave:** Giroscopio; distancia ultrasónico; color
- **Tren motriz:** diferencial de dos motores

> El objetivo es demostrar que con componentes accesibles se pueden construir sistemas funcionales y bien documentados.

---

## Índice General del Proyecto

1. **[Visión General](/docs/overview.md)** – Componentes principales y fases de operación.
2. **[Hardware y Componentes](/docs/hardware.md)** – Especificaciones electrónicas y mecánicas.  
   - **[Esquema Electromecánico](/schemes/)**  
   - **[Diseño de circuito interactivo](/embeds/index.html)** *(opcional con GitHub Pages)*
3. **[Arquitectura de Software](/docs/software.md)** – Librerías, estructura de carpetas y flujo del código.
4. **[Sensores y Pines](/docs/sensors.md)** – Rol de cada sensor y asignación de pines/puertos.
5. **[Movilidad del Robot](/docs/mobility.md)** – Configuración de motores y giros/curvas.
6. **[Control PID del Giroscopio](/docs/pid.md)** – Calibración e implementación para estabilidad.
7. **[Visión con Cámara](/docs/vision.md)** – Detección y evasión con PixyCam u otra cámara. *(si aplica)*
8. **[Ultrasónico y Filtros](/docs/ultrasonic.md)** – Medición de distancia y filtrado.
9. **[Detección de Color](/docs/color.md)** – Calibración y lógica de uso.
10. **[Modelado 3D y Fabricación](/docs/models.md)** – Modelos STL y parámetros de impresión.
11. **[Manual de Usuario](/docs/user-manual.md)** – Construcción, operación y solución de problemas.

---

## Fotos y Videos

- **Fotos del Equipo:** [/t-photos](/t-photos)
- **Fotos del Vehículo:** [/v-photos](/v-photos)
- **Video Demostrativo:** (https://youtu.be/RNI24cD9cLQ?si=tq7dkKawt0CTLH3k) 

---

## Código Fuente

Todo el código de control y pruebas vive en la carpeta **`/src`**. Sugerimos organizarlo así:

- `[/src]` – programas en EV3 (bloques o MicroPython).  
- [/src](/test)` – códigos de prueba de sensores y motores.  


---

## Diagramas y Gráficas

- **Flujogramas de operación:** en **`/assets`** o **`/docs`**.  
- **Gráficas de calibración:** exporta PNG/SVG y enlaza desde `/docs/pid.md`.

---

## Integrantes del Equipo 🧑‍💻🧑‍🔧

- **Kathiusca Arcia** – Programación y documentación
- **Sofía Barrias** – Electrónica y pruebas
- **Estyfen Adames** – coordinación y control
  
> En **`/t-photos`** encontrarás fotos formales y divertidas del equipo.

---

## Cómo colaborar

Consulta **[CONTRIBUTING.md](CONTRIBUTING.md)** y abre *issues* con plantillas:
- **Reporte de bug**
- **Solicitud de mejora / feature**


---

## Agradecimientos

A la comunidad WRO y a quienes comparten recursos abiertos para aprendizaje en robótica educativa.
