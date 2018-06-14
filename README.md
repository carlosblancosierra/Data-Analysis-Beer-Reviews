Data-Analysis-Beer-Reviews

Para la aplicación a un puesto de data analyst me dieron el reto de analizar una base de datos de cervecerias y sus respectivas cervezas, esto debia hacerse con python o R, yo decidi usar python.

Estas fueron las preguntas:

1.	¿Qué cervecería produce la cerveza más fuerte según ABV?
Schorschbräu hace la cerveza mas fuerte segun el abv, la cual se llama Schorschbräu Schorschbock 57% y cuenta con 57.7 de porcentaje de alcohol

2.	¿Si tuviera que elegir 3 cervezas para recomendar usando sólo estos datos, cuáles elegiría? 
Si tuviera que elegir para probar tres cervezas con solo estos datos, elijiria las siguientes tres cervezas:

Pliny The Elder
Weihenstephaner Hefeweissbier
Bell's Hopslam Ale

Puesto dentro del grupo de cervezas que solo obtuvieron calificacion general perfecta estas son las que mas cantidad de calificaciones tienen, el intervalo de confianza en el que verdadera media de la poblacion es efectivamente de 5.0 es mayor a medida que se cuenta con mas datos.

3.	¿Cuál de los factores (aroma, taste, apperance, palette) es más importante para determinar la calidad general de una cerveza? 
De acuerdo al modelo de regresion lineal calculado y la base de datos el factor mas influyente es el sabor de la cerveza, ya que cuenta con el mayor coeficiente en la ecuacion (0.55572727), por delante del aroma (factor = 0.07030425), apariencia (factor = 0.04652282), palate (factor = 0.26869394) y porcentaje volumetrico de alcohol (factor = -0.03084413)


4.	¿Si yo típicamente disfruto una cerveza debido a su aroma y apariencia, qué estilo de cerveza debería probar? 
Tomando en cuenta solo el aroma y la apariencia de las cervezas, yo recomendaria probar el estilo 'American Double / Imperial Stout'

Se llego a esta conclusion ya que se calcularon los ratings usando el modelo de regresion lineal calculado con la base de datos pero solo tomando en cuenta aroma y apariencia, con los demas factores en 0.

Adicionalmente se analizo si algun tipo de cerveza contaba con bajos reviews para evitar tener valores que no tengan alto valor estadistico.

Luego, con estos nuevos ratings se calculo el promedio de dicho rating por cada estilo de cerveza, el promedio mayor lo obtuvo el estilo recomendado: 'American Double / Imperial Stout'.
