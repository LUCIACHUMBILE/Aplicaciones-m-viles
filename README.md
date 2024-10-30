# Aplicaciones-m-viles

# Índice del Proyecto

| Sección                       | Descripción                                                       |
|-------------------------------|-------------------------------------------------------------------|
| 1. [Introducción](#introducción)          | Breve descripción del proyecto y sus objetivos.                |
| 2. [Preprocesamiento de Datos](#Análisis)|Importación de librerías, carga de datos, revisión de duplicados, nulos y tipo de datos.   |
| 3. [Análisis Datos](#instalación)         |Análisis de cohorte y métricas.|
| 4. [Prueba de hipótesis](#resultados)     |Prueba de hipótesis           |
| 5. [Conclusiones](#conclusiones)          |Resumen de las conclusiones .       |


En el presente proyecto se realizará un análisis de los datos recopilados de la apliación Treasure, en la que los usuarios y las usuarias publican anuncios para vender cosas que ya no necesitan con el fin de definir grupos que difieren en términos de métricas del producto (tasa de retención, tiempo dedicado a la aplicación, frecuencia de ocurrencia de eventos, conversión en el evento de destino, contacts_show).

Se realizará en el análisis exploratorio de datos, segmentación de usuarios y prueba de hipótesis para encontrar diferencias de conversión entre usuarios que descargaron la aplicación mediante google y quienes lo hicieron mediante bing.

#Insights

![image](https://github.com/user-attachments/assets/fd37b56a-5aef-4d40-a5b3-ffb90b94ba1c)

#Distribución por tipo de evento

![image](https://github.com/user-attachments/assets/c1498d1c-4241-437e-8c85-ed3452b4df1e)

# Usuarios según fuente 
![image](https://github.com/user-attachments/assets/7221a391-e7d8-4d9d-9f9b-8b86b12bb4cc)
# Distribución por tipo de evento  
![image](https://github.com/user-attachments/assets/32580fc6-29b5-4c09-87ba-a2298cf3eb97)


# Conclusiones
Dado que el valor p es muy alto (mayor a 0.05), no se puede afirmar que haya una diferencia significativa en las retensiones entre los usuarios que entraron a través de Google y los que entraron a través de Bing. En otras palabras, basándonos en esta prueba, los datos no sugieren que uno de los grupos tenga un rendimiento significativamente mejor que el otro en términos de retención.

Sin embargo se pueden aprovechar datos resultantes como:

El evento con mayor frecuencia fue tips_show, y en 2do lugar photos_show
La fuente más utilizada por los usuarios fue bing.
Los eventos con mayor frecuencia se da en todo los sources.

Para armar una mejor estrategia de marketing.
