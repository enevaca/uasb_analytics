---
title: "Resultado1.md"
author: "NoelVacaMoreno"
date: "06/05/2016"
output: html_document
---
#Resultado 1
##Resultado del estudio de la probabilidad para entrar a la universidad

Se desea enconcontar quien van a llegar a la universidad segun los siguientas datos:

* Edad
* Educación
* Estado Civil
* Nacionalidad
* Raza

![Resultado1](https://github.com/enevaca/uasb_analytics/blob/master/Resultado1.png "Resultado1")

Para el estudio se ha utilizado un Select Attributes para filtrar los datos, en donde se 
eligieron los campos arriba mencionados, luego se usó un Set Role para especificar que el
estudio se hará en base al parámetro educación, luego se utilizó un Decision Tree que hará 
el algoritmo de predicción y finalmente un Aplly Model parsear los elementos.

Por tanto todos los que tienen una edad mayor a 17 años, tienen los siguiente, de ellos los que 
tienen menor o igual a 18 años llegarán a 11º grado; por otro lado los que tienen edad mayor a 
llegarán a estudios Superiores, caso contrario harán algunos estudios universitarios.

Por otro lado, los que tienen edad menor o igual 17 años según su estado civil, los que lleguen 
a casarse llegarán hasta 9º grado y los que nunca se casen llegarán hasta 11º grado.
