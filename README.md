
![image](https://github.com/user-attachments/assets/e56445ea-deea-4304-b681-def7d8489249)
# Análisis de Accidentes Viales en Vías Controladas por el INVIAS (Colombia)

Este proyecto tiene como objetivo analizar la accidentalidad vial en Colombia en las vías controladas por el Instituto Nacional de Vías (INVIAS), utilizando Python y Power BI. Se realiza una exploración de los datos históricos (2022– 2024 ) para propósitos de análisis y visualización.

## 📌 Introducción

El Instituto Nacional de Vías (INVIAS) es la entidad encargada de la infraestructura vial en Colombia. Este análisis busca comprender los patrones y causas de los accidentes, identificar regiones críticas y proponer recomendaciones para mejorar la seguridad vial.

## 🎯 Objetivos del análisis

- Analizar tendencias de accidentalidad a lo largo del tiempo.
- Identificar causas frecuentes de accidentes.
- Detectar regiones geográficas con mayor número de incidentes.
- Evaluar la gravedad de los accidentes en términos de víctimas y heridos.

## 🔍 Dataset

- **Original**: Accidentalidad Vial 2022 -  2024 (Fuente: INVIAS, Datos Abiertos Colombia)

| Campo              | Descripción                                      |
|--------------------|--------------------------------------------------|
| AÑO                | Año del accidente                                |
| FECHA_ACC          | Fecha exacta del accidente                       |
| DIA_SEMANA_ACC     | Día de la semana en que ocurrió el accidente     |
| DEPARTAMENTO       | Departamento donde ocurrió el accidente          |
| CONDIC_METEOR      | Condición meteorológica                          |
| ESTADO_SUPER       | Estado de la superficie de la vía                |
| TERRENO            | Tipo de terreno                                  |
| GEOMETRIA_ACC      | Geometría de la vía (Curva, Recta)               |
| N_HERIDOS          | Número de heridos                                |
| N_MUERTOS          | Número de muertos                                |
| N_VICTIMAS         | Total de víctimas (heridos + muertos)            |
| CLASE_ACCIDENTE    | Tipo de accidente (Colisión, Volcamiento, etc.)  |
| CAUSA_POSIBLE      | Causa probable del accidente                     |

## 🧪 Proceso de ETL

- Limpieza de nombres de municipios.
- Corrección de fechas fuera de rango.
- Homogeneización de valores en campos categóricos.

## 📈 Análisis Estadístico

Se realiza análisis descriptivo de heridos, muertos y víctimas por accidente, además de visualizaciones por región, tiempo y causa usando Power BI.

## 📊 Visualización (Power BI)

![image](https://github.com/user-attachments/assets/2ed585ef-e0c8-4a05-8150-71b540ddf21f)

https://app.powerbi.com/groups/c9b8e1e3-c82b-457d-9d83-f5e7b264720a/reports/f6dac31b-2876-48c8-8008-e70593a99e16?ctid=899789dc-202f-44b4-8472-a6d40f9eb440&pbi_source=linkShare

Se incluye un dashboard interactivo con:
- Accidentes por año y departamento.
- Causas y tipos de accidentes más frecuentes.
- Condiciones climáticas y geométricas asociadas.
- Evolución en la gravedad de los accidentes.

## 📁 Archivos

- `Accidentalidad_Vial_2022_-_2024.csv` – Datos reales.
- `dashboard.pbix` – Panel de Power BI.
- `notebook_analisis.ipynb` – Análisis exploratorio en Python.

## 🧠 Conclusiones

- La mayoría de los accidentes se concentran en Antioquia, Boyacá y Córdoba.
- Las causas más frecuentes son exceso de velocidad y falta de distancia.
- El número de víctimas ha disminuido progresivamente desde 2022.
- Los accidentes se presentan más en curvas y bajo lluvia.

## 🚀 Recomendaciones

- Fortalecer programas de educación vial.
- Mejorar infraestructura en tramos peligrosos.
- Implementar medidas en zonas montañosas y de clima adverso.
- Reforzar vigilancia en puntos críticos.

---

**Autor:** Geraldin Carriazo  

