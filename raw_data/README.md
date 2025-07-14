# 📉 Esta sección corresponde a las bases de datos sin procesar

En total se trabajó con cuatro datasets para el análisis.

Fueron dos los datasets principales, los cuales fueron extraídos del Portal de Datos Abiertos del Gobierno de la Ciudad de México, y de los Datos Abiertos de Incidencia Delictiva del Gobierno de México. 

Como apoyo, se usaron dos datasets más, obtenidos también de la última fuente mencionada.


# 📊 Los dos datasets principales:
- Carpetas de Investigación (acumulado 2016-2024). Llamado *"carpetasFGJ_acumulado_2025_01"*. (Archivo demasiado grande para incluirlo en el repositorio. Se adjunta el link de descarga más abajo).
- Cifras de Víctimas del Fuero Común, 2015 - mayo 2025. Llamado en este repositorio *"IDVFC_NM_ene25.csv"*


# 📊 Los dos datasets  de apoyo:
-   Cifras de Incidencia Delictiva Municipal, 2015 - mayo 2025. Llamado en este repositorio *"IDM_NM_abr25.zip"*
-   Cifras de Incidencia Delictiva Estatal, 1997 - diciembre 2017. Llamado en este repositorio *"IDE-1997-2017.csv"*


# ➡️ Convención de nombres para distinguir los distintos datasets en la limpieza y el análisis:

-  *IDM_NM_abr25.csv* recibe la denominación DF1 (o Dataframe 1).
-  *carpetasFGJ_acumulado_2025_01* recibe la denominación DF2 (o Dataframe 2).
-  *IDVFC_NM_ene25* recibe la denominación DF3 (o Dataframe 3).
-  *IDE-1997-2017* recibe la denominación DFextra (o Dataframe extra).


# 📌 Relevancia y estructura de cada base de datos en el proyecto:

-  **Dataframe 1:** Nos introduce a las bases de datos de la privación a la libertad personal. Su manipulación tiene como objetivo extraer información sobre las modalidades en que se presenta el delito hacia la libertad personal, con el fin de saber cómo filtrar el Dataframe 2, el cuál es la base de datos central para el proyecto.
  
-  **Dataframe 2:** Es el corazón del análisis en este proyecto. Se limpia con base en la información recopilada para el Dataframe 1. Contiene información fundamental sobre las denuncias registradas: fechas, horas, modalidad del delito, colonia, alcaldía del hecho, otros delitos asociados, etc. Abarca desde 2016 hasta enero de 2025.

-  **Dataframe 3:** Complementa el Dataframe 2 con información sobre las víctimas, que es su rango de edad y sexo.

-  **Dataframe extra:** Contiene registros de carpetas de investigación desde 1997 hasta 2017. Sirve de apoyo para el Dataframe 2 en cuestión de desarrollar hipótesis sobre los patrones temporales del delito de interés.


# 📥 Descarga de *carpetasFGJ_acumulado_2025_01*:

Debido al tamaño del archivo CSV, el dataset Carpetas de Investigación (acumulado 2016-2024) no está incluido en este repositorio. Por lo que se adjunta el siguiente enlace de descarga:

[Descargar del dataset desde Google Drive](https://drive.google.com/drive/u/4/folders/135wNU9gdzE8I6oFZqswHkQfrBuBdlNte)




