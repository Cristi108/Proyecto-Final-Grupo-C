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
| Investigador | Joshua | joshalexhung-stpy | Aportes teóricos, Investigacion |

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

Proyecto Final Grupo C/
│
├── datos/                                   # carpeta con los datos originales del proyecto
│   ├── consumo.csv                          # archivo con datos de consumo y demanda de agua
│   ├── datos_agua.csv                       # archivo con datos de producción de agua por años
│   └── hidroalimentarias.csv                # archivo con los casos registrados por año o región
│
├── cuadernos/                               # análisis y pruebas realizados en google colab
│   ├── Fase_2.ipynb                          # exploración de datos, estadísticas y visualizaciones
│   └── Punto_3_3.ipynb                       # análisis del impacto y discusión de la fase 3
│
├── app/                                     # carpeta con la aplicación final
│   ├── app.py                               # código principal de la aplicación (streamlit o análisis final)
│
├── docs/                                    # documentos del proyecto
│   ├── documentacion_tecnica.md             # explicación técnica del proyecto y decisiones tomadas
│   ├── informe_final.md                     # informe final con resultados, análisis y recomendaciones
│   ├── fase_1_proyecto_grupo_c.pdf          # fase 1 del proyecto ecovida
│   └── reuniones.md                         # registro de reuniones, acuerdos y organización del equipo
│
├── assets/                                  # recursos visuales del proyecto
│   ├── images_del_2.2/                      # imágenes y gráficas del análisis exploratorio 2.2
│   ├── images_del_2.3/                      # imágenes y gráficas del análisis 2.3
│   └── screenshots/                         # capturas de pantalla de la app y resultados
│
├── requirements.txt                         # librerías necesarias para ejecutar el proyecto
└── README.md                                # documentación principal del proyecto
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

Abre en tu Navegador:
https://miprimerrepositorio-bau26ntybkem64zsucqiyb.streamlit.app/

El tablero se ejecutará automaticamente.

# Enlaces importantes

- Dashboard:[https://miprimerrepositorio-bau26ntybkem64zsucqiyb.streamlit.app/]
- Presentación: [https://www.canva.com/design/DAG6lq3idBM/TitIU82I3P5OW17qjk38Ig/edit?utm_content=DAG6lq3idBM&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton]
- Demostración en vídeo: [https://www.canva.com/design/DAG7EHt9goE/Sz6cjJknhykwHOshjQ7YJA/edit?utm_content=DAG7EHt9goE&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton]
