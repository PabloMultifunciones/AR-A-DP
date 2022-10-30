# AR-A-DP

Aprendizaje Reforzado - Adicional - Distribucion de Probabilidades

### Introduccion ###

Una distribución de probabilidad es una función que describe las probabilidades de ocurrencia de los diversos resultados posibles de una variable aleatoria . Como ejemplo simple, considere el experimento de lanzar una moneda al aire tres veces. Los posibles resultados de cada lanzamiento individual son cara o cruz. Sea la variable aleatoria X el número de cruces que resultan de tres lanzamientos de una moneda justa; el espacio de muestra de este experimento es:

{HHH, HHT, HTH, HTT, THH, THT, TTH, TTT}

Por lo tanto, hay 1 forma de que ocurra 0 colas, 3 formas de que ocurra 1 colas, 3 formas de que ocurran 2 colas y 1 forma de que ocurran 3 colas; la distribución de probabilidad se muestra en la siguiente tabla:

![d](https://user-images.githubusercontent.com/95035101/198897499-49e65f09-9f72-4c31-8b2e-555811a1b76c.png)

Lo anterior es un ejemplo de una distribución de probabilidad discreta. Tenga en cuenta que la suma de probabilidades debe ser 1.

Todas las distribuciones de probabilidad se pueden clasificar como distribuciones de probabilidad discretas o distribuciones de probabilidad continuas.

### Distribución de probabilidad discreta ###

Una distribución de probabilidad es discreta o continua dependiendo de si la variable aleatoria es discreta o continua. Una variable discreta solo puede tomar valores distintos, como el lanzamiento de una moneda que cae en cara o cruz, o el número de estudiantes en una clase. La moneda solo puede caer en cara o cruz, mientras que el número de estudiantes en una clase es un número específico, como 20. No puede haber 20.5 estudiantes, 30.7 estudiantes, etc.

Una distribución de probabilidad discreta se puede describir mediante una función de masa de probabilidad (pmf), que proporciona la probabilidad de ocurrencia de cada valor de una variable aleatoria discreta. Un pmf tiene las siguientes propiedades:

* La probabilidad, P, de x ∈ X es: P (X=x)=f (x)  
* f (x) ≥ 0 para todo x  
* La suma de las probabilidades de todos los valores posibles debe ser igual a 1

Se puede usar una distribución uniforme discreta para representar una variable aleatoria que tiene un número finito de valores que tienen la misma probabilidad de ocurrencia. Lanzar un dado de 6 caras es un ejemplo, ya que cada una de las 6 caras del dado tiene la misma probabilidad de ocurrir en un lanzamiento dado.

Sea X una variable aleatoria discreta con n valores en el intervalo [a, b]. X tiene una distribución uniforme discreta si su pmf está definido por

 ![Zih4KSA9IFxmcmFjMW4_100](https://user-images.githubusercontent.com/95035101/198897609-2fecc627-41b8-4f4a-b163-24ed717b8584.svg)

para x=1, 2, 3, … n. Tiene la siguiente forma:

![discrete-uniform-distribution](https://user-images.githubusercontent.com/95035101/198897654-536344c9-b205-4065-837e-a2daf85f730d.png)

### Distribución binomial ###
Se utiliza una distribución binomial para modelar un experimento en el que solo hay dos resultados posibles. Lanzar una moneda justa de dos caras es un ejemplo, ya que los únicos resultados posibles son cara o cruz. A continuación se muestra un ejemplo de una distribución binomial para el experimento de lanzar 2 monedas justas:  

![binomial-distribution](https://user-images.githubusercontent.com/95035101/198897686-ec545a3c-f1ae-443d-9d08-82c2184234c4.png)

El pmf para una distribución binomial es:

![Zih4KSA9IFxiaW5vbXtufXt4fXBeeHFee24teH0_100](https://user-images.githubusercontent.com/95035101/198897707-aeded70f-96a7-4236-907f-a737e8848515.svg)

p es la probabilidad de éxito de una prueba individual  
q=1 – p es la probabilidad de falla  
n es el número de pruebas  
x es el número de éxitos de n ensayos  

![XGJpbm9te259e3h9ID0gXGZyYWN7biF9e3ghKG4teCkhfQ_100](https://user-images.githubusercontent.com/95035101/198897718-de85bdae-ce12-44f5-8b0c-fc22592f1223.svg)

Ejemplo

Dado que solo el 20% de todos los adultos pueden aprobar una prueba cognitiva específica, ¿cuál es la probabilidad de que de 5 adultos seleccionados al azar, 3 de ellos pasen la prueba?

Dado que solo hay dos resultados posibles, aprobado o reprobado, podemos usar el pmf para una distribución binomial para determinar la probabilidad, donde p=0.2, q=0.8, n=5 y x=3:


![PSBcYmlub217NX17M30oMC4yKV4zKDAuOF57NS0zfSk_100](https://user-images.githubusercontent.com/95035101/198897758-f821a68e-ccbd-4aec-9c8e-b2d8a5f7bb5b.svg)
![PSBcZnJhY3s1IX17MyEyIX0oMC4yXjMpKDAuOF4yKSA9IDAuMDU_100](https://user-images.githubusercontent.com/95035101/198897766-8676c769-d2cc-46ca-9ffa-97a1fd107379.svg)

Por lo tanto, existe un 5% de probabilidad de que 3 de los 5 adultos elegidos al azar pasen la prueba cognitiva.

### Distribución de Poisson ###

Se puede utilizar una distribución de Poisson para modelar la probabilidad de que ocurra un evento independiente una cierta cantidad de veces durante un período específico de tiempo (o distancia, área , volumen, etc.). Por ejemplo, la cantidad de veces al mes que un automóvil pasa una luz roja en particular puede presentar una distribución de Poisson.

El pmf para una distribución de Poisson es

e ≈ 2.718 es el número de Euler.

Distribución de probabilidad continua
Una variable continua es aquella que puede tomar cualquier valor dentro de algún intervalo, y una distribución de probabilidad continua es la distribución de probabilidad de una variable aleatoria continua. Los ejemplos de variables continuas incluyen la altura y el peso. Hay límites superior e inferior para la altura y el peso humanos, pero dentro de esos límites, hay un número infinito de alturas y pesos posibles. Por ejemplo, es poco probable que dos personas que miden 5 pies y 8 pulgadas de alto tengan exactamente la misma altura. En cambio, su altura probablemente varía en algún valor decimal que no se puede medir con precisión.

La probabilidad de que una variable aleatoria continua adopte cualquier resultado individual es 0, por lo que, a diferencia de las distribuciones de probabilidad discretas, las distribuciones de probabilidad continuas no se pueden representar mediante una tabla. En cambio, las distribuciones de probabilidad continuas se representan típicamente mediante una función de densidad de probabilidad, que se puede usar para determinar la probabilidad de que la variable aleatoria se encuentre dentro de un cierto rango de valores. La siguiente figura es un ejemplo de una distribución de probabilidad continua.

![probability-density-function](https://user-images.githubusercontent.com/95035101/198897801-f8696368-76f1-4a5a-919b-a875f080170a.png)

La probabilidad de que un resultado, X, se encuentre entre el intervalo ayb está representada por el área sombreada debajo de la curva, que se puede encontrar calculando la integral de la función de densidad de probabilidad en el intervalo dado. En otras palabras,

![UChhIDwgWCA8IGIpID0gXGludF9hXmJ7Zl9YKHgpZHh9_100](https://user-images.githubusercontent.com/95035101/198897824-2115e063-2d35-4e47-95a2-5f14f0dfe1ef.svg)

Tenga en cuenta que si a fueran -∞ y b fueran + ∞,

![XGludF97LVxpbmZ0eX1ee1xpbmZ0eX17Zl9YKHgpZHggPSAxfQ_100](https://user-images.githubusercontent.com/95035101/198897832-c09e7f34-d0b5-452d-89b0-d5abcc22999a.svg)

Esto se debe a que la probabilidad de todo el PDF debe ser igual a 1, ya que existe un 100% de probabilidad de que X se encuentre en este intervalo si es un número real.

Hay muchos tipos diferentes de distribuciones de probabilidad continua, incluida una distribución normal, una distribución uniforme continua y una distribución de chi cuadrado.

### Distribución normal ###

La distribución normal, también conocida como distribución gaussiana, o más informalmente como curva de campana, es una de las distribuciones de probabilidad más comunes. Su nombre informal se basa en el hecho de que tiene forma de campana, aunque no es el único tipo de distribución que tiene forma de campana. La siguiente figura muestra una distribución normal donde μ es la media y σ es la desviación estándar.

![empirical-rule](https://user-images.githubusercontent.com/95035101/198897844-1706288d-b0be-4843-b87d-78cc6eea65e2.png)

Una distribución normal es simétrica con respecto a su media, y la mayoría de los valores de una distribución normal se agrupan alrededor de la media, con el 99,7% de los valores dentro de 3 desviaciones estándar de la media. Cuanto más lejos esté un valor de la media, es menos probable que ocurra. Más específicamente, para una variable aleatoria continua que tiene una distribución normal, el 68% de las observaciones caerán dentro de una desviación estándar de la media, el 95% caerán dentro de dos desviaciones estándar y el 99.7% caerán dentro de tres desviaciones estándar.

Una de las razones por las que la distribución normal es tan importante y de uso común es porque muchas cantidades físicas, como la altura y el peso, tienen distribuciones casi normales. Debido a esto, muchas pruebas estadísticas están diseñadas para su uso con poblaciones distribuidas normalmente. Por lo tanto, dado que una cantidad en estudio exhibe una distribución normal, los investigadores pueden usar muchos métodos estadísticos confiables para hacer inferencias sobre la población basándose en muestras recolectadas.

Distribución uniforme continua
Una distribución uniforme continua es un tipo de distribución de probabilidad simétrica que tiene la siguiente función de densidad de probabilidad:

![Zih4KT0gXGJlZ2lue2Nhc2VzfSB7XGZyYWN7MX17Yi1hfX0sICYge2EgXGxlIHggXGxlIGJ9IFxcIHswfSwgJiB7XHRleHR7b3RoZXJ3aXNlfX0gXGVuZHtjYXNlc30_100](https://user-images.githubusercontent.com/95035101/198897926-b084d616-31b9-49b7-9f99-7d101c8d4970.svg)

A continuación se muestra una representación gráfica del pdf de una distribución uniforme continua.

![continuous-uniform-distribution](https://user-images.githubusercontent.com/95035101/198897932-a3d25cd2-ad64-4308-bdcb-a1bcd03244fc.png)

Una distribución aleatoria continua también se conoce como distribución rectangular debido al rectángulo formado, como se muestra en el área sombreada en la figura. A medida que aumenta el ancho del pdf, la densidad de cualquier valor dado disminuye. Además, dado que todas las funciones de densidad de probabilidad se integran a 1 en sus respectivos intervalos, la altura de la función de densidad de probabilidad disminuye a medida que aumenta su ancho. Las distribuciones continuas uniformes se pueden usar para describir experimentos en los que la variable aleatoria continua es simétrica y se encuentra dentro de un intervalo específico.

### Distribución de chi-cuadrado ###

La distribución chi-cuadrado es una de las distribuciones más utilizadas en estadística, particularmente para la prueba de hipótesis y la construcción de intervalos de confianza. El pdf para una distribución chi-cuadrado es

![Zih4KT0gXGJlZ2lue2Nhc2VzfSB7XGZyYWN7eF57XGZyYWN7a317Mn0tMX1lXntcZnJhY3steH17Mn19fXsyXntcZnJhY3trfXsyfX1cR2FtbWFcbGVmdChcZnJhY3trfXsyfVxyaWdodCl9fSwgJiB7eCBcZ2UgMH0gXFwgezB9LCAmIHtcdGV4dHtvdGhlcndpc2V9fSBcZW5ke2Nhc2VzfQ==_100](https://user-images.githubusercontent.com/95035101/198897965-3405d195-3562-410f-b59a-d9533d64f162.svg)

donde k son los grados de libertad y ![XEdhbW1hXGxlZnQoXGZyYWN7a317Mn1ccmlnaHQp_100](https://user-images.githubusercontent.com/95035101/198897978-bce6e78b-fb6f-41e8-b6c3-b4430197e5d2.svg)
 es la función gamma:
 
![XEdhbW1hKHgpID0gXGludF97MH1ee1xpbmZ0eX0gdF57eC0xfWVeey10fWR0_100](https://user-images.githubusercontent.com/95035101/198898000-26b4727b-364b-48a4-83a6-71f1d77e17b2.svg)

No siempre es necesario integrar el pdf de una distribución chi-cuadrado. Al igual que otras distribuciones de probabilidad, existen tablas que se pueden utilizar para determinar estadísticas importantes, como el valor p, que puede indicar si una estadística de prueba es estadísticamente significativa o no.


