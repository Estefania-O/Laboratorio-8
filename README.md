# Laboratorio-8

## INDUCTOR Y CAPACITADOR

**1. OBJETIVO**

Objetivo General

•	Identificar los conceptos más importantes que definen a los inductores y capacitores, para ampliar nuestro conocimiento y sobretodo que nuestro entendimiento sea mas profundo.

Objetivos Específicos

•	Conocer e investigar que son los capacitores e inductores para saber sus aplicaciones, características y métodos de resolución.

•	Calcular su método de resolución de los capacitores e inductores en serie y paralelo.

**2. MARCO TEÓRICO**

![.](https://github.com/Estefania-O/Laboratorio-8/blob/main/img./Mapa_Lab%208.png)

**3. DIAGRAMAS**

Circuitos con capacitadore y bobinas.

![.](https://github.com/Estefania-O/Laboratorio-8/blob/main/img./Circuitos_Gu%C3%ADa%208.png)

Circuito con capacitadores implementado con la ayuda de la herramienta Proteus.

![.](https://github.com/Estefania-O/Laboratorio-8/blob/main/img./Circuito_capacitadores.png)

Medición del voltaje (Vo) con el uso del osciloscopio en el circuito con capacitadores.

![.](https://github.com/Estefania-O/Laboratorio-8/blob/main/img./Medicion_V0_Osciloscopio.png)

Medición del voltaje (Vo)con el uso del voltímetro en el circuito con capacitadores.

![.](https://github.com/Estefania-O/Laboratorio-8/blob/main/img./Medicion_V0_Voltimetro.png)

Medición de la corriente en la resistencia del circuito con capacitadores.

![.](https://github.com/Estefania-O/Laboratorio-8/blob/main/img./Medicion_Corriente_Resistencia.png)

Circuito con bobina implementado con las ayuda de la herramienta Proteus.

![.](https://github.com/Estefania-O/Laboratorio-8/blob/main/img./Circuito_bobinas.png)

Medición del voltaje (Vo) con el uso del osciloscopio en el circuito con bobina.

![.](https://github.com/Estefania-O/Laboratorio-8/blob/main/img./Medicion_Vo_Osciloscopio.png)

Medición del voltaje (Vo) con el uso del voltímetro en el circuito con bobina.

![.](https://github.com/Estefania-O/Laboratorio-8/blob/main/img./Medicion_Vo_Osciloscopio.png)

Medición de la corriente en la resistencia del circuito con bobina.

![.](https://github.com/Estefania-O/Laboratorio-8/blob/main/img./Medicion_Corriente_Resistencia2.png)

**4. COMPONENTES**

|**CANTIDAD**|**ELEMENTO**|
|:----:|:----:|
|1|Generador de señales|
|1|Osciloscopio|
|1|Protoboard|
|1|Multímetro|
|1|Cables conductores|
|1|Resistor de 100 Ω|
|2|Capacitador de 10 μF|
|2|Bobina de 100 mH|

**5. EXPLICACIÓN**

Para la primera simulación se utilizo la herramienta Proteus para la implementación del circuito con capacitadores, con las ayuda de un osciloscopio, voltimetro y un amperímetro se pudo dar lectura de los valores de voltaje y corriente que  se detallan en la siguiente tabla:

**Tabla I.** Datos de lectura circuito 1.

|**frecuencia (Hz)**|**V0 Oscilocopio**|**V0 Multimetro**|**I Resistencia (mA)**|
|:---:|:----:|:---:|:----:|
|0|0|0|0|
|10|9.90|7.04|8.88|
|50|8.40|6.00|37.7|
|100|6.20|4.38|55.4|
|500|1.55|1.10|69.8|
|1000|0.78|0.55|70.5|

Para la segunda simulacion se implemento el mismo circuito cambiando los capacitadores por unas bobinas o inductores, con la ayuda de un osciloscopio, voltimetro y un amperímetro se pudo dar lectura de los valores de voltaje y corriente que se detallan en la siguiente tabla:

**Tabla II.** Datos  de lectura circuito 2.
|**frecuencia (Hz)**|**V0 Oscilocopio**|**V0 Multimetro**|**I Resistencia (mA)**|
|:---:|:----:|:---:|:----:|
|0|0|0|0|
|10|0.3175|0.23|70.4|
|50|1.57|1.11|69.9|
|100|3.02|2.14|67.5|
|500|8.45|5.98|37.6|
|1000|9.5|6.74|21.2|

1.- ¿Cómo se comportan la bobina y el capacitor en corriente continua (cero Hz)?

En la fase estable, el fenómeno descrito en la curva de carga del condensador continuará ocurriendo hasta que se estabilice y se convierta en una fase continua. En esta etapa, la intensidad de la corriente que fluye a través del condensador es igual a cero, por lo que se considera un "circuito abierto". En los inductores al ser la corriente constante la caída de tensión sobre ellos es igual a cero, por lo que lo interpretamos como simplemente un “cable” en el circuito.

2.- ¿Cómo se comportan la bobina y el capacitor en corriente alterna?

El comportamiento de los capacitores en corriente alterna dependerá de la función que describa su comportamiento en un intervalo de tiempo definido. Entonces, el capacitor se puede representar como otro componente pasivo en el circuito.  Al  existir  una  variación  de  la  corriente  en  un  circuito  de  corriente  alterna  es  posible conocer los valores que pueden tomar la corriente y la caída de tensión por medio de las funciones que describan a estas variables en un intervalo de tiempo definido. 
Entonces se  puede representar al inductor como un elemento pasivo más en el circuito.

3.- ¿Qué cree usted que ocurriría con el voltaje Vo y la corriente de la resistencia en los circuitos analizados en esta práctica, si se utilizan dos bobinas o dos capacitores de valores distintos?

Cambiará según cuánto cambie la impedancia Si la impedancia capacitiva o resistiva se vuelve más pequeña, la caída de voltaje Vo será más pequeña  y si la impedancia capacitiva o resistiva aumenta, la caída de voltaje Vo teóricamente será mayor.

4.- ¿Qué son los valores eficaces de voltaje y corriente?

Los valores efectivos de corriente y voltaje son valores equivalentes en corriente continua, es decir, tienen el mismo comportamiento con respecto a la potencia suministrada en el circuito.

**6. CONCLUSIONES**

•	Si la frecuencia baja, la reactancia aumenta es fundamental para evitar el paso de corriente continua

•	Los capacitores e inductores se utilizan mucho en la electrónica y en otros campos, además de encontrarse en la mayoría de los circuitos eléctricos. 

•	Son componentes pasivos, y el capacitor es sustentado por campo eléctrico mientras que el inductor es sustentado por un campo magnético


**7. BIBLIOGRAFÍA**

**8. ANEXOS**
