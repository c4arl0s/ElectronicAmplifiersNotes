# ElectronicAmplifiersNotes
Electronic Amplifiers Notes, another of my favorite classes.
**ESTABILIDAD DEL PUNTO DE OPERACIÓN**

**ESTABILIDAD DEL PUNTO DE OPERACIÓN**

INTRODUCCIÓN
============

**Transistor:** Elemento de tres terminales (base, colector, emisor) que
sirve para amplificar una señal, este dispositivo es una fuente de
corriente controlada por corriente, su nombre se debe a la unión de dos
palabras: transferencia y resistor, o transferencia de resistencia, y
esto es debido a que la impedancia de entrada del transistor es baja, y
su impedancia de salida es alta.

![](media/image1.png){width="1.386111111111111in"
height="2.5034722222222223in"}

MODOS DE FUNCIONAMIENTO DEL TRANSISTOR
======================================

![](media/image2.png){width="6.135416666666667in"
height="3.401388888888889in"}

![](media/image3.png){width="6.13125in" height="3.423611111111111in"}

![](media/image4.png){width="6.132638888888889in"
height="3.448611111111111in"}

![](media/image5.png){width="6.13125in" height="3.18125in"}

Cuando este dispositivo se polariza en la región activa directa el flujo
de electrones “real” es del emisor al colector, es por esto que sus
terminales reciben estos nombres: el emisor “emite” electrones, mientras
que el “colector” los colecta:

![](media/image6.png){width="6.625in" height="1.8388888888888888in"}

El símbolo del transistor nos dice mucho acerca de cómo debe polarizarse
para situarse en la región activa directa, observe la flecha que existe
entre las terminales B-E, esta flecha nos indica que la terminal B debe
ser mas positiva que la E, es decir, la unión PN debe polarizarse en
directa, ahora observe las terminales B-C, la ausencia de la flecha nos
indica que la terminal B debe ser menos positiva que la C, es decir la
unión PN existente debe polarizarse en inversa. Una situación homóloga
pasa para los transistores PNP.

**DEFINICIONES UTILES PARA LA MATERIA**

**Polarizacion**: dar condiciones de corriente y voltaje en un circuito
eléctrico.

SENSIBILIDAD
============

Medida del cambio de alguna de las características de funcionamiento de
una red que se produce, por cambiar de valor uno o mas de sus elementos.

Utilidad:

-   Evalúa cambios en el funcionamiento de una red eléctrica en general.

-   Solo para cambios infinitesimales (%5, 10%)

Su definición matemática es como sigue:

Se lee: “sensibilidad de una función de red N(w) con respecto a un
parámetro x”

CIRCUITO DE POLARIZACION FIJA
=============================

![](media/image8.png){width="3.2444444444444445in" height="2.93125in"}

Si la relación es lineal, y las variaciones son pequeñas:

CALCULO DE FACTORES DE SENSIBILIDAD PARA POLARIZACION FIJA
----------------------------------------------------------

Es un factor que nos dice que tanto varía un parámetro del circuito.

  ------------------------------------------------------------------------------------ --

  ![](media/image20.wmf){width="1.2236111111111112in" height="0.6534722222222222in"}
  
  ![](media/image21.wmf){width="1.2236111111111112in" height="0.6534722222222222in"}
  ------------------------------------------------------------------------------------ --

CALCULO DE LA VARIACION DE ICQ PARA UNA POLARIZACION FIJA
---------------------------------------------------------

Sustituyendo:

CONCLUSIONES: 
--------------

La variación de la corriente de colector es grande, por lo que el
circuito es inestable con respecto a la variable betha.

CIRCUITO DE POLARIZACION POR TENSION DE EMISOR
==============================================

A continuación analizaremos el siguiente circuito, y haremos su análisis
de sensibilidad, y veremos como varia el punto de operación con la
resistencia RE en el emisor.

![](media/image38.png){width="4.097222222222222in"
height="3.813888888888889in"}

c

Si la relación es lineal, y las variaciones son pequeñas:

1.  CALCULO DE FACTORES DE SENSIBILIDAD DEL CIRCUITO DE POLARIZACION POR TENSIÓN DE EMISOR
    --------------------------------------------------------------------------------------

2.  CONCLUSIONES: 
    --------------

Vemos que el punto de operación es estable para esta configuración a
diferencia del de polarizacion fija.

ANALICE CIRCUITO DE POLARIZACION 
=================================

![](media/image58.png){width="5.129166666666666in" height="4.76875in"}

Tomando la expresión anterior y considerando que

