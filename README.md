# Banking Lakehouse Data Engineering

Proyecto práctico de ingeniería de datos orientado a construir un Lakehouse bancario usando tecnologías modernas.

## Objetivo

Construir una solución de datos de extremo a extremo aplicando:

- Python
- PySpark
- Spark SQL
- Delta Lake
- Arquitectura Medallion
- Google Colab
- Databricks
- AWS
- Git y GitHub

## Arquitectura

El proyecto utilizará una arquitectura por capas:

- **Bronze:** datos originales sin transformar.
- **Silver:** datos limpios, tipificados y validados.
- **Gold:** datos preparados para análisis y consumo de negocio.

## Estructura del proyecto

```text
banking-lakehouse-data-engineering
│
├── data
├── docs
├── notebooks
├── src
├── tests
│
├── .gitignore
├── README.md
└── requirements.txt