---
title: "Resultado3.md"
author: "NoelVacaMoreno"
date: "06/05/2016"
output: html_document
---
#Resultado 3
##Resultado de Quienes tendrán mejores sueldos según el grado académico.

Para este estudio tomé encuenta las columnas del dataset: 

* Capital ganado
* Capital perdido
* Educación
* Horas por semana

Para el estudio se ha utilizado un Select Attributes para filtrar los datos, en donde se 
eligieron los campos arriba mencionados, luego se usó un Set Role para para especificar que el
estudio se hará en base al parámetro educación, luego se utilizó un Decision Tree que hará 
el algoritmo de predicción y finalmente un Aplly Model parsear los elementos.

Se puedo observar que en el Arbol de Desiciones: 
* los que tiene mayor a 70654 de capital ganado y tienen mayor a 77 horas de trabajo por semana son Masters
* los que tiene mayor a 70654 de capital ganado y tienen mayor a 71 horas de trabajo son Bachilleres
* los que tiene mayor a 70654 de capital ganado y tienen mayor a 41 horas de trabajo son Profesores de escuela
* los que tiene mayor a 70654 de capital ganado y tienen menor o igual 41 horas de trabajo son Estudios Superiores
* los que tiene mayor a 70654 de capital ganado y tienen mayor 35 horas de trabjos son Doctorados
* los que tiene mayor a 70654 de capital ganado y tienen menor o igual 35 horas de trabajo son Profesores de Escuela
* los que tiene mayor a 70654 de capital ganado y tienen mayor 27 horas de trabajo han hecho algunos estudios universitarios
* los que tiene mayor a 70654 de capital ganado y tiene menor o igual 27 horas de trabjo son Bachilleres
Por otro lado: 

* los que tiene menor a 37702 de capital ganado son Masters
* los que tiene menor o igual a 14682 de capital ganado son de Estudios Superiores
* los que tiene mayor a 30961 de capital ganado son de Estudios Superiores
* ganan menor o igual a 30961, trabajando 4 horas por semana y son Masters
* ganan mas a 15022 y son Bachilleres
* ganan menor o igual 15022 y pueden ser Master o Bachilleres
