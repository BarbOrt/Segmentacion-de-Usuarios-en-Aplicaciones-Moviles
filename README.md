# Segmentación de Usuarios en Aplicaciones Móviles

El objetivo principal de este análisis es segmentar a los usuarios en función de su comportamiento en la aplicación y probar hipótesis estadísticas relacionadas con métricas clave del producto. Esta segmentación nos permitirá identificar grupos de usuarios con comportamientos similares, lo que a su vez ayudará a personalizar estrategias de marketing y mejorar la retención de usuarios.


## Objetivo del Proyecto**

El objetivo de este proyecto es segmentar a los usuarios y usuarias de la aplicación móvil Trash to Treasure en función de su comportamiento y analizar diferentes métricas del producto, como la tasa de retención, tiempo dedicado a la aplicación, frecuencia de eventos y conversión en el evento `contacts_show`.

## Pasos del Proyecto**

1. Importación de Librerías y Carga de Datos

- Importar las librerías necesarias.
- Cargar los datasets `mobile_dataset_us.csv` y `mobile_sources_us.csv`.

2. Preprocesamiento de Datos

- Revisar y manejar valores ausentes.
- Convertir tipos de datos si es necesario.
- Unificar el formato de los datos temporales.
- Fusionar datasets en función del `user.id`.

3. Análisis Exploratorio de Datos (EDA)

- Visualizar la distribución de eventos por tipo de evento.
- Analizar la distribución temporal de los eventos.
- Calcular y visualizar el número de usuarios por fuente de descarga.
- Analizar las frecuencias de los eventos por usuario.

4. Segmentación de Usuarios

- Definir criterios de segmentación basados en los eventos completados.
- Implementar técnicas de segmentación (e.g., clustering).
- Describir los segmentos resultantes en términos de métricas del producto.

5. Prueba de Hipótesis

- Formular y probar una hipótesis sobre la diferencia en la conversión en vistas de información de contacto entre quienes descargaron la aplicación de Bing y quienes la descargaron de Google.
- Formular una hipótesis estadística adicional sobre los datos del dataset y probarla.

6. Análisis de Métricas de Negocio

- Calcular y analizar la tasa de retención de usuarios.
- Calcular el tiempo promedio dedicado a la aplicación.
- Evaluar la frecuencia de ocurrencia de eventos.
- Analizar la conversión en el evento `contacts_show`.

7. Preparar una Presentación

- Crear visualizaciones claras y concisas de los hallazgos.
- Elaborar una narrativa que explique los resultados y su relevancia.
- Preparar un documento en PDF con la presentación final.

8. Construcción de dashboards en Tableau para visualizar las métricas y los segmentos de usuarios:

1. **[Dashboard 1](https://public.tableau.com/app/profile/barbara.ortiz/viz/Dashboard1_proyectofinal/Dashboard1)**: 
   - Distribución de eventos por tipo.
   - Indicador del número de usuarios.
   - Filtro por fecha de evento.

2. **[Dashboard 2](https://public.tableau.com/app/profile/barbara.ortiz/viz/Dashboard2_proyectofinal/Dashboard2)**: 
   - Número de eventos por día.
   - Histograma del número de usuarios por fuente.
   - Filtro por tipo de evento.

La presentación final se preparó en PDF, resumiendo los hallazgos y conclusiones del proyecto.
