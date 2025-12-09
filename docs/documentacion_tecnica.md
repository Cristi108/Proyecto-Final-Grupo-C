# DOCUMENTACIÓN TÉCNICA 

### **1. Nombre del Proyecto**

**Ecovida – Monitoreo de Producción, Consumo y Enfermedades Hidroalimentarias**
---
### **2. Descripción General**

Este proyecto analiza tres conjuntos de datos relacionados con el agua en Panamá para el periodo 2018–2022.
Los datos utilizados fueron:

• Producción de agua potable

• Consumo de agua potable por tipo de usuario

• Casos de enfermedades hidroalimentarias

El objetivo es comprender cómo la producción y el consumo de agua se relacionan con la aparición de enfermedades, y presentar la información de manera clara mediante un dashboard interactivo.

---
### **3. Metodología**

**El proyecto se desarrolló en tres fases:**

 **Fase 1 – Planificación**

• Selección del ODS: ODS 6 – Agua limpia y saneamiento

**Definición de la problemática:**
Relación entre disponibilidad de agua potable y enfermedades hidroalimentarias

Asignación de roles y responsabilidades

Búsqueda de fuentes de datos

**Fase 2 – Procesamiento y análisis de datos**

• Carga de los tres archivos CSV

• Exploración inicial

• Limpieza básica de datos

• Análisis estadístico y visualización

**Fase 3 – Implementación**

•Creación de dashboard básico

• Funcionalidades de filtrado por año y provincia

• Generación de métricas y visualizaciones

---
### **4. Arquitectura de la Solución**

Los datos pasan por el siguiente proceso técnico:

Entrada de Datos

**Se utilizan tres archivos CSV:**

• produccion_agua.csv

• consumo_agua.csv

• enfermedades_hidroalimentarias.csv

• Procesamiento de Datos


**Se realizaron los siguientes pasos:**

• Lectura con pandas

• Conversión de columnas de año a formato numérico

• Agrupaciones por provincia y año

• Suma total de casos por enfermedad

• Merge entre producción, consumo y salud

• Análisis


**Se aplicaron:**

• Estadísticas descriptivas

• Cálculo de promedios y tendencias

• Visualización temporal

• Visualizaciones

### **Se generaron gráficos con:**

• matplotlib

• seaborn

• plotly

• Dashboard

Una aplicación interactiva permite:

• Filtrar por año

• Comparar producción vs consumo

• Analizar casos de enfermedades

• Ver recomendaciones finales

---
### **5. Visualizaciones Realizadas**

Se generaron gráficos para apoyar la toma de decisiones.
Los principales fueron:

• Producción de agua potable por provincia (2018–2022)

• Gráfico de barras

• Consumo de agua potable por tipo de usuario (2018–2022)

• Gráfico de barras

• Casos totales de enfermedades hidroalimentarias por provincia y año

• Línea temporal (lineplot)

• Evolución de Casos de Enfermedades Hidroalimentarias por Provincia (2018–2022)

• Gráfico de barras

• Comparación de casos por enfermedad cada año

• Gráfico de barras

• Comparación Producción vs Consumo de Agua por Tipo de Usuario

• Gráfico de barras

• Producción de agua vs Casos de Enfermedades (2018–2022)

• Gráfico de barras comparativas

Estas visualizaciones se integraron en el dashboard y también se utilizaron para la presentación y análisis.

---
### **6. Dashboard**

La aplicación fue desarrollada con Streamlit

Permite seleccionar:

• Provincia

• Año

• Tipo de usuario

• Muestra métricas:

• Total de producción

• Total de consumo

• Casos totales por enfermedad

Las capturas del dashboard se incluyen dentro de:

assets/screenshots/

---
### **7. Documentación de Reuniones**

Se creó un documento adicional que registra:

• Fechas de reuniones

• Temas discutidos

• Responsables

• Cambios de asignación

• Avances de las fases

Este documento se sube a:

docs/reuniones.md

---
### **8. Estructura del Repositorio**

Esto es lo que sube al GitHub:

```
proyecto-final/
|
├── data/
│   ├── produccion_agua.csv
│   ├── consumo_agua.csv
│   └── enfermedades_hidroalimentarias.csv
|
├── notebooks/
│   └── fase2_analisis.ipynb
|
├── app/
│   ├── app.py
│   └── utils.py
|
├── docs/
│   ├── documentacion_tecnica.md
│   └── reuniones.md
|
├── assets/
│   ├── images/
│   └── screenshots/
|
├── requirements.txt
└── README.md
```

---
### **9. Observaciones Finales**

• Se cumplieron los lineamientos del proyecto

• El análisis es coherente con el ODS 6

• Se incluyen recomendaciones y conclusiones basadas en datos

• El repositorio está organizado y documentado
