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

Un operador operacional es un elemento activo de circuitos de suma importancia por lo que es común encontrarlos en diseños prácticos de circuitos a causa de su versatilidad, bajo costo, facilidad de uso y grato manejo.

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
Lo


Se pueden hacer diferentes configuraciones en los amplificadores para que cumplan determinadas funciones. En la siguiente grafica recuperada de Sadiku(2004), podemos ver un resumen de las configuraciones más comunes y las funciones que cumplen respectivamente

![image](https://user-images.githubusercontent.com/64505672/91803299-91dbc900-ebf0-11ea-8536-73a8117e712f.png)




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
- Se puede concluir que en un circuito Dc los capacitores se comportan como circuitos abiertos y los inductores como cortocircuitos. Por otro lado en circuitos alimentados por corriente alterna se onservo que al existir una frecuencia diferente de 0 tanto el capacitor como elresistor se oponen al flujo de carriente, es decir que tienen una impedancia z.
- Al observar las primeras 3 tablas de datos llenadas, se puede concluir que en el caso de un circuito con capacitores, el voltaje disminuye mientras que la corriente aumenta, en el caso de inductores sucede el proceso inverso, esto a su vez está relacionado con la reactancia obtenida.
- Los errores tabulados en la tabla 4. son respecto a los voltajes rms en los dos tipos de circuitos (capacitivos e inductivos), se concluye que estos se encuentran en un rango aceptable y la razón principal de este error es por fallas realizadadas en los cálculos (consideración de decimales). 

## 9.RECOMENDACIONES
- Utilizar un simulador mas completo que tinker cad.

- A la hora de medir la amplitud de la onda senoidal medir con cuidado para reducir el error.

- Revisar previamente el uso del osciloscopio para no cometer errores.

## 10. BIBLIOGRAFÍA

- M.Sadiku, C.Alexander, Fundamentos de circuitos eléctricos (3ra Edición), 2004.

- Allan, H.Robbins, Análisis de Circuitos. Teoría y práctica(4ta Edición), 2008.
