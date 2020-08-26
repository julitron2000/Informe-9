# Informe N°8 INDUCTOR Y CAPACITOR

AUTORES: DAVID HINOJOSA,
         JAVIER DELGADO,
         JULIO ROSERO.

## 1. PLANTEAMIENTO DEL PROBLEMA

En los circuitos eléctricos existen elementos llamados capacitores e inductores, son usados en practicamaente todos los circuitos de los diferentes electrodomesticos, por ello es importante aprender a realizar las mediciones de voltaje y corriente con estos elementos.

## 2. OBJETIVOS
### Objetivo General
- Analizar el comportamiento de la bobina y el capacitor en circuitos
### Objetivo Específico
- Verificar el comportamiento de la bobina y el capacitor en circuitos DC.
- Verificar el comportamiento de la bobina y el capacitor en circuitos AC.
- Verificar las combinaciones serie y paralelo de bobinas y capacitores.
- Familiarizarse con el uso de instrumentos de medida

## 3. MARCO TEÓRICO 
Esta práctica se centra en la observación del comportamiento de ciertos elementos pasivos que encontramos en circuitos eléctricos, llamados capacitores e inductores, que tienen la capacidad de almacenar energia eléctrica, a diferencia de los resistores que se oponian al paso de la corriente (dispación de energia).

### Capacitores
Según Sadiku (2004) "Un capacitor es un elemento pasivo diseñado para almacenar energía en su campo eléctrico. Junto con los resistores, los componentes eléctricos más comunes son los capacitores, los cuales son de amplio uso en electrónica, comunicaciones, computadoras y sistemas de potencia" p(216).

