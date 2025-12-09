# Proyecto-Final-Grupo-C - Ecovida

# Nombre del Equipo
**Ecovida**

# Slogan
**“Tu acción importa, nuestro futuro también”**

# ODS Objetivo
**ODS 6 - Agua limpia y saneamiento**

# Informacion del Equipo

| Rol | Nombre | GitHub | Responsabilidades |
|---|---|---|---|
| Gestor de logistica | Ammi Cristina | Cristi08 | Preparacion de datos, Documentacion |
| Investigador | Ammi Elizabeth | AEliza160 | Recoleccion de datos, Visualizaciones Iniciales |
| Ivestigador | Irismar | robledoirismar230-stack | Recoleccion de datos, Funcionalidades Esenciales |
| Desarrollo de prototipo | Saret |  ct24-saretmedina | Arquitectura de la Solución, Enfoque en el Impacto |
| Analisis de Datos | Ostin | opatino2318 | Desarrollo del Dashboard/Aplicación |
| Investigador | Joshua | @usuario | Aportes teóricos, Investigacion |

# Problematica

# Qué problema estamos resolviendo?

Panama produce grandes cantidades de agua potable, por en todas las provincias del pais se registran casos de enfermedades hidroalimentarias.

Esto indica que algo sucede entre la prouccion, la distribucion y la calidad del agua que llega a los hogares.

Las posibles causas son:

- Fugas en las tuberias
- Redes antiguas que no reciben mantenimiento
- Contaminacion por filtraciones desde el suelo
- Perdida de presion en las tuberias

Aunque hay agua, no siempre llega limpia ni segura a las personas

# Por qué es importante?

Porque el agua es algo básico que todas las personas usan todos los días.
Cuando la red que distribuye el agua no funciona bien:

- Entra suciedad o contaminación
- Aparecen bacterias
- Aumentan enfermedades como diarrea y gastroenteritis

Esto afecta tanto a la salud de la población como al sistema de salud, que tiene que tratar más casos.

# A quién afecta?

Este problema puede afectar a cualquier persona, pero especificamente a:

- Familias que dependen del agua de grifo
- Provincias rurales y comarcas
- Niñoos y adultos mayores

# Alcance del Proyecto

- **Lugar**: Panama todas las provincias y comarcas
- **Años**: 2018 a 2022
- **Tema**: Produccion de agua, consumo y enfermedades

# Datos Utilizados

| Conjunto de datos | Fuente | Descripción | Período |
|---|---|---|---|
| Producción de agua potable | IDAAN | Cantidad de agua producida por provincia y año | 2018–2022 |
| Consumo de agua potable | IDAAN | Consumo total por provincia | 2018–2022 |
| Enfermedades hidroalimentarias | INEC | Casos reportados por provincia | 2018–2022 |

# Tecnologías utilizadas

- Python
- Pandas
- Streamlit
- Plotly
- GitHub

# Principales Hallazgos

# Insight 1: Se produce más agua de la que se consume
En casi todas las provincias, la producción es mayor que el consumo.
Esto puede significar que se pierde mucha agua antes de llegar a las casas, probablemente por fugas.

# Insight 2: Las enfermedades siguen presentes
Aunque hay agua, se siguen registrando casos de enfermedades.
Esto nos hace pensar que el problema no es la cantidad, sino cómo llega el agua.

# Insight 3: Algunas provincias tienen más riesgo
Las zonas rurales y comarcas pueden tener:

- Tuberias más viejas
- Poca inversión o mantenimiento
- Menos acceso a plantas de tratamiento
  
Esto las hace más vulnerables.

# Recomendaciones

1. Revisar la infraestructura
- Identificar fugas, tuberías viejas o rotas
2. Mejorar el mantenimiento
- Cambiar tramos dañados y dar mantenimiento frecuente
3. Monitorear la calidad del agua
- Hacer pruebas regulares, especialmente en provincias rurales

# Proximos Pasos

- Comparar provincia por provincia
- Ver dónde hay más pérdidas de agua
- Diseñar soluciones prioritarias según los hallazgos

# Impacto Esperado

- Más de 4 millones de personas beneficiadas
- Menos casos de enfermedades transmitidas por el agua
- Mejores servicios para toda la población

La meta es contribuir a:

- ODS 6: Agua limpia
- ODS 3: Salud y bienestar

# Arquitectura del Proyecto

```text

└── flujo-datos/
    ├── 01-obtencion/                          # Obtención de datos (.csv)
    │       ├── datos_agua.csv                 
    │       ├── hidroalinentarias.csv          
    │       └── consumo.csv                    
    │                                           # Herramienta: pandas.read_csv()
    │
    ├── 02-limpieza/                           # Limpieza de datos
    │       └── limpieza.py                    # Herramientas: Pandas (drop, rename, astype, split)
    │                                           # Acciones: eliminar columnas, corregir tipos, separar textos, manejar nulos
    │
    ├── 03-integracion/                        # Integración / Unión de datasets
    │       └── merge.py                       # Herramienta: Pandas (merge)
    │                                           # Acción: unir producción + enfermedades por país
    │
    ├── 04-transformacion/                     # Transformación de datos
    │       └── transform.py                   # Herramientas: Pandas + NumPy
    │                                           # Acciones: groupby, sum, mean, ordenar, convertir fechas
    │
    ├── 05-visualizacion/                      # Visualización de resultados
    │       └── graficos.py                    # Herramientas: Matplotlib + Seaborn
    │                                           # Gráficos: líneas, comparativos, countplot
    │
    └── 06-resultados/                         # Resultados finales
            ├── dataset_limpio.csv             # Dataset procesado
            └── visualizaciones/               # Imágenes generadas

```

# Agradecimientos

- Tech Horizons
- IDAAN e INEC
- Comunidad open source

# Contacto
Preguntas? Nos puedes contactar!
Correo del equipo: proyect.ecovida@gmail.com

**Gracias por leer nuestro proyecto**
Realizado por el equipo de Ecovida


# Instalación y Ejecución

git clone [https://github.com/Cristi108/Proyecto-Final-Grupo-C]
cd [Proyecto Final Grupo C]

# Instala las Dependencias

pip install -r requirements.txt

# Ejecuta el Dashboard

streamlit run src/dashboard.py

Abre en tu Navegador:
El tablero se abre automáticamente enhttp://localhost:8501

# Enlaces importantes

- Dashboard en vivo: [URL si está desplegado]
- Conjuntos de datos utilizados: [Enlaces a las fuentes]
- Presentación: [Enlace a diapositivas]
- Demostración en vídeo: [Enlace si tienes vídeo]