Es decir:

Entonces:

y entonces se hace independiente de la constante beta.

CONCLUSIONES: 
--------------

Al realizar el cálculo para los valores de resistencia del circuito,
estos valores hacen que el transistor se polarice en la región de
saturación, por lo que hay que rediseñar el circuito, para poder
polarizarlo en la región activa directa.

**POLARIZADO EN REGION DE SATURACION**

VARIACIONES DE LA TENSION VBE E ICB0 RESPECTO A LA TEMPERATURA.
===============================================================

Calcular cuanto varia Icq si la temperatura varia de 25 \[°C\] a 150
\[°C\]

CIRCUITO DE POLARIZACION POR REALIMENTACION DE COLECTOR
=======================================================

Analizar el siguiente circuito.

![](media/image88.png){width="2.3472222222222223in"
height="4.0993055555555555in"}

--------------------------------------------1

--------------------------2

de Ibq:

CIRCUITO DE POLARIZACION POR EMISOR, POR DIVISOR DE TENSION, AUTOPOLARIZACION O UNIVERSAL.
==========================================================================================

![](media/image106.png){width="4.2868055555555555in"
height="3.2118055555555554in"}

-------------------------------------------(1)

----------------------------------------------(2)

----------------------------------------------(3)

\(2) en (1)

----------------------------------- (4)

----------------------- (5)

---------------------------------- (6)

6 en

![](media/image116.wmf){width="1.6388888888888888in"
height="0.2777777777777778in"} -------------------- (7)

**(3) en (1)**

![](media/image122.wmf){width="1.8611111111111112in"
height="0.2777777777777778in"} ----------------- (8)

CONCLUSIONES
------------

Este tipo de polarizacion tiene la ventaja de que la fuente en la malla
de entrada es diferente a la malla de salida, es decir, controlando las
resistencias R1 y R2 podemos variar la corriente en la base sin la
necesidad de otra fuente de tensión, además de que maneja las 3
configuraciones comunes del transistor, (base común, emisor común, y
colector común), además de que se puede compensar contra las variaciones
de bheta.

CORRIENTE DE COLECTOR EN FUNCION DE LA CORRIENTE DE PORTADORES MINORITARIOS PARA UNA POLARICION FIJA
====================================================================================================

![](media/image132.png){width="3.025in" height="3.0256944444444445in"}

Demostrar que del circuito anterior, la expresión de Icq en función de
los portadores minoritarios es:

Si despreciamos la corriente de portadores minoritarios:

Si tomamos en cuenta la corriente de portadores minoritarios :

![](media/image137.wmf){width="1.6388888888888888in"
height="0.2777777777777778in"} --------------A

![](media/image138.wmf){width="1.7020833333333334in"
height="0.2659722222222222in"}---------------------malla de entrada

----------------------malla de salida

**Despejando Ib de**
![](media/image140.wmf){width="1.8611111111111112in"
height="0.2777777777777778in"}

------------ y sustituyendo en en la malla de entrada:

---------

Ahora de

Sustituye en 

Es decir:

![](media/image154.wmf){width="2.7916666666666665in"
height="0.5277777777777778in"}

si tomamos en cuenta que bheta &gt;&gt; 1 y que Re(b+1)&gt;&gt;Rb

![](media/image158.wmf){width="2.125in" height="0.5277777777777778in"}
Lo cual queda demostrado

CONCLUSIONES
------------

Al hacer el análisis de la corriente de colector en función de los
portadores minoritarios, vemos que es afectado el valor por las
resistencias RE y RB.

 CALCULO DE LA VARIACIÓN DE LA CORRIENTE DE COLECTOR PARA UNA POLARIZACION UNIVERSAL
====================================================================================

![](media/image159.png){width="3.872916666666667in"
height="3.421527777777778in"}

![](media/image160.wmf){width="1.3194444444444444in"
height="1.9722222222222223in"}

CALCULO DE ICQ A VALORES NOMINALES:
-----------------------------------

![](media/image161.wmf){width="2.2083333333333335in"
height="0.4722222222222222in"}

![](media/image164.wmf){width="1.1111111111111112in"
height="0.5277777777777778in"}

 CALCULO DE LA VARIACION DE ICQ. 
---------------------------------

Recordando la expresión de Icq en función de los portadores minoritarios
para el emisor común:

![](media/image168.wmf){width="2.861111111111111in"
height="0.5277777777777778in"}

si verificamos la condición de que
![](media/image169.wmf){width="1.19375in" height="0.2777777777777778in"}

