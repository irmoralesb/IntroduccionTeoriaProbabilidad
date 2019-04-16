El Modelo Matemático
================

Experimentos Aleatorios
-----------------------

**El modelo**: Es solo una aproximación del sistema real y está sujeto siempre a comprobación.
**Experimento**: Un experimento es cualquier proceso que conduce a un resultado específico.
**Experimento Aleatorio:** consideraremos todos aquellos experimentos en los cuales, una vez definidas las condiciones en que se realizan, su resultado *no queda únicamente determinado.*
**Experimento Determinado:** lado consideraremos todos aquellos experimentos en los cuales, una vez definidas todas las condiciones bajo las cuales se realizan, su resultado queda únicamente determinado.
**Realización de un experimento aleatorio**: A cada repetición particular de un experimento aleatorio la llamaremos una realización de éste.

Eventos
-------

**Propiedad relativa a un experimento aleatorio**: Diremos que una propiedad es relativa a un experimento aleatorio si una vez realizado éste podemos decir si se presenta o no.
**Eventos**: Un evento es una propiedad relativa a un experimento aleatorio.
**Ocurrencia de un evento**:Se dice que un evento ocurre al realizar un experimento aleatorio si la propiedad que lo caracteriza se presenta en esa realización.

Principio de Regularidad de las frecuencias
-------------------------------------------

**Principio de regularidad de las frecuencias**: Entenderemos la fracción que resulta de dividir el número de veces que el evento ocurre en una serie de realizaciones del experimento entre el número total de veces que el experimento se realiza en esa serie. Este principio no es un principio absoluto que se cumple en cualquier serie de repeticiones de un experimento aleatorio.

El principio de regularidad de las frecuencias debe interpretarse con cuidado. Expresa que la frecuencia con que se presenta cada posible resultado de un experimento aleatorio, en una serie grande de realizaciones, se mantiene aproximadamente constante, pero, una eventual desviación de esa constante, si bien es algo que ocurre raramente, es perfectamente aceptable.

El Concepto de Probabilidad
---------------------------

El problema que se plantea en el cálculo de probabilidades consiste en encontrar una manera que permita medir el **“qué tan fácilmente”** se presentará un evento en futuras realizaciones de un experimento aleatorio. Así, se trata de asignar un número a cada evento, el cual exprese esa medida.

**Probabilidad de un evento**: La probabilidad de un evento relativo a un experimento aleatorio es un número que mide la **“facilidad”** con que el evento ocurre al realizar el experimento.

Espacios muestrales
-------------------

