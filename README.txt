
Recurrent Neural Network for Stock Market

Inditex

Mercado bursátil y Deep Learning

El 12 de marzo de 2020, el Ibex35  sufrió la mayor caída de su historía, perdió un 14,06% y acumula unas pérdidas del 36,6% en las últimas tres semanas. 

¿Que capacidad tiene una Red Neuronal para predecir el valor de cotización de una determinada acción?

La turbulencia y volatilidad actual en los mercados, es un factor de motivación para ir en búsqueda de una respuesta. 

He seleccionado Inditex, por ser un título nacional, mediático y de gran capitalización bursátil (74.000 millones de euros). Su valor de cierre de los últimos 5 años, desde el 11-3-2015 hasta el 12-3-2020, ambos inclusive, tiene un total de 1282 registros.

Con los 1100 primeros registros he entrenado una red neuronal multicapa recurrente (LSTM Bidireccional) y profunda. 

Con los 182 últimos registros he testado el modelo que ha alcanzado un MAE de 0,44 € con una predicción diaria.

Llegado a este punto, me planteo:

 
¿Que MAE obtendría la RNR en su predicción de los precios de cierre de las próximas 5 sesiones?

¿Que precio de la acción prevé la RNN para el cierre de la sesión 5ª?


Aunque el modelo está entrenado para hacer predicciones diarias. Ello no impide pedirle una predicción a 5 días vista pero, eso si, con mucho mayor margen de error.

El modelo predice para la 5ª sesión, es decir, para el jueves 19 de marzo de 2020, un precio de cierre de 21.98 euros. 


El 19 de marzo de 2020, Inditex ha cotizado entre un mínimo de 20,23 € y un máximo de 22,30€. Por tanto, la predicción de 21,98€  para ese día ha tenido su oportunidad, como ventana de entrada o salida en el valor en función de la estrategia del inversor.

No obstante lo anterior, lo cierto es que el día 19 de marzo de 2020 su valor de cierre ha sido 20,75 € por título.