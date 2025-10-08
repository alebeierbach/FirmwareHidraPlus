# Firmware Hidra Plus

Proyecto de desarrollo del **firmware personalizado para la impresora 3D “Hidra Plus”**, basado en la arquitectura de **Marlin** y adaptado para funcionar sobre una **placa Arduino Mega 2560 con RAMPS 1.4**.

---

## Objetivo

El propósito de este proyecto es **diseñar, adaptar y optimizar el firmware de control** de la impresora 3D *Hidra Plus*, garantizando un funcionamiento estable, preciso y flexible.  
Se busca aprovechar al máximo las capacidades del hardware mediante la personalización de Marlin, ajustando parámetros de movimiento, gestión térmica y configuración de extrusores.

---

## Tecnologías y componentes principales

- **Firmware base:** [Marlin 2.1.2.4](https://marlinfw.org/)  
- **Microcontrolador:** Arduino Mega 2560  
- **Placa controladora:** RAMPS 1.4  
- **Lenguaje:** C / C++  
- **Entorno de desarrollo:** Arduino IDE / PlatformIO  
- **Mecánica:** Sistema IDEX (doble extrusor independiente)

---

## Descripción técnica

El proyecto contempla la **configuración completa de Marlin** para la impresora *Hidra Plus*, incluyendo:

- Calibración de ejes X, Y, Z y extrusores duales.  
- Control de temperatura mediante termistores NTC y PID tuning.  
- Definición de límites físicos, homing y velocidades máximas seguras.  
- Implementación de **IDEX** para impresión en espejo o duplicado.  
- Ajuste de drivers (A4988 / TMC) y pasos por milímetro.  
- Integración de ventiladores, sensores de fin de filamento y autolevel.  

El firmware se orienta a **maximizar la precisión del movimiento**, la **estabilidad térmica** y la **autonomía operativa** de la impresora.

