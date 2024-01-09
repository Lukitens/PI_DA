# Proyecto individual Nº2: Siniestros Viales: #
![Siniestro_imagen](https://github.com/Lukitens/PI_DA/blob/main/SV-1.jpg)

## Introducción: ##

En este proyecto trabajé con 2 archivos xslx sobre siniestros viales en la Ciudad de Buenos Aires, uno sobre [homicidios](https://github.com/Lukitens/PI_DA/blob/main/homicidios.xlsx) y el otro sobre [lesiones](https://github.com/Lukitens/PI_DA/blob/main/lesiones.xlsx)
Esta información proviene de la página oficial de [Buenos Aires](https://data.buenosaires.gob.ar/dataset/victimas-siniestros-viales)

El objetivo de este proyecto se basa en presentar un dashboard en Power BI con KPIS

## EDA: ##

Para este proyecto realicé un análisis exploratorio de datos en el que chequee valores nulos, valores duplicados, valores outliers, tendencias, etc. Esto lo realicé en un notebook de python para una mayor comodidad.
Para esto utilicé las librerias pandas, matplotlib y seaborn.

Durante el EDA vi que el excel de homicidios tenía muchas filas con todos los datos nulos, por lo que opté por eliminarlas y guardarlas en el excel [homicidios_sinulos.xlsx](https://github.com/Lukitens/PI_DA/blob/main/homicidios_sinnulos.xlsx)
[Notebook](https://github.com/Lukitens/PI_DA/blob/main/eda.ipynb)

## Dashboard: ##

El dashboard lo hice en PowerBI, este dashboard traté de darle la misma estética a todas las páginas y un uso simple e interactivo, en el que se puede filtrar los datos por años y navegar entre las páginas con botones
[Dashboard](https://github.com/Lukitens/PI_DA/blob/main/dashboard_proyecto.pbix)
