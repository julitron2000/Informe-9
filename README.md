# Informe N°9 Amplificador Operacional

AUTORES: DAVID HINOJOSA,
         JAVIER DELGADO,
         JULIO ROSERO.

## 1. PLANTEAMIENTO DEL PROBLEMA

El amplificador operacional es un componente activo que podemos encontrar en los circuitos eléctricos y además es uno de de los componentes de la instrumentación electrónica moderna. Por lo tanto, dominar sus aspectos fundamentales es decisivo para cualquier aplicación práctica de circuitos electrónicos.

## 2. OBJETIVOS
### Objetivo General
- Analizar el comportamiento de los amplificadores operacionales en circuitos eléctricos
### Objetivo Específico
- Verificar el principio de funcionamiento de un amplificador operacional.
- Analizar algunas aplicaciones básicas con el amplificador operacional.
- Familiarizarse con el uso de instrumentos de medida.

## 3. MARCO TEÓRICO 

Amplificadores Operacionales

Un amplificador operacional es un elemento activo de circuitos de suma importancia por lo que es común encontrarlos en diseños prácticos de circuitos a causa de su versatilidad, bajo costo, facilidad de uso y grato manejo.

Sadiku (2004) define al amplificador operacional:

"El amplificador operacional es una unidad electrónica que se comporta como una fuente de tensión controlada por tensión, es un elemento de circuitos activo diseñado para realizar operaciones matemáticas de suma, resta, multiplicación, división, diferenciación e integración" pag(176).

Un amplificador operacional esta compuesto internamente por un gran número de resistores, capacitores, inductores, transistores y diodos. Normalmente tiene 8 terminales en los cuales se especifica una funcion para cada terminal. En el siguiente grafico se puede observar la funcion de las terminales y su representacion en los circuitos en la derecha

