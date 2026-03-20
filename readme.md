# Observatorio Abierto de Biodiversidad y Estrés Ambiental Urbano – León BioLab

[![License: AGPL v3](https://img.shields.io/badge/Código-AGPL%20v3-blue.svg)](LICENSE_CODE)
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/Datos-CC%20BY--NC--SA%204.0-lightgrey.svg)](LICENSE_DATA)
[![License: CERN OHL v2](https://img.shields.io/badge/Hardware-CERN%20OHL%20v2-green.svg)](LICENSE_HARDWARE)
[![Status](https://img.shields.io/badge/Estado-Fase%201-yellow.svg)]()
[![City](https://img.shields.io/badge/Ciudad-León%2C%20Guanajuato-orange.svg)]()

---

## 📖 Sobre el Proyecto

**León BioLab** es una iniciativa de ciencia abierta que desarrolla un observatorio ambiental urbano accesible y replicable. El proyecto combina estaciones de monitoreo de bajo costo, datos satelitales abiertos y técnicas de inteligencia artificial para generar datos públicos sobre calidad del aire, microclima urbano y salud de la vegetación.

Este repositorio contiene todos los elementos necesarios para que cualquier colectivo, escuela o comunidad pueda construir su propio observatorio ambiental: desde los planos de las estaciones hasta el código de la plataforma de datos.

### 🌎 ¿Por qué existe León BioLab?

Actualmente, muchas ciudades intermedias como León, Guanajuato, no cuentan con redes de monitoreo ambiental de acceso abierto. No existen APIs públicas que permitan consultar datos en tiempo real sobre calidad del aire, temperatura o humedad en distintas zonas. Esta falta de información limita:
- La investigación científica local
- La educación ambiental basada en evidencia
- La participación ciudadana en temas ecológicos
- La toma de decisiones informadas sobre planeación urbana

León BioLab nace para llenar ese vacío, creando un modelo replicable de infraestructura abierta de datos ambientales.

### Objetivos del Proyecto

**General**
> Desarrollar un observatorio ambiental urbano basado en tecnologías abiertas que permita monitorear y analizar variables ambientales y ecológicas mediante sensores, imágenes y datos satelitales.

**Específicos**
- Diseñar e implementar estaciones de monitoreo ambiental con sensores de bajo costo y componentes de fácil adquisición
- Implementar sistemas de captura de imágenes para análisis longitudinal de vegetación urbana
- Integrar datos satelitales (NASA, ESA, Copernicus) con datos locales en una plataforma unificada
- Aplicar técnicas de inteligencia artificial para estudiar patrones ambientales y estrés vegetal
- Generar un repositorio de datos abiertos para investigación, educación y réplica del proyecto

---

## Equipo fundador

## Arquitectura del Sistema

## Estructura del repositorio

```code
Bio-lab/
│
├── README.md # Readme del proyecto
├── LICENSE_CODE # GNU AGPL-3.0
├── LICENSE_DATA # CC BY-NC-SA 4.0
├── LICENSE_HARDWARE # CERN OHL v2 Strong
│
├── home_page/ # Página de información del proyceto
|
├── docs/ # Documentación técnica
│ ├── guia_contribucion.md # Guía paara contribuir al proyecto
│ ├── fase1_diseno/
│ │ ├── variables_ambientales.md # Variables definidas
│ │ ├── hipotesis_cientificas.md # Hipótesis iniciales
│ │ └── arquitectura_general.md # Diagramas y flujos
│ └── manuales/
│ └── manual_estacion_a.md # Cómo construir una estación
│
├── hardware/ # Diseños para replicar
│ ├── estacion_tipo_a/
│ │ ├── schematics/ # Esquemáticos PDF
│ │ ├── pcb/ # Archivos Gerber
│ │ ├── bill_of_materials.csv # Lista de componentes
│ │ └── enclosure/ # Archivos STL para impresión 3D
│ └── firmware/
│ └── esp32_base/
│ ├── main.ino # Código principal
│ ├── config.h # Configuración de sensores
│ └── libraries/ # Librerías necesarias
│
├── backend/ # API y servicios
│
├── ai/ # Modelos de IA (futuras fases)
|
├── frontend/ # Plataforma de visualización de datos (futuras fases)
|
├── scripts/ # Utilidades
│ └── simulate_stations.py # Simulación de datos para pruebas
│
└── tests/
└── test_hardware.py
```

## API Pública

## Instrucciones para replicar

## Dataset

## Variables Ambientales Monitoreadas

## Estado del Proyecto
| Fase  | Periodo | Estado |
|--------------|--------------|--------------|
| Fase 1: Diseño del sistema  | Abril - Mayo 2026 | En curso|


## Cómo contribuir 🤝
Si deseas replicar, adaptar o mejorar este proyecto:

- Fork este repositorio
- Construye una estación siguiendo los manuales
- Reporta problemas o sugerencias en Issues
- Comparte tus datos y experiencias

Consulta la Guía de Contribución para más detalles.

## 📬 Contacto
Colectivo: Singularity

Representante: José Javier Gutiérrez Ramírez

Correo: replacedspace17@singularitymx.org

GitHub: github.com/ReplacedSpace17