![\\Omega](https://latex.codecogs.com/png.latex?%5COmega "\Omega") representa el espacio muestral

![\\omega\_x](https://latex.codecogs.com/png.latex?%5Comega_x "\omega_x") representa cada posible resultado del experimento aleatorio

Así el espacio muestral se puede representar como:

![\\Omega = \\{(1,1,1),(1,1,2),...\\}](https://latex.codecogs.com/png.latex?%5COmega%20%3D%20%5C%7B%281%2C1%2C1%29%2C%281%2C1%2C2%29%2C...%5C%7D "\Omega = \{(1,1,1),(1,1,2),...\}")

o tambien como

![\\Omega = \\{(\\omega\_1),(\\omega\_2),..\\}](https://latex.codecogs.com/png.latex?%5COmega%20%3D%20%5C%7B%28%5Comega_1%29%2C%28%5Comega_2%29%2C..%5C%7D "\Omega = \{(\omega_1),(\omega_2),..\}")

**Espacio muestral**: El espacio muestral de un experimento aleatorio es el conjunto formado por todos sus posibles resultados.

Un ejemplo para mostrar la nomenclatura de un espacio muestral sea un conjunto infinito no numerable ![\\Omega = \\{ x \\in \\R : x \\geq 0 \\}](https://latex.codecogs.com/png.latex?%5COmega%20%3D%20%5C%7B%20x%20%5Cin%20%5CR%20%3A%20x%20%5Cgeq%200%20%5C%7D "\Omega = \{ x \in \R : x \geq 0 \}") , en este caso ![\\Omega](https://latex.codecogs.com/png.latex?%5COmega "\Omega") es un conjunto infinito no numerable.

Representación de Eventos
-------------------------

**Resultados favorables a un evento**: Los resultados favorables a un evento A, relativo a un experimento aleatorio, son todos aquellos posibles resultados del experimento de los cuales se deduce la ocurrencia de A.

**Equivalencia de eventos**: Dos eventos son equivalentes si la ocurrencia de cualquiera de ellos implica la ocurrencia del otro en cualquier realización del experimento.

En particular, cada posible resultado ω ∈ Ω representa un evento, consistente en la ocurrencia de ω. A esta clase particular de eventos, que se representan por un elemento de Ω, los llamaremos eventos elementales.

**Eventos elementales**: Un evento elemental relativo a un experimento aleatorio es un evento consistente en la ocurrencia de un específico posible resultado del experimento.

**Evento seguro**: El evento seguro relativo a un experimento aleatorio es un evento que siempre ocurre al realizar el experimento.

**Evento imposible**: El evento imposible relativo a un experimento aleatorio es un evento que nunca ocurre al realizar el experimento.

Composición de eventos
----------------------

**Unión de eventos**: Si A y B son dos eventos, definimos un nuevo evento caracterizado por la propiedad de que ocurre en la realización de un experimento si y sólo si ocurre alguno de los eventos A o B, o ambos. A este nuevo evento lo llamaremos la unión de A y B y lo denotaremos por A ![\\cup](https://latex.codecogs.com/png.latex?%5Ccup "\cup") B.

**Intersección de eventos**: Si A y B son dos eventos, definimos un nuevo evento caracterizado por la propiedad de que ocurre en la realización de un experimento si y sólo si los dos eventos A y B ocurren. A este nuevo evento lo llamaremos la intersección de A y B y lo denotaremos por A ![\\cap](https://latex.codecogs.com/png.latex?%5Ccap "\cap") B.

**Complemento de un evento**: Si A es un evento, definimos un nuevo evento caracterizado por la propiedad de que ocurre en la realización de un experimento si y sólo si A no ocurre. A este nuevo evento lo llamaremos el complemento o la negación de A y lo denotaremos por ![A^c](https://latex.codecogs.com/png.latex?A%5Ec "A^c").

**Eventos Ajenos**: En la teoría de Conjuntos se tiene el concepto de eventos ajenos, lo cual significa que éstos tienen una intersección vacía. Como veremos más adelante, este concepto es especialmente importante en la teoría de la probabilidad.

**Eventos mutuamente excluyentes**: Diremos que dos eventos A y B son mutuamente excluyentes si la ocurrencia de ambos en cualquier realización del experimento es imposible.

**Eventos mutuamente excluyentes**: Diremos que n eventos A1,..., An son mutuamente excluyentes si los eventos ![A\_i](https://latex.codecogs.com/png.latex?A_i "A_i") y ![A\_j](https://latex.codecogs.com/png.latex?A_j "A_j") son mutuamente excluyentes para toda i, j ∈ {1,..., n}, con i ![\\ne](https://latex.codecogs.com/png.latex?%5Cne "\ne") j.

Ejemplo:

En una cierta compañía el esquema para aprobar una propuesta es el siguiente: tres personas —A, B y C— analizan la propuesta y ésta es aprobada únicamente si por lo menos dos de las tres personas dan su visto bueno. Consideremos una determinada propuesta y sean A, B, C y D los eventos ‘la persona A da su visto bueno’, ‘la persona B da su visto bueno’, ‘la persona C da su visto bueno’ y ‘la propuesta es aprobada’, respectivamente. D puede expresarse como una unión de eventos mutuamente excluyentes, cada uno de los cuales está dado en términos de A, B y C, a saber, D = (A ∩ B ∩ C c) ∪ (A ∩ Bc ∩ C) ∪ (Ac ∩ B ∩ C) ∪ (A ∩ B ∩ C).

Funciones de probabilidad
-------------------------

El problema que se plantea en el cálculo de probabilidades consiste en encontrar una manera que permita asignar a cada evento un número, el cual mida el “que tan fácilmente” se presentará el evento en futuras realizaciones de un experimento aleatorio. Ese número que se asigna a un evento es llamado, la probabilidad del evento. Dicho de otra manera, lo que se busca es una función con valores reales definida sobre la familia de eventos; a tal función la llamaremos la **función de probabilidad.**

Al asignar probabilidades a cada evento, relativo a un experimento aleatorio dado, lo que estamos haciendo es definir un **modelo** que nos permitirá estudiar el experimento aleatorio.

La interpretación práctica de la probabilidad de un evento que se utiliza más frecuentemente es la basada en el principio de **regularidad de las frecuencias**. La probabilidad de un evento A, relativo a un experimento aleatorio repetible, es un número que debe ser aproximadamente igual a la frecuencia relativa con que el evento A ocurre en una serie grande de realizaciones del experimento aleatorio.

Se pueden plantear unas reglas:

    * Si A es un evento y denotamos por P(A) a su probabilidad de ocurrencia, entonces P(A) ≥ 0.
    * El evento seguro Ω tiene, en cualquier caso, una frecuencia relativa igual a 1 pues siempre ocurre.
      Es decir, podemos escribir P(Ω) = 1.
    * Cierto evento C es la unión de dos eventos mutuamente excluyentes A y B, luego entonces: 
      P(C) = P(A) + P(B).

**Función de probabilidad**: Dado un experimento aleatorio cualquiera, denotando por A a la familia de eventos relativos a ese experimento, diremos que una función P: A 7→ R es una función de probabilidad si se satisfacen las siguientes propiedades:

    i. P(A) ≥ 0 para todo evento A. 
    ii. P(Ω) = 1. 
    iii. Si A y B son dos eventos mutuamente excluyentes, entonces: P(A ∪ B) = P(A) + P(B)

Ejercicios
----------

**Ejercicio 1 Problema de los 3 jugadores** Tres jugadores —P, Q y R— juegan partidas por parejas, comenzando P contra Q. Quien gane una partida juega con el otro jugador, hasta que uno de los jugadores gane dos partidas consecutivas, ganando entonces el juego. Describa el espacio muestral de este juego.

![\\Omega = \\{(P,P),(P,R,Q,P,P), (P,R,Q,P,R,Q,P,P),...\\}](https://latex.codecogs.com/png.latex?%5COmega%20%3D%20%5C%7B%28P%2CP%29%2C%28P%2CR%2CQ%2CP%2CP%29%2C%20%28P%2CR%2CQ%2CP%2CR%2CQ%2CP%2CP%29%2C...%5C%7D "\Omega = \{(P,P),(P,R,Q,P,P), (P,R,Q,P,R,Q,P,P),...\}")

![\\cup \\{(P,R,Q,Q),(P,R,Q,P,R,Q,Q),.. \\} ](https://latex.codecogs.com/png.latex?%5Ccup%20%5C%7B%28P%2CR%2CQ%2CQ%29%2C%28P%2CR%2CQ%2CP%2CR%2CQ%2CQ%29%2C..%20%5C%7D%20 "\cup \{(P,R,Q,Q),(P,R,Q,P,R,Q,Q),.. \} ")

![\\cup \\{(P,R,R),(P,R,Q,P,R,R),..\\} ](https://latex.codecogs.com/png.latex?%5Ccup%20%5C%7B%28P%2CR%2CR%29%2C%28P%2CR%2CQ%2CP%2CR%2CR%29%2C..%5C%7D%20 "\cup \{(P,R,R),(P,R,Q,P,R,R),..\} ")

![\\cup \\{(Q,Q),(Q,R,P,Q,Q),(Q,R,P,Q,R,P,Q,Q),...\\}](https://latex.codecogs.com/png.latex?%5Ccup%20%5C%7B%28Q%2CQ%29%2C%28Q%2CR%2CP%2CQ%2CQ%29%2C%28Q%2CR%2CP%2CQ%2CR%2CP%2CQ%2CQ%29%2C...%5C%7D "\cup \{(Q,Q),(Q,R,P,Q,Q),(Q,R,P,Q,R,P,Q,Q),...\}")

![\\cup \\{(Q,R,R),(Q,R,P,Q,R,R),...\\}](https://latex.codecogs.com/png.latex?%5Ccup%20%5C%7B%28Q%2CR%2CR%29%2C%28Q%2CR%2CP%2CQ%2CR%2CR%29%2C...%5C%7D "\cup \{(Q,R,R),(Q,R,P,Q,R,R),...\}")

![\\cup \\{(Q,R,P,P),(Q,R,P,Q,R,P,P),...\\}](https://latex.codecogs.com/png.latex?%5Ccup%20%5C%7B%28Q%2CR%2CP%2CP%29%2C%28Q%2CR%2CP%2CQ%2CR%2CP%2CP%29%2C...%5C%7D "\cup \{(Q,R,P,P),(Q,R,P,Q,R,P,P),...\}")

**Ejercicio 2** Un experimento aleatorio consiste en elegir al azar 3 números —a, b y c— en el intervalo \[0, 1\], para formar la ecuación ![ax^2+bx+c = 0](https://latex.codecogs.com/png.latex?ax%5E2%2Bbx%2Bc%20%3D%200 "ax^2+bx+c = 0"). Sea A el evento ‘las dos raíces de la ecuación son reales y distintas’. Represente como un conjunto Ω al espacio muestral de este experimento y al evento A como un subconjunto de Ω.

![\\Omega = \\{(a,b,c) \\in \\R^3 : 0 \\leq a \\leq 1, 0\\leq b \\leq 1, 0 \\leq c \\leq 1\\} ](https://latex.codecogs.com/png.latex?%5COmega%20%3D%20%5C%7B%28a%2Cb%2Cc%29%20%5Cin%20%5CR%5E3%20%3A%200%20%5Cleq%20a%20%5Cleq%201%2C%200%5Cleq%20b%20%5Cleq%201%2C%200%20%5Cleq%20c%20%5Cleq%201%5C%7D%20 "\Omega = \{(a,b,c) \in \R^3 : 0 \leq a \leq 1, 0\leq b \leq 1, 0 \leq c \leq 1\} ")

![A = \\{(a,b,c) \\in \\Omega : b^2 - 4ac &gt; 0 \\} ](https://latex.codecogs.com/png.latex?A%20%3D%20%5C%7B%28a%2Cb%2Cc%29%20%5Cin%20%5COmega%20%3A%20b%5E2%20-%204ac%20%3E%200%20%5C%7D%20 "A = \{(a,b,c) \in \Omega : b^2 - 4ac > 0 \} ")

**Ejercicio 3** Dos personas, P y Q, juegan un juego de azar, el cual consiste en ir lanzando un par de dados por turnos, comenzando por P, de tal manera que, si P obtiene una suma igual a 7, se acaba el juego, ganando P, mientras que, si Q obtiene una suma igual a 6, se acaba el juego, ganando Q. Sea A el evento ‘el jugador P gana el juego’. Represente como un conjunto Ω al espacio muestral de este juego y al evento A como un subconjunto de Ω.

![ \\Omega = \\{(P), (\\overline{P,Q},P),(\\overline{P,Q,P,Q},P)\\,...\\} ](https://latex.codecogs.com/png.latex?%20%5COmega%20%3D%20%5C%7B%28P%29%2C%20%28%5Coverline%7BP%2CQ%7D%2CP%29%2C%28%5Coverline%7BP%2CQ%2CP%2CQ%7D%2CP%29%5C%2C...%5C%7D%20 " \Omega = \{(P), (\overline{P,Q},P),(\overline{P,Q,P,Q},P)\,...\} ")

![ \\cup \\{(\\overline{P},Q), (\\overline{P,Q,P},Q),(\\overline{P,Q,P,Q,P},Q)\\,...\\} ](https://latex.codecogs.com/png.latex?%20%5Ccup%20%5C%7B%28%5Coverline%7BP%7D%2CQ%29%2C%20%28%5Coverline%7BP%2CQ%2CP%7D%2CQ%29%2C%28%5Coverline%7BP%2CQ%2CP%2CQ%2CP%7D%2CQ%29%5C%2C...%5C%7D%20 " \cup \{(\overline{P},Q), (\overline{P,Q,P},Q),(\overline{P,Q,P,Q,P},Q)\,...\} ")

![ A = \\{(P), (\\overline{P,Q},P),(\\overline{P,Q,P,Q},P)\\,...\\}](https://latex.codecogs.com/png.latex?%20A%20%3D%20%5C%7B%28P%29%2C%20%28%5Coverline%7BP%2CQ%7D%2CP%29%2C%28%5Coverline%7BP%2CQ%2CP%2CQ%7D%2CP%29%5C%2C...%5C%7D " A = \{(P), (\overline{P,Q},P),(\overline{P,Q,P,Q},P)\,...\}")

**Ejercicio 4** Sean A y B dos eventos y sean E y F los eventos ‘ocurre exactamente uno de los dos eventos A y B’ y ‘ocurre a lo más uno de los dos eventos A y B’, respectivamente. Exprese los eventos E y F en términos de A y B.

![ E = (A \\cup B) - (A \\cap B)  ](https://latex.codecogs.com/png.latex?%20E%20%3D%20%28A%20%5Ccup%20B%29%20-%20%28A%20%5Ccap%20B%29%20%20 " E = (A \cup B) - (A \cap B)  ")

![ F = (\\overline{A \\cap B})](https://latex.codecogs.com/png.latex?%20F%20%3D%20%28%5Coverline%7BA%20%5Ccap%20B%7D%29 " F = (\overline{A \cap B})")

**Ejercicio 5** Un trabajador produce n partes de un artículo. Sea ![A\_i](https://latex.codecogs.com/png.latex?A_i "A_i") el evento ‘la i-ésima parte está defectuosa’. Exprese en términos de los ![A\_i](https://latex.codecogs.com/png.latex?A_i "A_i") cada uno de los siguientes eventos:

    a) ninguna de las n partes está defectuosa,

![\\bigcap\_{i=1}^n A\_i^c ](https://latex.codecogs.com/png.latex?%5Cbigcap_%7Bi%3D1%7D%5En%20A_i%5Ec%20 "\bigcap_{i=1}^n A_i^c ")

    b) al menos una de las n partes está defectuosa,

![\\bigcap\_{i=1}^n A\_i ](https://latex.codecogs.com/png.latex?%5Cbigcap_%7Bi%3D1%7D%5En%20A_i%20 "\bigcap_{i=1}^n A_i ")

 c) exactamente una de las n partes está defectuosa.

![\\bigcup\_{i=1}^n \[\\, A\_i \\cap (\\bigcap\_{j \\neq i} A\_j^c) \]\\,  ](https://latex.codecogs.com/png.latex?%5Cbigcup_%7Bi%3D1%7D%5En%20%5B%5C%2C%20A_i%20%5Ccap%20%28%5Cbigcap_%7Bj%20%5Cneq%20i%7D%20A_j%5Ec%29%20%5D%5C%2C%20%20 "\bigcup_{i=1}^n [\, A_i \cap (\bigcap_{j \neq i} A_j^c) ]\,  ")