![image](https://user-images.githubusercontent.com/64505672/91800362-6fe14700-ebee-11ea-884a-a63c5d616ba7.png)

Los terminales importantes a considerar en este nivel de estudio son los siguientes.
- Terminal 2: Entrada inversora
- Terminal 3: Entrada no inversora
- Terminal 4: Suministro de potencia negativa V-
- Terminal 6: Salida
- Terminal 7: Suministro de potencia positiva V+

Consideramos que una entrada aplicada a la terminal no inversora aparecerá con la misma polaridad en la salida, mientras que una entrada aplicada a la terminal
inversora aparecerá invertida en la salida.
Se puede representar el circuito equivalente de un amplificador operacional de la siguiente manera

![image](https://user-images.githubusercontent.com/64505672/91807554-e59ae200-ebf1-11ea-85a9-5760ed5dcf0d.png)

donde v1 es la tensión entre la terminal inversora y tierra y v2 es la tensión entre la terminal no inversora y tierra. El amplificador operacional percibe la diferencia entre esas dos entradas, la multiplica por la ganancia A y provoca que la tensión resultante aparezca en la salida. Sadiku(2004)
Entonces la salida vo está dada por

![image](https://user-images.githubusercontent.com/64505672/91808508-27c42380-ebf2-11ea-9437-6470b938dbc2.png)


A se llama ganancia en tensión de lazo abierto, porque es la ganancia del amplificador operacional sin retroalimentación externa de la salida a la entrada. Se evidencia entonces que un amplificador operacional es un amplificador de alta ganancia con resistencia de entrada muy alta y baja resistencia de salida.
Los valores entre los que operan las variables de un amp op son

![image](https://user-images.githubusercontent.com/64505672/91809754-81c4e900-ebf2-11ea-8ab6-4a6562c9f8e5.png)

El concepto de retroalimentación es crucial para la comprensión de los circuitos de amplificadores operacionales. Una retroalimentación negativa se obtiene cuando la salida se retroalimenta a la terminal inversora del amplificador operacional. Cuando hay una vía de retroalimentación de la salida a la entrada, la proporción entre la tensión de salida y la tensión de entrada se llama ganancia de lazo cerrado. Como resultado de la retroalimentación negativa, es posible demostrar que la ganancia de lazo cerrado es casi insensible a la ganancia de lazo abierto A del amplificador operacional. Por esta razón se usan amplificadores operacionales en circuitos con trayectorias de retroalimentación.

Es importante recalcar que la tensión de salida depende de y está limitada por la tensión de alimentación. 

![image](https://user-images.githubusercontent.com/64505672/91810341-5393d900-ebf3-11ea-8bbe-043e85585b0b.png)

Se pueden hacer diferentes configuraciones en los amplificadores para que cumplan determinadas funciones. En la siguiente grafica recuperada de Sadiku(2004), podemos ver un resumen de las configuraciones más comunes y las funciones que cumplen respectivamente

![image](https://user-images.githubusercontent.com/64505672/91803299-91dbc900-ebf0-11ea-8536-73a8117e712f.png)

- Amplificador inversor: invierte la polaridad de la señal de entrada mientras la amplifica.
- Amplificador no inversor: es un circuito de amplificador operacional diseñado para suministrar una ganancia en tensión positiva.
- Amplificador sumador: es un circuito del amplificador operacional que combina varias entradas y produce una salida que es la suma ponderada de las entradas.
- Amplificador diferencial: es un dispositivo que amplifica la diferencia entre dos entradas pero rechaza toda señal común a las dos entradas.


## 4. DIAGRAMAS

![chrome_8faVvy1m9G](https://user-images.githubusercontent.com/66037763/91918072-622bd000-ec87-11ea-8570-2f34a4af41cb.png)


Circuito guía correspondiente al amplificador operacional lm 324 (caso 1). 


![chrome_d8NVr7VCJh](https://user-images.githubusercontent.com/66037763/91936596-c9f90f80-ecb5-11ea-8027-0fc62b1476cb.png)


Circuito guía correspondiente al amplificador operacional 741 (caso 2).


![chrome_giR5p4kna0](https://user-images.githubusercontent.com/66037763/91936600-cc5b6980-ecb5-11ea-9956-d540b39bc1cd.png)


Circuito guía correspondiente al aplificador operacional 741 con doble fuente alterna (caso 3).


![image](https://user-images.githubusercontent.com/66037763/91936649-e8f7a180-ecb5-11ea-8bfd-aa2173f87e20.png)


Circuito simulado con amplificador lm 324, caso 1, con osciloscopios conectados.


![image](https://user-images.githubusercontent.com/66037763/91936677-f7de5400-ecb5-11ea-9570-eb4ce0f01fb8.png)


Circuito simulado con amplificador 741, caso 2, con osciloscopios conectados.


![image](https://user-images.githubusercontent.com/66037763/91936714-07f63380-ecb6-11ea-855c-046ae4eec969.png)



Circuito simulado con amplificador 741, caso 3, con osciloscopios conectados.



## 5. LISTA DE COMPONENTES
A. Generador de Señales


![chrome_LUEFWCOVi0](https://user-images.githubusercontent.com/66037763/90581763-a1d7bf80-e191-11ea-9e2b-1254612c8019.png)



B. Resistores


![chrome_YBCCxA2dTh](https://user-images.githubusercontent.com/66037763/91255172-cdc2ea00-e729-11ea-8fde-001f1ab47c6a.png)



C. Protoboard


![chrome_gnkRWUT4Si](https://user-images.githubusercontent.com/66037763/84236208-e9b8d700-aabc-11ea-9985-2e94ef9d6adb.png)




D. Oscilosciopio



![chrome_p6hVOC777I](https://user-images.githubusercontent.com/66037763/90581876-f2e7b380-e191-11ea-8fed-2af53bdc9daa.png)




E. Fuente DC



![chrome_FxjHlWp3kM](https://user-images.githubusercontent.com/66037763/84236034-96df1f80-aabc-11ea-9159-3d2235bc315b.png)



F. Capacitores


![chrome_gYijK3iWZh](https://user-images.githubusercontent.com/66037763/91255322-28f4dc80-e72a-11ea-99b1-98898211f286.png)



G. Amplificador operacional (LM324J)


![multisim_ox32OV8e6p](https://user-images.githubusercontent.com/66037763/91929560-44b92f00-eca4-11ea-9045-cc660fae2ae5.png)


H. Amplificador operacional (741)


![multisim_V0KRjblbKU](https://user-images.githubusercontent.com/66037763/91929608-60243a00-eca4-11ea-9114-c8f56ccb13f8.png)



## 6. DESCRIPCION DE PREREQUISITOS Y CONFIGURACION

![image](https://user-images.githubusercontent.com/66037763/91950626-0df41080-ecc6-11ea-9220-3c84850a7444.png)



![image](https://user-images.githubusercontent.com/66037763/91932063-c57b2980-ecaa-11ea-99ab-04698445d64f.png)


Datasheet correspondiente al amplificador operacional LM324J, su función dentro de un circuito integrado 



![image](https://user-images.githubusercontent.com/66037763/91950812-1ba99600-ecc6-11ea-9d2d-087dc8570684.png)



![image](https://user-images.githubusercontent.com/66037763/91931689-c2cc0480-eca9-11ea-9260-d8f52e22c826.png)

Datasheet correspondiente al amplificador operacional 471, donde se menciona la función de sus pines.




ANÁLISIS DE RESULTADOS

1. Analice y compare las formas de onda obtenidas en la práctica con los resultados obtenidos en el trabajo preparatorio. Comente dicha comparación.

![image](https://user-images.githubusercontent.com/66037763/91930199-d1182180-eca5-11ea-91de-597a395c23fb.png)

Se observa en la imágen la forma de onda que toma la entrada y salida de tensión. El canal B corresponde a la entrada en el amplificador, y este valor es aproximádamente 
1V (voltaje entregado por la fuente) mientras que en el canal A, se observa el voltaje de salida, y es notable cuanto ha aumentado (una proporción de 4.3). A este circuito operacional se lo llama amplificador "inversor".

![image](https://user-images.githubusercontent.com/66037763/91935695-e1cf9400-ecb3-11ea-8dd9-71ce91befe13.png)

De igual manera, el canal B corresponde a la entrada de tensión al amplificador y el canal A de su salida. Sus valores son de 5 V y 13.12 V correspondientemente, donde se amplifica el valor en una proporción de 2.624. Es importante destacar la forma de la onda del voltaje de salida (13.12 V) en la cual toma una figura rectangular. A este anplificador operacional se lo llama "integrador".


![image](https://user-images.githubusercontent.com/66037763/91933818-679d1080-ecaf-11ea-942f-19aa378380e8.png)

Tanto en el canal B como en el C se observa una tensión aproximada de 1 V, las cuales entran al amplificador donde sale un voltaje de 8.2 V. La proporción de amplificación es de 8.2 (la mayor hasta ahora). En este circuito, los voltajes en paralelo se suman de tal manera que el voltaje de salida es mayor que en los otros voltajes. A este tipo de amplificador se lo llama de "suma". 

PREGUNTAS

1. Anote parámetros técnicos importantes de un amplificador operacional que deben ser tomados en cuenta al momento de utilizarlos en un proyecto.

-El rango máximo y mínimo con el que puede trabajar el amplificador respecto al voltaje de entrada. 

-El número de pines y la función de cada uno de estos.

-Rango de temperaturas, valores de seguridad máximos con los que puede trabajar el amplificador operacional.

-Consumo de potencia, potencia que requiere el amplificador o consumida por este.


2. Investigue las características de amplificadores operacionales distintos a los utilizados en esta práctica.

LM741

Este dispositivo también es de uso común por sus parámetros regulares (estándar) pero su principal función recae en su alta impedancia.

LM725

Parecido al antes mencionado, con la diferencia de que mejoran sus parámetros, sin embargo presenta una menor impedancia comparado al LM741

LF411

Convergen los dos antes mencionados, parámetros mejorados con una alta impedancia lo hacen un amplificador útil para ciertas funciones particulares.

NE5533

Utilizado principalmente para aplicaciones donde no se requiera alta precisión ya que presenta parámetros de baja calidad y una impdedancia muy baja.
 

3. Investigue otras aplicaciones con circuitos más complejos que utilizan amplificadores operacionales.

-Amplificador seguidor de tensión, en este amplificador el voltaje de salida va a ser igual al de entrada ya que no hay resistencias de retroalimentación en su salida.

-Amplificador de diferencia, amplifica la diferencia entre dos entradas pero rechaza toda señal común entre ellas.

Entre otras se encuentran: comparador, conversor de corriente a tensión, derivador ideal, función exponencial y logarítmica.

## 7. CRONOGRAMA
![cronograma](https://user-images.githubusercontent.com/66037557/91936145-e5afe600-ecb4-11ea-959b-38640a675e32.png)


## 8.CONCLUSIONES
- Se puede concluir que todos los amplificadores operacionales tiene una ganancia que depende del tipo de circuito que utilicemos, a execpcion del seguidor de tension debido a que el voltaje se mantiente constante mientras que la corriente disminuye.
- Se logró comprobar que al utilizar un amplificador operacional este amplia la onda notablemente en una proporcion directamente relacionada al circuito.
- Se observó que hay varios tipos de amplificadores operacionales que son muy utilizados para temas donde se requiera alta presición, pues con ellos se pueden realizar operaciones matemáticas como la diferenciación.

## 9.RECOMENDACIONES
- Utilizar un simulador mas completo que tinker cad.

- Tener mucha precaución cuando conectemos el circuito para no cometer errores en las mediciones.

## 10. BIBLIOGRAFÍA

- M.Sadiku, C.Alexander, Fundamentos de circuitos eléctricos (3ra Edición), 2004.

- Allan, H.Robbins, Análisis de Circuitos. Teoría y práctica(4ta Edición), 2008.
