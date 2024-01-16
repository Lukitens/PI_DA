# Proyecto individual Nº2: Siniestros Viales: #
![Siniestro_imagen](https://github.com/Lukitens/PI_DA/blob/main/Imagenes/SV-1.jpg) 

## Introducción: ##

En este proyecto trabajé con 2 archivos xslx sobre siniestros viales en la Ciudad de Buenos Aires, uno sobre [homicidios](https://github.com/Lukitens/PI_DA/blob/main/homicidios.xlsx) y el otro sobre [lesiones](https://github.com/Lukitens/PI_DA/blob/main/lesiones.xlsx)
Esta información proviene de la página oficial de [Buenos Aires](https://data.buenosaires.gob.ar/dataset/victimas-siniestros-viales)

El objetivo de este proyecto se basa en presentar un dashboard en Power BI con KPIS

## EDA: ##

Para este proyecto realicé un análisis exploratorio de datos en el que chequee valores nulos, valores duplicados, valores outliers, tendencias, etc. Esto lo realicé en un notebook de python para una mayor comodidad.
Para esto utilicé las librerias pandas, matplotlib y seaborn.
[Notebook](https://github.com/Lukitens/PI_DA/blob/main/eda.ipynb)

## Dashboard: ##

El dashboard lo hice en PowerBI, este dashboard traté de darle la misma estética a todas las páginas y un uso simple e interactivo, en el que se puede filtrar los datos por años y navegar entre las páginas con botones. 
Al dashboard le dí una estética como si fuera una presentación oficial de un ministerio, usando el color celeste y un diseño simple y serio.
[Dashboard](https://github.com/Lukitens/PI_DA/blob/main/dashboard_proyecto.pbix)

### Presentación ###

![Presentación Imagen](https://github.com/Lukitens/PI_DA/blob/main/Imagenes/Presentación.png)

En la presentación Puse un titulo general llamado Informe sobre siniestros viales en la Ciudad de Buenos Aires, acompañado del logo del ministerio de transporte y aclarando que el proyecto fue llevado a cabo por el Observatorio de Movilidad y Seguridad Vial. Abajo de eso coloqué unos botones con los cuáles se puede ir a la página que se solicite

### Informe Homicidios ###
![Informe Homicidios](https://github.com/Lukitens/PI_DA/blob/main/Imagenes/InformeHomicidios.png)

 - En esta página podemos observar que en el primer gráfico el tipo de calle con mayor víctimas es la avenida, esto se debe a que hay una gran cantidad de personas circulando simultaneamente a una velocidad muy alta, por lo que hace que sea mas probable los accidentes. Le siguen las autopistas y luego las calles normales

 - El número total de victimas es 717 y el máximo de victimas de homicidios en un mismo día fueron 3

 - El género con mas porcentaje de victimas lo tiene el género masculino con una amplia diferencia, ya que abarca el 76,65 % de los casos

 - Vemos que el año con mayor cantidad de victimas fue el 2018 y disminuyó considerablemente en 2020 y 2021 debido a la pandemia

 - La comuna con el mayor número de victimas es la comuna 1, esto se debe a que está compuesta por 6 barrios que son muy transitados

 - En el gráfico de victimas por franja horaria podemos ver que la mayoría de accidentes se dan entre las 5 y las 7 AM y por la noche luego de las 12 AM disminuyen

### Informe Lesiones ###
![Informe Lesiones](https://github.com/Lukitens/PI_DA/blob/main/Imagenes/InformeLesiones.png)

 - Vemos que en el primer gráfico, el mayor numero de victimas por el tipo de calle nuevamente lo tienen las avenidas

 - El número total de victimas fue de aproximadamente 28.000 lesionados y el número maximo de victimas en un día fueron 16

 - Vemos que nuevamente la mayor parte de las victimas son hombres con un 67,08% de los casos

 - Podemos observar que hubo una fuerte caída de los casos de lesiones luego de 2019 debido a la pandemia

 - Nuevamente la comuna con mayor cantidad de victimas es la comuna 1

La mayor cantidad de accidentes se producen entre las 16 y las 17 horas y luego disminuyen y que luego de las 12 AM vuelven a disminuir los casos

### Mapas ###
![Mapas](https://github.com/Lukitens/PI_DA/blob/main/Imagenes/Mapas.png)

Esta página esta dedicada exclusivamente a los mapas para poder verlos con mayor claridad y que las páginas no queden con un exceso de información y todo amontonado

### KPIs ###
![KPIs](https://github.com/Lukitens/PI_DA/blob/main/Imagenes/KPIs.png)

En esta página se pueden observar los KPIs propuestos que consistían en:

  - Reducir en un 10% la tasa de homicidios en siniestros viales de los últimos seis meses, en CABA, en comparación con la tasa de homicidios en siniestros viales del semestre anterior.

  - Reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año, en CABA, respecto al año anterior.

En esta página se puede filtrar la información por año y por semestre

[Autor](https://www.linkedin.com/in/lucas-raña-49120a271/)
