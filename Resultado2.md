---
title: "Resultado2.md"
author: "NoelVacaMoreno"
date: "06/05/2016"
output: html_document
---
#Resultado 2
##Resultado del estudio sobre ganancias segun factores

Para este estudio tomé encuenta las columnas del dataset: 

* Edad
* Capital ganado
* Capital perdido
* Horas por semana

![Resultado2](https://github.com/enevaca/uasb_analytics/blob/master/Resultado2.png "Resultado2")

Para el estudio se ha utilizado un Select Attributes para filtrar los datos, en donde se 
eligieron los campos arriba mencionados, luego se usó un Filter Examples para realizar 
el estudio o filtro de algún parámetro de acuerdo a alguna condición especifícica y, 
finalmente se utilizó un Clustering como clasificador que trabaja con un número k agrupaciones 
y el número maximo de iteracción que al final clasifca en el número de grupos especificado
y a cada grupo lo llama cluster.

El estudio se ejecutó con k=3 y con 10 iteracciones, teniendo cluster 0, 1 y 2
En conclusión se puede decir que:
* En el cluster 1 estan los más viejos, es decir, de mayor edad
* Los que ganan más, igual se encuentran en el cluster 1
* Los que pierden platan, estan sólo en el cluster 2
* Los que trabajan más horas por semana, se encuentran en el cluster 1
* Para los del cluster 0 y 1 no hay pérdidas

Cluster 0: 1303 items
Cluster 1: 159 items
Cluster 2: 31099 items
Total number of items: 32561

