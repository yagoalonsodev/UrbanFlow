# UrbanFlow

Plataforma de Data Engineering orientada al análisis de datos de transporte urbano.

UrbanFlow es un proyecto desarrollado para explorar y evolucionar una arquitectura de datos completa, desde una implementación local basada en PostgreSQL y Python hasta arquitecturas Lakehouse utilizando Databricks y Microsoft Fabric.

El proyecto se desarrolla en diferentes versiones para demostrar la evolución de la arquitectura, las tecnologías y las prácticas de Data Engineering.

## Arquitectura

```text
                         UrbanFlow
                            │
             ┌──────────────┼──────────────┐
             │              │              │
             ▼              ▼              ▼
        UrbanFlow V1   UrbanFlow V2   UrbanFlow V3
                         Databricks       Fabric
             │              │              │
             ▼              ▼              ▼
        PostgreSQL      Delta Lake       OneLake
        Python          PySpark          PySpark
        Docker          Lakehouse        Fabric Lakehouse
        Airflow         Databricks       Data Factory
                        Medallion         Power BI
```

## Repositorios

| Repositorio | Descripción | Tecnologías principales |
|---|---|---|
| [urbanflow-data-engineerig](https://github.com/yagoalonsodev/urbanflow-v1) | Primera implementación de la plataforma de Data Engineering | Python, PostgreSQL, Docker, Airflow |
| [urbanflow-databricks](https://github.com/yagoalonsodev/urbanflow-databricks) | Evolución de UrbanFlow utilizando una arquitectura Lakehouse con Databricks | Databricks, PySpark, Delta Lake, SQL |
| [urbanflow-fabric](https://github.com/yagoalonsodev/urbanflow-fabric) | Implementación de UrbanFlow sobre Microsoft Fabric | Microsoft Fabric, OneLake, PySpark, SQL, Power BI |

> Los enlaces se actualizarán cuando los repositorios correspondientes estén creados.

## Evolución del proyecto

### V1 — Data Engineering local

La primera versión establece la base del proyecto mediante una arquitectura local de procesamiento y almacenamiento de datos.

Incluye:

- Ingesta y procesamiento de datos
- Python
- SQL
- PostgreSQL
- Docker
- Apache Airflow
- Modelado de datos
- Procesos ETL/ELT

[Ver UrbanFlow V1 →](https://github.com/yagoalonsodev/urbanflow-v1)

---

### V2 — Databricks & Lakehouse

La segunda versión evoluciona la arquitectura hacia un modelo Lakehouse utilizando Databricks.

Principales tecnologías y conceptos:

- Databricks
- Apache Spark
- PySpark
- Delta Lake
- Medallion Architecture
- Bronze / Silver / Gold
- Procesamiento incremental
- Data Quality
- SQL
- Jobs y Workflows

[Ver UrbanFlow Databricks →](https://github.com/yagoalonsodev/urbanflow-databricks)

---

### V3 — Microsoft Fabric

La tercera versión adapta la arquitectura de UrbanFlow al ecosistema Microsoft Fabric.

Principales tecnologías y conceptos:

- Microsoft Fabric
- OneLake
- Fabric Lakehouse
- Data Factory
- PySpark
- SQL
- Medallion Architecture
- Data Quality
- Power BI

[Ver UrbanFlow Fabric →](https://github.com/yagoalonsodev/urbanflow-fabric)

## Objetivos

El proyecto busca demostrar conocimientos prácticos en:

- Data Engineering
- ETL / ELT
- Data Pipelines
- SQL
- Python
- PySpark
- Data Lakes y Lakehouse
- Data Warehousing
- Orquestación
- Data Quality
- Procesamiento incremental
- Cloud Data Platforms
- Analytics

## Stack tecnológico

### Data Engineering

- Python
- SQL
- Apache Spark
- PySpark
- Apache Airflow

### Databases & Storage

- PostgreSQL
- Delta Lake
- OneLake

### Cloud & Data Platforms

- AWS
- Databricks
- Microsoft Fabric

### DevOps

- Docker
- Git
- GitHub Actions

## Autor

**Yago Alonso**

Data Engineer en formación.

[GitHub](https://github.com/yagoalonsodev) · [LinkedIn](https://www.linkedin.com/in/yago-alonso-090372256/)

---

Proyecto personal de aprendizaje y portfolio orientado a Data Engineering.