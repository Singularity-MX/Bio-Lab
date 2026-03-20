leon-biolab/
│
├── README.md                          # Presentación principal del proyecto
├── LICENSE_CODE                       # GNU AGPL-3.0
├── LICENSE_DATA                       # CC BY-NC 4.0
├── LICENSE_HARDWARE                   # CERN OHL v2 Strong
├── .gitignore
├── requirements.txt                   # Dependencias de Python
├── docker-compose.yml                 # Orquestación de servicios
│
├── docs/                              # Documentación general
│   ├── fase1_diseno/
│   │   ├── variables_ambientales.md
│   │   ├── hipotesis_cientificas.md
│   │   ├── arquitectura_general.md
│   │   └── plan_piloto_sitios.md
│   ├── manuales/
│   │   ├── manual_instalacion_estacion.md
│   │   ├── manual_usuario_dashboard.md
│   │   └── guia_contribucion.md
│   └── presentaciones/
│       └── intro_leon_biolab.pdf
│
├── hardware/                          # Planos y diseño de estaciones
│   ├── estacion_tipo_a/
│   │   ├── schematics/
│   │   │   └── estacion_a_schematic.pdf
│   │   ├── pcb/
│   │   │   └── estacion_a_gerber.zip
│   │   ├── bill_of_materials.csv
│   │   └── enclosure/
│   │       └── estacion_a_caja.stl
│   ├── estacion_tipo_b/
│   │   ├── schematics/
│   │   ├── pcb/
│   │   └── bill_of_materials.csv
│   └── firmware/
│       ├── esp32_base/
│       │   ├── main.ino
│       │   ├── config.h
│       │   └── libraries/
│       └── camara_rpi/
│           └── capture.py
│
├── backend/                           # API y servicios
│   ├── api/
│   │   ├── main.py                    # FastAPI/Flask principal
│   │   ├── routes/
│   │   │   ├── telemetry.py           # POST /api/v1/telemetry
│   │   │   ├── stations.py            # GET /api/v1/stations
│   │   │   ├── measurements.py        # GET /api/v1/measurements
│   │   │   └── images.py              # GET /api/v1/images
│   │   ├── models/
│   │   │   ├── station.py
│   │   │   ├── measurement.py
│   │   │   └── image.py
│   │   ├── database.py                # Conexión a BD
│   │   └── schemas.py                 # Pydantic schemas
│   ├── database/
│   │   ├── init_db.sql
│   │   └── migrations/
│   ├── ingestion/
│   │   ├── satellite_data_fetcher.py
│   │   └── data_validator.py
│   └── requirements.txt
│
├── ai/                                # Modelos de IA
│   ├── models/
│   │   ├── vegetation_analyzer/
│   │   │   ├── model.py
│   │   │   ├── train.py
│   │   │   └── weights/
│   │   └── microclimate_predictor/
│   │       ├── model.py
│   │       └── train.py
│   ├── notebooks/
│   │   ├── exploratory_analysis.ipynb
│   │   └── correlation_study.ipynb
│   └── api/
│       └── inference.py               # Endpoint de IA
│
├── frontend/                          # Dashboard web
│   ├── src/
│   │   ├── components/
│   │   │   ├── Dashboard.jsx
│   │   │   ├── Map.jsx
│   │   │   ├── Charts.jsx
│   │   │   └── StationCard.jsx
│   │   ├── pages/
│   │   │   ├── Home.jsx
│   │   │   ├── DataExplorer.jsx
│   │   │   └── About.jsx
│   │   ├── services/
│   │   │   └── api.js
│   │   └── styles/
│   ├── public/
│   ├── package.json
│   └── README.md
│
├── scripts/                           # Utilidades
│   ├── simulate_stations.py           # Simulación de datos
│   ├── deploy.sh
│   └── backup_db.sh
│
└── tests/
    ├── test_api.py
    └── test_hardware.py