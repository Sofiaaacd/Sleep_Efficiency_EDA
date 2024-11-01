 # Análisis Exploratorio de Datos - Eficiencia del Sueño

**Redactado por:** Sofía Andrea Cruz Durán.

_____
 Este proyecto realiza un análisis exploratorio de datos (EDA) sobre el conjunto de datos Sleep Efficiency Dataset, buscando patrones que puedan influir en la eficiencia del sueño. Se analizan características como el estado de fumador, el consumo de alcohol, consumo de cafeína, entre otros factores, y su posible relación con la calidad del sueño.


## DATASET: *Sleep Efficiency Dataset*
**Fuente**: Kaggle.

El conjunto de datos utilizado contiene registros de eficiencia del sueño de varios individuos y algunos factores que podrían afectar su calidad de sueño, entre esos esta la edad, género, consumo de alcohol, frecuencia con la que realizan ejercicio, entre otros. 


## Descripción del Análisis Exploratorio de Datos (EDA)

Realizamos una limpieza no muy detallada de los datos, en donde renombramos las columnas con el fin de facilitar el acceso a las variables. Verificamos y gestionamos los valores nulos encontrados. Exploramos a través de diferentes gráficos y realizamos un análisis de la eficiencia del sueño según las principales variables del dataset. Este análisis nos permite concluir lo siguiente:

 - El análisis muestra que la eficiencia del sueño en mujeres aumenta a partir de los 50 años, mientras que en hombres se incrementa a partir de los 60 años.
 - Según el diagrama de caja, el hábito de fumar esta relacionado con una inestabilidad en la efiencia del sueño.
 - Las mujeres tienden a tener una eficiencia del sueño más consistente, mientras que los hombres tienen una mayor variabilidad en su eficiencia del sueño.
 - Las personas que hacen ejercicio entre 4 y 5 veces muestran una relación positiva con la eficiencia del sueño, mientras que aquellas personas que hacen ejercicio entre 0 y 3 veces tienen una menor eficiencia del sueño.
 - Podemos inferir que a medida que aumenta una persona el consumo de alcohol, disminuya la eficiencia del sueño. Aquellos que no consumen alcohol tienen una eficiencia del sueño más alta.


## Librerías utilizadas:

Para lla realización de este EDA, fue necesario usar las siguientes librerías:

- pandas
- numpy
- seaborn 
- matplotlib.pyplot 
- sklearn.impute 