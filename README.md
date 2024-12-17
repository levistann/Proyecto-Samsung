Nombre del proyecto:
Análisis del precio del petróleo y su correlación con diferentes eventos climáticos, económicos y geopolíticos que se desarrollaron en el mundo de 1990 a 2024.

Descripción:
El proyecto se enfoca en analizar los precios históricos del petróleo y cómo estos se correlacionan con diferentes eventos globales, como crisis económicas, conflictos geopolíticos, cambios en políticas energéticas, y avances tecnológicos, entre otros.
Utilizando un conjunto de datos que abarca varias décadas, el objetivo es explorar patrones y tendencias en los precios del crudo, además de identificar posibles influencias externas. Además, se busca representar visualmente estos datos para facilitar
la comprensión y toma de decisiones dentro de contextos económicos y políticos.

Arquitectura:
![Mesa de trabajo 1](https://github.com/user-attachments/assets/5d4ae95a-748b-40e0-8ed0-c8f99856518a)

Proceso:
  Fuente del dataset:
    Se utiliza la librería pandas para cargar el archivo CSV que contiene los datos históricos del precio del petróleo.

  Preparación de los datos:
    Conversión de la columna de fechas a un formato datetime.
    Establecimiento de la columna de fechas como índice del DataFrame.
    Filtrado de los datos para mantener un rango específico de fechas (por ejemplo, desde 1990 hasta 2022).

  Cálculo de indicadores:
    Cálculo de la media móvil simple (SMA) para diferentes ventanas de tiempo (por ejemplo, SMA50 y SMA100).
    Identificación y manejo de valores atípicos utilizando el rango intercuartílico (IQR).
    Cálculo de la variación porcentual diaria del precio del petróleo.

  Visualización de datos:
    Creación de gráficos de líneas para visualizar la evolución del precio del petróleo a lo largo del tiempo.
    Superposición de gráficos de dispersión para resaltar máximos y mínimos históricos.
    Adición de indicadores como SMA en los gráficos para facilitar el análisis visual.

  Análisis de eventos históricos:
    Identificación de eventos históricos relevantes que han afectado el precio del petróleo.
    Superposición de estos eventos en los gráficos para analizar la correlación entre eventos y cambios en el precio del petróleo.

Estado del proyecto:
  Carga y preparación de datos: Completado.
    Los datos históricos del precio del petróleo han sido cargados exitosamente desde un archivo CSV.
    Las fechas han sido convertidas a un formato datetime y establecidas como índice del DataFrame.
    Se ha filtrado el rango de fechas relevante para el análisis.
    
  Cálculo de indicadores: Completado.
    Se han calculado correctamente la media móvil simple (SMA) y la media móvil exponencial (EMA) para diferentes ventanas de tiempo.
    Se han identificado y manejado valores atípicos en los datos.
    La variación porcentual diaria del precio del petróleo ha sido calculada y añadida al DataFrame.
    
  Visualización de datos: Completado.
    Se han creado gráficos de líneas para visualizar la evolución del precio del petróleo.
    Se han añadido gráficos de dispersión para resaltar los máximos y mínimos históricos.
    Los indicadores SMA y EMA se han superpuesto en los gráficos.
    
  Análisis de eventos históricos: En progreso.
    Se ha comenzado la identificación de eventos históricos relevantes.
    Próximamente se realizará la superposición de estos eventos en los gráficos para analizar su impacto en el precio del petróleo.

  Documentación y presentación: En progreso.
    Se está trabajando en la documentación detallada del proyecto, incluyendo el README.
    Próximamente se realizará la preparación de la presentación final del proyecto.

Agradecimientos:
  SAMSUNG Innovation Campus
