# financial-data-warehouse-mx
financial-data-warehouse-mx/
├── 01_raw_data/
│   └── seed_raw_financial_data.sql   <-- El script de abajo
├── 02_staging/
│   └── stg_polizas_limpias.sql       <-- Limpieza y estandarización
├── 03_data_marts/
│   ├── dim_cuentas.sql
│   ├── fct_contabilidad_fpa.sql      <-- Modelo para FP&A
│   └── fct_conciliacion_tesoreria.sql <-- Modelo para Tesorería
├── 04_data_quality_tests/
│   └── test_integridad_contable.sql  <-- Reglas de validación (Partida doble, nulos)
├── docs/
│   └── diccionario_metricas.md       <-- Documentación de negocio y KPIs
└── README.md                         <-- Presentación ejecutiva del proyecto
