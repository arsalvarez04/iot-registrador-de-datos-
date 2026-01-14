# Interfaz IoT para Monitoreo Meteorológico basada en ESP32 y Bresser 7.1

## Descripción general

Este repositorio contiene el desarrollo del subproyecto correspondiente a la asignatura
**Ingeniería en Automática**, perteneciente a la carrera **Ingeniería Automática**
de la **Universidad Central “Marta Abreu” de Las Villas (UCLV)**.

El subproyecto aborda el diseño e implementación de una **interfaz IoT** para la recepción,
almacenamiento y visualización de datos meteorológicos provenientes de una estación
**Bresser 7.1**, con un ESP32 como nodo de adquisición.

---

## Objetivos del subproyecto

- Implementar un broker MQTT para la recepción de datos de sensores.
- Integrar Node-RED como plataforma de procesamiento y enrutamiento de datos.
- Almacenar datos en una base de datos de series temporales (InfluxDB 3).
- Visualizar la información mediante dashboards interactivos en Grafana.
- Validar la correcta operación de la interfaz IoT mediante pruebas funcionales.

---

## Arquitectura del sistema
MQTT
↓
Mosquitto
↓
Node-RED
↓
InfluxDB 3
↓
Grafana

---

## Tecnologías utilizadas
- **MQTT / Mosquitto**
- **Node-RED**
- **InfluxDB 3**
- **Grafana Enterprise**
- **Sistema local (sin Docker)**

---

## Contenido del repositorio

- `/mqtt` → Instalación y pruebas del broker Mosquitto  
- `/node-red` → Flujos y configuración  
- `/influxdb` → Instalación y esquema de datos  
- `/grafana` → Configuración de visualización  
- `/tests` → Mensajes de prueba e integración  

---

## Autor

**Arturo Santana Álvarez**  
Estudiante de 4to Año – Ingeniería Automática  
Facultad de Ingenierías Eléctricas – UCLV

---

## Licencia

Proyecto académico con fines educativos.


