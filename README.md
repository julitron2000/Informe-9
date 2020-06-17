# Informe N°3 ANÁLISIS DE N0D0S

AUTORES: DAVID HINOJOSA,
         JAVIER DELGADO,
         JULIO ROSERO.

## 1. PLANTEAMIENTO DEL PROBLEMA

Al momento de analizar circuitos, frecuentemente, se presentan casos en los que es indispensable aplicar un análisis por método de nodos , por lo que conocer y saber utilizar este método debe ser un requisito necesario e indispensable para realizar cualquier análisis de un circuito tanto en la práctica como en la teoría.

## 2. OBJETIVOS
-Comprobar experimentalmente el analisis de nodos
-Medir y registrar el voltaje en los nodos.
-Determinar el porcentaje de error entre el valor teorico y experimental.

## 3. MARCO TEÓRICO 
![image](https://user-images.githubusercontent.com/64505672/84841818-10b96080-b009-11ea-8c5f-862ff4ee8891.png)

Un nodo es el punto en donde se conectan diferentes elementos en un circuito, en el cual se puede medir el voltaje que cae en este punto, basándonos en la ley de corrientes Kirchhoff y la ley de Ohm.
### Método de Nodos

![image](https://user-images.githubusercontent.com/64505672/84841694-ac969c80-b008-11ea-88e9-abf614eb50b4.png)

El método de Nodos es un método utilizado para resolver cualquier tipo de circuitos.

![image](https://user-images.githubusercontent.com/64505672/84841751-db147780-b008-11ea-9d40-00c5b02e7e4f.png)

Los pasos para determinar la caida de voltaje en un nodo son:
1. Determinar las corrientes que entran y salen en cada nodo.
2. Aplique la LCK en cada uno de los n nodos. Use la ley de Ohm para expresar las corrientes en términos de los voltaje que caen en los elementos, considerando que la corriente sera igual a la diferencia de voltaje sobre la resistencia y considerando que el voltaje en tieera es cero.
3. Resuelva las n ecuaciones simultáneas resultantes para obtener el voltaje en cada nodo.

## 4. DIAGRAMAS

## 5. LISTA DE COMPONENTES
A. Fuente de Voltaje de C.D.


![chrome_FxjHlWp3kM](https://user-images.githubusercontent.com/66037763/84236034-96df1f80-aabc-11ea-9159-3d2235bc315b.png)


B. Multímetro Digital

![chrome_1E7H2m0GOE](https://user-images.githubusercontent.com/66037763/84236069-a6f6ff00-aabc-11ea-90f8-49d128847e17.png)


C. Resistor de 820 Ω


![chrome_H59RekD0Sn](https://user-images.githubusercontent.com/66037763/84236097-b4ac8480-aabc-11ea-88e9-0930cd8a6151.png)


D. Resistor de 390 Ω


![chrome_nYj42XTcAA](https://user-images.githubusercontent.com/66037763/84236121-bc6c2900-aabc-11ea-9052-20d1e126c649.png)


E. Resistor de 1 kΩ


![chrome_jPVmQCB5dn](https://user-images.githubusercontent.com/66037763/84236149-cbeb7200-aabc-11ea-96d9-4b01e8f8ef81.png)


F. Resistor de 1.2 kΩ


![chrome_RgP3H68Ui2](https://user-images.githubusercontent.com/66037763/84236162-d60d7080-aabc-11ea-864d-536485900f86.png)


G. Resistor de 2.2 kΩ

![chrome_u6waqAZiNN](https://user-images.githubusercontent.com/66037763/84236192-e0c80580-aabc-11ea-9767-487481f78259.png)


H. Protoboard

![chrome_gnkRWUT4Si](https://user-images.githubusercontent.com/66037763/84236208-e9b8d700-aabc-11ea-9985-2e94ef9d6adb.png)


## 6. DESCRIPCION DE PREREQUISITOS Y CONFIGURACION

## 7. CRONOGRAMA
![0006](https://user-images.githubusercontent.com/66037557/84841262-70167100-b007-11ea-9910-d1d3f00f408a.png)


## 8.CONCLUSIONES
-Se concluyó gracias al análisis nodos, el valor analítico de los voltajes en el nodo1=2.82028 y nodo2=4.80195  .

-se logró comprobar que tanto los voltajes calculados en los respectivos nodos como los medidos poseen un bajo grado de error, siendo el error en el nodo1=0.00993% y en el nodo2=0.042%.

-se concluye que la razón por la que el error es muy pequeño se debe a que el simulador posee una incertidumbre casi nula, a diferencia de la vida real en la que la que las tolerancias de nuestras resistencias pueden variar.

## 9.RECOMENDACIONES
-Tener cuidado al tomar la medida de caída de tensión en nuestros nodos, podemos obtener valores erróneos.

-Armar el circuito de una forma didáctica para que todos puedan entender el funcionamiento del mismo.

-Utilizar la mayor cantidad de decimales posibles en el cálculo, para sacar un grado de error mas significativo.

## 10. BIBLIOGRAFÍA

-M.Sadiku, C.Alexander, Fundamentos de circuitos eléctricos (3ra Edición), 2004.

-Allan, H.Robbins, Análisis de Circuitos. Teoría y práctica(4ta Edición), 2008.