![image](https://user-images.githubusercontent.com/64505672/91253138-c64d1200-e724-11ea-9aec-9409a02197e4.png)

Cuando una fuente de tensión v se conecta al capacitor, deposita una carga positiva q en una placa y una carga negativa q en la otra. Se dice que el capacitor almacena la carga eléctrica. El monto de carga almacenada, representado por q, es directamente proporcional a la tensión aplicada v de modo que

![image](https://user-images.githubusercontent.com/64505672/91253412-5a1ede00-e725-11ea-8874-683160b95678.png)

donde C, la constante de proporcionalidad, se conoce como la capacitancia del capacitor y se mide en faradios. Un faradio es 1 columbio/voltio.
 
La corriente que pasa por un capacitor se lo calcula con la siguiente formula 

![image](https://user-images.githubusercontent.com/64505672/91253689-09f44b80-e726-11ea-9482-68a1c739b216.png)

Asi mismo se puede determinar el voltaje en funcion de la corriente

![image](https://user-images.githubusercontent.com/64505672/91253819-5e97c680-e726-11ea-98b0-b179faee20a9.png)

Una manera mas fácil de visualizar el comportamiento que de un capacitor es con la siguiente grafica

![image](https://user-images.githubusercontent.com/64505672/91254333-ba168400-e727-11ea-8c53-6f18a922f677.png)

Con respecto a las ecuaciones se puede concluir que: 
- Para que un capacitor conduzca corriente su voltaje debe variar en funcion del tiempo .
- La tensión en un capacitor no puede cambiar abruptamente, ya que debe ser continua.

La capacitancia equivalente de un cierto número de capacitores conectados en paralelo se lo calcula asi

![image](https://user-images.githubusercontent.com/64505672/91254482-25605600-e728-11ea-9c81-21e2cdbd0352.png)

La capacitancia equivalente de un cierto número de capacitores conectados en serie se lo calcula asi

![image](https://user-images.githubusercontent.com/64505672/91254549-4c1e8c80-e728-11ea-9ae8-7a408d1343a6.png)

La corriente que pasa el capacitor se calcula asi

![image](https://user-images.githubusercontent.com/64505672/91255505-8ab54680-e72a-11ea-870c-15877002e459.png)

### Inductores

Según Sadiku (2004) "Un inductor es un elemento pasivo diseñado para almacenar energía en su campo magnético. Los inductores encuentran numerosas aplicaciones en sistemas
electrónicos y de potencia" 

![image](https://user-images.githubusercontent.com/64505672/91256161-38752500-e72c-11ea-8b6a-c517677c85e1.png)

Para encontrar el volataje que pasa por un inductor se tiene la siguiente fórmula

![image](https://user-images.githubusercontent.com/64505672/91255009-65740880-e729-11ea-933d-25e93c26edba.png)

donde L es la constante de proporcionalidad, llamada inductancia del inductor y se llama henry, donde 1 henry es igual a 1 voltio-segundo por amperio.
Para entender mejor el comportamiento de un inductor se presenta el siguiente gráfico.

![image](https://user-images.githubusercontent.com/64505672/91255820-69a12580-e72b-11ea-97fc-451027705f00.png)

Con respecto a las ecuaciones anteirores se puede concluir que
- La tensión en un inductor es de cero cuando la corriente es constante.
- La corriente que circula por un inductor no puede cambiar instantáneamente, ya que se opone a cambios abruptos de corriente.

La inductancia equivalente de un numero determinado de inductores conectados en paralelos se calcula asi

![image](https://user-images.githubusercontent.com/64505672/91256288-90ac2700-e72c-11ea-8677-ccbedcab0546.png)

La inductancia equivalente de un numero determinado de inductores conectados en serie se calcula asi

![image](https://user-images.githubusercontent.com/64505672/91256328-afaab900-e72c-11ea-9e35-1d5bb99a7b1f.png)

Para resumir la información, Sadiku (2004) nos facilita la siguiente tabla que incluye informacion de los resitores

![image](https://user-images.githubusercontent.com/64505672/91256498-1a5bf480-e72d-11ea-9808-46bfea0b6d5b.png)



## 4. DIAGRAMAS


![chrome_jj2CMayvW6](https://user-images.githubusercontent.com/66037763/91268424-ef789d00-e73a-11ea-8903-91b9b250db91.png)


Primer circuito, se tiene una fuente de voltaje AC y un par de capacitores de 10 μF en paralelo. De igual manera debe colocar el osciloscipio en paralelo al igual que el multímetro cuando se calcule voltaje. En el caso de medir corriente se coloca el multímetro en serie. 


![chrome_LmmTjpbTyf](https://user-images.githubusercontent.com/66037763/91268391-e12a8100-e73a-11ea-8d38-57a0bebe17d9.png)


Para el segundo circuito, se repite el proceso antes mencionado, la diferencia es que los componentes son un par de inductores de 100 mH. A continuación, ejemplos de los circuitos simulados con su respectiva señal en el osciloscopio:

CONDUCTORES

En 50 Hz:

![image](https://user-images.githubusercontent.com/66037763/91269579-ff917c00-e73c-11ea-91ab-34377e1c3ab6.png)





![image](https://user-images.githubusercontent.com/66037763/91269389-a75a7a00-e73c-11ea-971b-de2597fe50ef.png)



CAPACITORES

En 50 Hz:

![image](https://user-images.githubusercontent.com/66037763/91270337-18e6f800-e73e-11ea-8019-84a06952a325.png)




![image](https://user-images.githubusercontent.com/66037763/91270392-2bf9c800-e73e-11ea-84d4-a0235c081321.png)



## 5. LISTA DE COMPONENTES
A. Generador de Señales


![chrome_LUEFWCOVi0](https://user-images.githubusercontent.com/66037763/90581763-a1d7bf80-e191-11ea-9e2b-1254612c8019.png)



B. Multímetros Digitales



![Multimetro](https://user-images.githubusercontent.com/66037763/86204443-252f4a00-bb2d-11ea-8508-0edf4c96af71.png)



C. Resistor de 100 Ω


![chrome_YBCCxA2dTh](https://user-images.githubusercontent.com/66037763/91255172-cdc2ea00-e729-11ea-8fde-001f1ab47c6a.png)



C. Protoboard


![chrome_gnkRWUT4Si](https://user-images.githubusercontent.com/66037763/84236208-e9b8d700-aabc-11ea-9985-2e94ef9d6adb.png)




D. Oscilosciopio



![chrome_p6hVOC777I](https://user-images.githubusercontent.com/66037763/90581876-f2e7b380-e191-11ea-8fed-2af53bdc9daa.png)




E. Fuente DC



![chrome_FxjHlWp3kM](https://user-images.githubusercontent.com/66037763/84236034-96df1f80-aabc-11ea-9159-3d2235bc315b.png)



F. Capacitores


![chrome_gYijK3iWZh](https://user-images.githubusercontent.com/66037763/91255322-28f4dc80-e72a-11ea-99b1-98898211f286.png)



G. Bobinas/inductores


![chrome_KUfo7uFUon](https://user-images.githubusercontent.com/66037763/91255513-8db03700-e72a-11ea-8d4b-121f8973c0c9.png)



## 6. DESCRIPCION DE PREREQUISITOS Y CONFIGURACION


ANALISIS DE RESULTADOS

1.
Tabla 1. Datos obtenidos del circuito con capacitancia
| PARÁMETRO ELÉCTRICO    |    0        |      10          |     50          |     100           |      500         |        1000            |
|           ---          |     ---     |       ---        |    ---          |    ---            |    ---           |         ---            |     
|       Vp               |    0        |      9.809 V     |     8.338 V     |     6.090 V       |     1.880 V      |       764.903 mV       |            
|       Vo               |    0        |      7.014 V     |     5.965 V     |     4.368 V       |     1.097 V      |       553.740 mV       |              
|      Corriente         |    0        |      8.929 mA    |     37.968 mA   |     55.604 mA     |     69.851 mA    |       70.493 mA        |              
 
Tabla 2. Datos obtenidos del circuito con inductancia
| PARÁMETRO ELÉCTRICO |    0       |      10     |     50     |     100      |      500     |    1000      |
|           ---       |     ---    |       ---   |    ---     |    ---       |    ---       |     ---      |     
|       Vp            |      0     |  317.580 mV |  1.556 V   |   3.006 V    |   8.407 V    |  9.108 V     |            
|       Vo            |      0     |  224.926 mV |  1.111 V   |   2.144 V    |   5.987 V    |  6.746 V     |              
|      Corriente      |      0     |  70.673 mA  |  69.831 mA |  67.379 mA   |   37.622 mA  |   21.196 mA  |   

Se puede observar, en la tabla 1. que es referente al circuito con capacitancia, que mientras la frecuencia aumenta el voltaje disminuye y la corriente aumenta proporcionalmente. Por otro lado en los datos de la tabla 2. referente al circuito con inductores, mientras la frecuencia aumenta tambien lo hace su voltaje, pero la corriente disminuye. De tal manera que la diferencia principal es en la proporcionalidad de la frecuencia con sus parámetros eléctricos; en el caso de los capacitores, el voltaje es inversamente proporcional pero la corriente es directa, y en el caso de los inductores el voltaje es directamente proporcional y la corriente inversa. 

2. 

Tabla 3. Reactancias
| PARÁMETRO ELÉCTRICO |    0       |      10     |     50     |     100      |      500     |    1000      |
|           ---       |     ---    |       ---   |    ---     |    ---       |    ---       |     ---      |     
|         X (C)       |    0       | 785.53 Ω    |  157.11 Ω  |   78.56 Ω    |   15.7 Ω     |    7.86 Ω    |   
|         X (L)       |    0       | 3.18 Ω      |   15.91 Ω  |   31.82 Ω    |  159.14 Ω    |   318.27 Ω   |

Inductancia equivalente = 50 mH

Capacitancia equivalente = 20 uF

Es visible en la tabla 3. que la reactancia capacitiva disminuye mientras la frecuencia aumenta, por otro lado la reactancia inductiva aumenta siguiendo la misma relación. Esto puede explicar la razón de cambio del voltaje en los circuitos vistos en la tabla 1. y 2. 

PREGUNTAS


1.- Justifique los errores cometidos en las mediciones.

**Cálculo de error**
Se utiliza el parámetro de voltaje para hacer el respectivo análisis de errores:

Tabla 4. Errores de Vo
| PARÁMETRO ELÉCTRICO |    10      |     50      |     100    |      500     |    1000      |
|           ---       |     ---    |       ---   |    ---     |    ---       |    ---       |         
|        E %Vo (C)    | 1.1119 %   | 1.1591 %    | 1.4129 %   |  2.1181 %    |    2.3245 %  |           
|        E %Vo (L)    | 0.1613 %   | 0.9668 %    | 0.8599 %   |  0.7074 %    |    4.5311 %  |           

2.- ¿Cómo se comportan la bobina y el capacitor en corriente continua (cero Hz)?

Cuando se tiene capacitores, en corriente contínua se considera un circuito abierto donde estén ubicados y es por esto que resulta un voltaje 0, en el caso de los inductores se considera un corto circuito, es decir que se considera un alambre sin impedancia (continúa en serie) y esta la razón por la que el multímetro mide 0 en este segmento.

3.- ¿Cómo se comportan la bobina y el capacitor en corriente alterna?

En corriente alterna, existe una frecuencia diferente a 0 por lo que tanto el capacitor como la bobina van a tener una impedancia que es equivalente a la resistencia en DC, por lo que ambos actúan de forma resistiva a la corriente en AC. 

4.- ¿Qué cree usted que ocurriría con el voltaje 𝑉𝑜 y la corriente de la resistencia en los
circuitos analizados en esta práctica, si se utilizan dos bobinas o dos capacitores de valores
distintos?

Los valores de corriente y voltaje cambiarían, sin embargo su relación proporcional al cambio de frecuencia se mantiene ya que esto es característico del elemento e independiente de su magnitud capacitiva o inductiva. 

5.- ¿Qué son los valores eficaces de voltaje y corriente?

Son los valores otorgados por el multímetro, basicamente son valores equivalentes a los de corriente continua de una forma de onda en corriente alterna.


## 7. CRONOGRAMA
![diagrama](https://user-images.githubusercontent.com/66037557/91257840-7f651980-e730-11ea-89ca-69b2c22909cf.png)


## 8.CONCLUSIONES
-
- Al observar las primeras 3 tablas de datos llenadas, se puede concluir que en el caso de un circuito con capacitores, el voltaje disminuye mientras que la corriente aumenta, en el caso de inductores sucede el proceso inverso, esto a su vez está relacionado con la reactancia obtenida.
- Los errores tabulados en la tabla 4. son respecto a los voltajes rms en los dos tipos de circuitos (capacitivos e inductivos), se concluye que estos se encuentran en un rango aceptable y la razón principal de este error es por fallas realizadadas en los cálculos (consideración de decimales). 

## 9.RECOMENDACIONES
-Utilizar un simulador mas completo que tinker cad.

-A la hora de medir la amplitud de la onda senoidal medir con cuidado para reducir el error.

-Revisar previamente el uso del osciloscopio para no cometer errores.

## 10. BIBLIOGRAFÍA

-M.Sadiku, C.Alexander, Fundamentos de circuitos eléctricos (3ra Edición), 2004.

-Allan, H.Robbins, Análisis de Circuitos. Teoría y práctica(4ta Edición), 2008.
