UNIVERSIDAD DE LAS FUERZAS ARMADAS - ESPE

![](https://github.com/BraddJCJ/Informe5_Jerez_Sangoquiza_Zambrano/blob/master/img/Logo_ESPE.png)

¨Práctica de Laboratorio N°6 Teorema de la maxima transferencia de potencia¨  
¨Fundamentos de Circuitos Eléctricos¨  
Integrantes: Jerez Bradd; Sangoquiza Andrés; Flores de Valgas Jonathan.  
NRC: 8702   
Fecha: 2020 - 07 - 22  

1.- PLANTEAMIENTO DEL PROBLEMA: 

¿Qué efecto existe en el rediseño de un circuito, implementado para el cálculo de la potencia al saber que el mismo posee pérdidas internas? ¿Qué relación existe entre el cálculo de potencia máxima y el Teorema de Thévenin? ¿Es posible determinar el valor de Potencia [W] de un circuito si uno de sus elementos resulta en una carga variable?


2.- OBJETIVOS:

* General: 

Comprobar experimentalmente el Teorema de la Máxima Transferencia de Potencia.

* Específico:

Determinación de la resistencia de carga que permitirá transferir la potencia máxima.
Calcular los valores de potencia máxima del circuito.
Identificar que valores de RL resultan en el cálculo de la Potencia Máxima.


3.- MARCO TEORICO:

Para el análisis de potencia máxima de un circuito lineal, se debe conocer los valores de VTh, RL y RTh, puesto que su relación para el cálculo de potencia nos permitirá obtener fácilmente el valor de potencia máxima, pero existen algunas cuestiones a tener en cuenta.

En presencia de un circuito con una carga RL (variable), siempre es recomendable rediseñar el circuito aplicando el Teorema de Th\'evenin. Este diseño es muy usado para suministrar de potencia a la carga RL. Además, es considerable que el rediseño de este circuito puede generar pérdidas significativas de potencia puesto que la supresión de potencia en los componentes tiene una influencia directa en comparación con el circuito original. RL al ser variable estará comprendida entre valores de cero a infinito. Cabe mencionar, que a valores máximos de RL la potencia será baja, de igual forma sucede si la carga Rl es mínima.

![](https://github.com/JonathanFloresDeValgas/InformeN6_FloresDeValgas_Jerez_Sangoquiza/blob/master/img/Sadiku%203%20Ed.pdf%20-%20Adobe%20Acrobat%20Reader%20DC%2021_07_2020%2022_35_34.png)

Si la carga RL tiene una variación constante, se le puede atribuir la siguiente fórmula, de modo que sea lo más oportuno el cálculo de la potencia “No Máxima” en un circuito de Thevenin.

![](https://github.com/JonathanFloresDeValgas/InformeN6_FloresDeValgas_Jerez_Sangoquiza/blob/master/img/Sadiku%203%20Ed.pdf%20-%20Adobe%20Acrobat%20Reader%20DC%2021_07_2020%2020_43_44.png)

Para alcanzar una “Máxima” potencia, RL debe ser igual que RTh, por lo tanto, en el cáalculo de potencia máxima se obtendría la fórmula: 

![](https://github.com/JonathanFloresDeValgas/InformeN6_FloresDeValgas_Jerez_Sangoquiza/blob/master/img/Sadiku%203%20Ed.pdf%20-%20Adobe%20Acrobat%20Reader%20DC%2021_07_2020%2021_01_26.png)

4.- DIAGRAMAS:

Circuito designado:

![](https://github.com/JonathanFloresDeValgas/InformeN6_FloresDeValgas_Jerez_Sangoquiza/blob/master/img/CN6.PNG)

Circuito implementado:

![](https://github.com/JonathanFloresDeValgas/InformeN6_FloresDeValgas_Jerez_Sangoquiza/blob/master/img/DiagramaN6.png)

5.- LISTA DE COMPONENTES:

![](https://github.com/JonathanFloresDeValgas/InformeN6_FloresDeValgas_Jerez_Sangoquiza/blob/master/img/Comp.PNG)
 
6.- CONCLUSIONES:

El cálculo de potencia por el método de Thevenin no es precisamente “Potencia Máxima” puesto que dependerá de los valores de la carga (RL) con respecto a la resistencia de Thevenin (RTh). 

Tras los cálculos realizados, se concluye que la potencia máxima de RL llega a ser aquella que posee un valor más próximo al valor de RTh. Puesto que la que más se acerca a este valor es la carga de 1000Ohm con una diferencia menor que el resto de cargas, entonces esta tiene una Potencia máxima.


7.- RECOMENDACIONES:

Se recomienda tener cuidado con los prefijos para cada unidad que perjudiquen y distorsionen los resultados en los cálculos de potencia. Además, se debe analizar la diferencia entre los valores RTh y RL antes de realizar los cálculos, puesto que los resultados deberán estar a corde al análisis planteado. Se recomienda tener muy en cuenta no todas las potencias calculadas aplicando el Teorema de Thévenin son netamente Máximas.

8.- CRONOGRAMA:

![](https://github.com/JonathanFloresDeValgas/InformeN6_FloresDeValgas_Jerez_Sangoquiza/blob/master/img/Cronograma.0.png)

9.- BIBLIOGRAFIA
 
 - Sadiku Matthew N. (2006). Fundamentos de Circuitos Eléctricos. McGraw-Hill Interamericana. México D. F.


 10.-ANEXOS:
 
 ![](https://github.com/JonathanFloresDeValgas/InformeN6_FloresDeValgas_Jerez_Sangoquiza/blob/master/Hojas%20T%C3%A9cnicas/Analisis%20de%20Resultados2.png)
 
 ![](https://github.com/JonathanFloresDeValgas/InformeN6_FloresDeValgas_Jerez_Sangoquiza/blob/master/Hojas%20T%C3%A9cnicas/Analisis%20de%20Resultados3.png)
 
 ![](https://github.com/JonathanFloresDeValgas/InformeN6_FloresDeValgas_Jerez_Sangoquiza/blob/master/Hojas%20T%C3%A9cnicas/Analisis%20de%20Resultados%204.png)
 
 ![](https://github.com/JonathanFloresDeValgas/InformeN6_FloresDeValgas_Jerez_Sangoquiza/blob/master/Hojas%20T%C3%A9cnicas/Analisis%20de%20Resultados5.png)
 
 ![](https://github.com/JonathanFloresDeValgas/InformeN6_FloresDeValgas_Jerez_Sangoquiza/blob/master/Hojas%20T%C3%A9cnicas/Analisis%20de%20Resultados6.png)
 
