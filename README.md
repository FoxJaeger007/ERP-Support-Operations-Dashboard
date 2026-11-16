# ERP Support Operations Dashboard

## Descripción del Proyecto

Proyecto de análisis de datos y Business Intelligence enfocado en la gestión de incidentes de soporte ERP. El objetivo principal es evaluar el desempeño operativo, el cumplimiento de los acuerdos de nivel de servicio (SLA) y la eficiencia de los procesos de atención mediante técnicas de análisis exploratorio de datos (EDA) en Python y visualización interactiva en Power BI.

---

## Objetivos

- Analizar el ciclo de vida de los incidentes.
- Evaluar el cumplimiento de los SLA.
- Identificar patrones de reapertura y reasignación.
- Analizar la distribución de impacto, urgencia y prioridad.
- Construir un dashboard ejecutivo para el seguimiento de indicadores operativos.

---

## Dataset

**Incident Management Process Enriched Event Log**

Características principales:

- 141.712 registros de eventos.
- 24.918 incidentes únicos.
- 36 variables originales.
- Ventana de análisis centrada en los trimestres completos de 2016 (Q2-Q4).

---

## Herramientas Utilizadas

### Análisis de Datos

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

### Inteligencia de Negocio

- Power BI

### Documentación

- Jupyter Notebook
- Microsoft Excel

---

## Principales Hallazgos

### Reapertura de incidentes

Solo el 0,9 % de los incidentes requirió al menos una reapertura durante el período analizado.

### Reasignación de incidentes

El 39,76 % de los incidentes fue reasignado al menos una vez, evidenciando que la transferencia de casos forma parte importante del flujo operativo.

### Complejidad operativa

Cada incidente registró, en promedio, 4,89 actualizaciones durante su ciclo observado.

### Cumplimiento de SLA

El cumplimiento de los acuerdos de nivel de servicio se mantuvo por encima del 95 % durante el período evaluado.

### Perfil de incidentes

La mayoría de los incidentes se concentró en niveles medios de impacto, urgencia y prioridad.

### Concentración temporal

La creación de nuevos incidentes se concentró principalmente durante el segundo trimestre de 2016, comportamiento observado en la fuente de datos original.

---

## Dashboard Power BI

El dashboard fue diseñado en tres niveles de análisis:

### Página 1: Resumen Ejecutivo

- Total de incidentes.
- Cumplimiento SLA.
- Reaperturas.
- Reasignaciones.
- Complejidad operativa.
- Tendencias temporales.

### Página 2: Perfil de Incidentes

- Prioridad.
- Impacto.
- Urgencia.
- Relación impacto-urgencia.
- Cumplimiento SLA por prioridad.

### Página 3: Gestión Operativa

- Analistas con mayor volumen de casos resueltos.
- Categorías con mayor demanda.
- Reasignaciones.
- Reaperturas.

---

## Estructura del Proyecto

```text
Data/
├── Raw/
└── Processed/

Images/

Notebooks/

Power BI/

SQL/
```

---

## Autor

Andrés Elías Arias Varón

Proyecto desarrollado como parte del portafolio profesional de Analítica de Datos y Business Intelligence.