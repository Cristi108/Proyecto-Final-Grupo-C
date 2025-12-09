# **INFORME FINAL DEL PROYECTO**

## **Introducción**

El agua es un recurso básico para la vida. En Panamá, todos los días se producen millones de galones de agua potable, pero aun así se registran cientos de casos de enfermedades relacionadas con el agua en todas las provincias. Esta situación despertó una pregunta importante:

¿Por qué, si producimos tanta agua, todavía hay personas que se enferman?

Nuestro proyecto nació para analizar esta contradicción. A través de datos reales del país, buscamos comprender lo que ocurre entre la producción, el consumo y la salud pública. El objetivo fue descubrir si existe una relación entre la cantidad de agua disponible, la forma en que se distribuye y la aparición de enfermedades hidroalimentarias.

Durante el trabajo analizamos información del periodo 2018–2022 de todas las provincias, usando datos de producción y consumo de agua potable y registros de enfermedades. La intención no fue solo describir el problema, sino presentar evidencias visuales y recomendaciones prácticas que ayuden a mejorar la situación en el futuro.

Este informe resume los objetivos, el método utilizado, los resultados y qué acciones pueden ayudar a cuidar mejor el agua y la salud de las personas.

---
## **Objetivos y metodología**

### **Objetivos del proyecto**

• Analizar la producción y consumo de agua potable en Panamá.

• Comparar la disponibilidad de agua con los casos de enfermedades hidroalimentarias.

• Identificar provincias con mayor riesgo.

• Proponer recomendaciones para mejorar la calidad del agua.

---

### **Metodología aplicada**

Para el análisis utilizamos datos de:

• Producción de agua potable

• Consumo por tipo de usuario

• Casos de enfermedades hidroalimentarias

• Las fuentes fueron principalmente el IDAAN y el INEC.


Los pasos del análisis fueron:

**1.Carga de datos:**
Se importaron los archivos CSV de producción, consumo y enfermedades.

**2.Limpieza de la información:**
Se eliminaron columnas que no servían, se corrigieron formatos y se revisaron valores vacíos.

**3.Unificación:**
Los tres conjuntos de datos se integraron en una sola estructura para poder compararlos.

**4.Cálculos y análisis:**
Se calcularon totales por año y provincia, y se revisaron tendencias.

**5.Visualizaciones:**
Se crearon gráficos para observar cómo los datos cambiaron con el tiempo.


Para el desarrollo utilizamos:

• Python

• Pandas, NumPy

• Matplotlib y Seaborn

• Streamlit para el tablero interactivo.

---

## **Principales hallazgos**

Después de organizar y analizar los datos, encontramos tres conclusiones importantes:

**1. Producción vs Consumo**

Panamá produce más agua de la que se consume, pero la diferencia desaparece en el camino.
Esto indica fugas, tuberías antiguas o pérdidas en la red de distribución.

**2. Enfermedades siguen ocurriendo**

A pesar de la producción alta, las enfermedades hidroalimentarias no disminuyen.
Esto demuestra que el problema no es la cantidad de agua, sino cómo llega a las personas.

**3. Provincias vulnerables**

Las zonas rurales y comarcas fueron las más afectadas.
Estas áreas tienen:

• Infraestructura más débil

• Menos mantenimiento

• Mayor dificultad de acceso

Los datos muestran que mejorar la infraestructura puede reducir los casos de enfermedades y mejorar la calidad de vida.

---

## **Retos del proyecto**

Durante el proyecto enfrentamos algunos desafíos naturales:


• Los archivos venían con diferentes formatos.

• Hubo que estandarizar columnas y nombres.

• Algunas provincias no tenían información completa para todos los años.

• La unión de datos de diferentes fuentes tomó tiempo.

Sin embargo, con trabajo en equipo y organización, pudimos resolverlos.
Cada reto nos permitió aprender más sobre el manejo de datos reales.

---

## **Recomendaciones**

A partir de los resultados, recomendamos acciones prácticas:


• Revisar las tuberías viejas y reparar fugas.

• Monitorear la calidad del agua antes de que llegue a los hogares.

• Enfocar inversiones en provincias vulnerables.

• Realizar programas de educación comunitaria para el manejo seguro del agua.

• Mantener un registro actualizado de producción, consumo y salud.

Estas recomendaciones pueden ayudar a reducir casos de enfermedades y garantizar agua segura para todos.

---

## **Conclusión**

Nuestro proyecto demostró que en Panamá se produce suficiente agua potable, pero el problema aparece durante la distribución. El agua se pierde o se contamina en el camino, lo que afecta directamente a la salud de la población, especialmente en áreas rurales.

La solución no depende solo de producir más agua; depende de cuidar la infraestructura que la lleva hasta los hogares.
Con datos reales descubrimos que donde la red es más fuerte, hay menos enfermedades.
Por eso, invertir en mantenimiento, monitoreo y prevención es esencial.

En resumen:

**Si cuidamos la red, cuidamos el agua.**

**Si cuidamos el agua, cuidamos a las personas.**

Este proyecto nos permitió entender cómo los datos pueden apoyar decisiones importantes para el país. La información se convierte en acción, y cada mejora en la red de agua puede significar una mejora directa en la salud de miles de familias.