Por lo que es independiente de bheta y podemos utilizar la expresión de
Icq que esta en función de los portadores minoritarios e independiente
de bheta:

![](media/image175.wmf){width="2.263888888888889in"
height="0.5277777777777778in"}

  ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  ![](media/image176.wmf){width="1.2236111111111112in" height="0.6534722222222222in"}; ![](media/image177.wmf){width="1.2236111111111112in" height="0.6534722222222222in"}; ![](media/image178.wmf){width="1.1895833333333334in" height="0.6534722222222222in"};
  ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Para encontrar la variación de Icq respecto a la temperatura tenemos la
icq en función de los portadores minoritarios e independiente de bheta:

![](media/image180.wmf){width="2.263888888888889in"
height="0.5277777777777778in"}

![](media/image181.wmf){width="5.44375in" height="0.7777777777777778in"}

Despejando la variación de Icq tenemos:

Sustituyendo valores:

 ![](media/image191.wmf){width="1.2638888888888888in"
height="0.2638888888888889in"}

CONCLUSIONES:
-------------

Aquí podemos concluir que para estos valores el circuito no es estable
ya que tiene un 21.75 % de desviación, la tensión Vcc es la que mas
desvía el valor de la corriente de colector, le sigue la corriente de
portadores minoritarios, después el incremento en la tensión base emisor
y por último la resistencia Re. Rehagamos el calculo ahora para unos
valores más finos, el ejercicio anterior se exagero en la variación de
los parámetros, por lo que unos valores mas reales se presentan a
continuación.

 RECALCULO DE LA VARIACION DE ICQ PARA POLARIZACION UNIVERSAL (1% ):
====================================================================

Observar cuál es el parámetro que mas desvía a la corriente de colector

![](media/image194.wmf){width="5.875in" height="2.013888888888889in"}

 ![](media/image199.wmf){width="1.2638888888888888in"
height="0.2638888888888889in"}

CONCLUSIONES: 
--------------

Como podemos ver la variación se reduce al 1.8 % , la tensión Vcc es la
que mas desvía el valor, le sigue la resistencia Re, después la tensión
Vbe, y por último la corriente de portadores minoritarios.

 RECALCULO DE LA VARIACION DE Icq PARA POLARIZACION UNIVERSAL (0.1% ):
======================================================================

Observar cual es el parámetro que mas desvía a la corriente de colector.

![](media/image202.wmf){width="3.3333333333333335in"
height="0.2638888888888889in"}

 ![](media/image204.wmf){width="1.2638888888888888in"
height="0.2638888888888889in"}

CONCLUSIONES:
-------------

Para estas condiciones, vemos que la tensión Vcc sigue siendo una
fracción mayor a la tensión Vbe en cuanto a la contribución de la
variación de la corriente colector, al último queda la variación por los
portadores minoritarios. El error en por ciento es de 0.407 %

 COMPENSACION RESPECTO A LA TEMPERATURA POR UN DIODO
====================================================

![](media/image205.png){width="2.7041666666666666in"
height="3.1659722222222224in"}

**---------------1**

**-------------------2**

**----------------3**

**------------------4**

**4 en 3**

**----------------- 5**

**----------------------------- 6**

**-------------------7**

**------------------ 8**

**-------------------------9**

CONCLUSIONES
------------

Si observamos el numerador, el factor de la variación de la tensión del
diodo respecto a la temperatura se puede manipular para hacerlo igual a
la variación de la tensión base emisor, por lo que el circuito puede ser
estable respecto a la temperatura.

COMPENSACIÓN CON RESPECTO A LA TEMPERATURA POR DOS DIODOS.
==========================================================

![](media/image217.png){width="3.8375in" height="3.2284722222222224in"}

**Calculando un equivalente de thevenin en la base del transistor y
tierra:**

**--------------------A**

**---------------------B**

**Sustituyendo B en A tenemos:**

**y la resistencia de thevenin 2 es:**

**Entonces la corriente en la base del transistor es:**

**Si ambos diodos son iguales:**

**Ahora suponiendo que (bheta+1)Re &gt;&gt; Rth2, tenemos que el
circuito es independiente de bheta:**

**Como vemos dos términos se eliminan y queda:**

**Calculando la variación de Icq con respecto a la temperatura
tenemos:**

**Igualando a cero esta expresión:**

CONCLUSIONES
------------

Puesto que la variación de la tensión del diodo así como la variación de
la tensión de la base-emisor son iguales se simplifican y queda:

Para que el circuito sea estable respecto a la temperatura las
resistencias RB y RD deben ser iguales.
