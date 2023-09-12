Proyecto Pick-ups Uber NY
Este proyecto se centra en la construcción de un dataframe utilizando funciones de pandas para leer archivos CSV y concatenar todos los registros. El objetivo principal es analizar el comportamiento de los viajes de Uber en la ciudad de Nueva York. Para ello, se desglosan los datos en función del mes, día y hora, ya que estos son los componentes del registro denominado "Date/time".

El proyecto utiliza varias bibliotecas, incluidas glob, os, pandas, datetime, matplotlib.pyplot y seaborn.

El proceso comienza con la lectura de múltiples archivos CSV y su concatenación en un único dataframe. Una vez que los datos están en un único dataframe, se observa que hay columnas como "Date/Time", "Lat", "Lon", "Base", entre otras. Hay un total de 4.534.327 registros.

El análisis posterior se centra en la columna "Date/Time", que se transformó en tipo string al leer los archivos CSV. Para responder a preguntas específicas y realizar un análisis descriptivo, es necesario ajustar el formato de los datos. Se plantean preguntas como cómo se comporta la demanda con respecto al mes, día y hora.

El proyecto también incluye la creación de listas para desglosar la columna "Date/Time" en componentes individuales como mes, día, año, hora y día de la semana.

Finalmente, se realiza un análisis descriptivo de las diferentes columnas creadas, como Mes, Día, Año, Hora y Día de la semana. Por ejemplo, se agrupan los datos por mes y se crea un sub-dataframe para visualizar el número de viajes por mes.