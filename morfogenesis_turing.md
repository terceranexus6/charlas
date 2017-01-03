#Morfogenesis química de Turing
>Trabajo sobre la _morfogénesis química de Turing_ para la asignatura de MC de 3GII

Paula de la Hoz Garrido    

![zebras](https://tedideas.files.wordpress.com/2014/08/zebras_istock_000021650180_large.jpg?w=750)


##Índice

- **1. Introducción**
  - 1.1 Alan Turing
  - 1.2 Validación de una teoría
- **2. Modelo matemático**
  - 2.1 Introducción
  - 2.2 Modelo matemático
  - 2.3 Casos
- **3. Implicaciones**
  - 3.1 Implicación química
  - 3.2 Implicación computacional
  - 3.3 Implicación filosófica
- **Notas**
- **Bibliografía**


##1.Introducción

###1.1 Alan Turing

**Alan Mathison Turing** era un matemático inglés que nació en 1912. Considerado el padre de la computación moderna, sus investigaciones han sido relevantes para los campos de la informática, matemáticas, filosofía, criptografía y _**química**_. 

Durante la _2GM_ su trabajo sobre la máquina Enigma sirvió para descifrar códigos nazis, y se considera que su investigación junto al de su equipo de investigación, aceleraron el final de la guerra. 

![Turing](https://github.com/terceranexus6/charlas/blob/master/images/Alan-Turing-el-hombre-que-enseno-a-pensar-a-las-maquinas%20(1).jpg)

En el campo de la inteligencia artificial, aportó un gran avance que sirvió de impulso para investigaciones posteriores. El conocido "_Test de Turing_" es un ejemplo de esto. Turing pensaba que lasmáquinas alcanzarían un nivel practicamente humano de razonamiento en un futuro. Esta postura podía verse en su artículo [_Computer Machinery and Intelligence_](https://www.csee.umbc.edu/courses/471/papers/turing.pdf) donde enumera las distintas objeciones suyas y de otros profesionales acerca de la idea de máquinas pensantes, y su contrapunto personal. 

> El test de Turing es un sistema mediante el cual se puede medir si una inteligencia artificial se asemeja lo suficiente al comportamiento humano. Para ello, un humano y un personaje anónimo (humano o inteligencia artificial) deben conversar a través de de un ordenador sin verse la cara. En base a la conversación, el humano debe decidir si su interlocutor es o no es un humano. La primera IA que pasó esta prueba es ELIZA, que emulaba a una psicóloga. 

### Infancia y juventud

*************************** por completar ** 

###1.2 Validación de una teoría

Aunque las aportaciones de Turing en el campo de la computación son mundialmente conocidas, su estudio sobre química y biología no habían alcanzado tanto renombre, hasta el 2014. En este año, su teoría de la morfogésis química  es validada (sesenta años después de la muerte del cientfico), en la que postula que las células biológicas idénticas se diferencian, cambian de forma y crean patrones a través de un proceso llamado reacción difusión intercelular.  

![patron](http://www.bio.brandeis.edu/faculty/images/epstein-fig.gif)

Esto ha sido posible gracias a la Universidad de Brandeis y la de Pittsburgh, en el cual  diseñaron un experimento para poner a prueba la teoría de Turing, descubriendo los seis patrones que había descrito y uno no previsto.

##Modelo matemático

###1.1 Introducción

Antes de explicar el proceso químico de la teoría, es conveniente nombrar que Turing era thompsoniano (autor a quien leyó durante su educación básica) que, como recordatorio, postulaba una teoría diferente a la de Darwin sobre la evolución, y escribe:

El hecho de que muchas formas biológicas parecen seguir reglas matemáticas o geométricas sencillas, indica que la existencia de fuerzas de constricción en su crecimiento es una explicación más parsimoniosa que la selección natural. 

En este párrafo, además de cuestionar la teoría de Darwin, señala la importancia de las matemáticas en el escenario de biología. Turing formulará su teoría química y matemática sobre la morfogénesis basándose en una ideología Thompsoniana. Esta teoría abarca un problema dentro de la biología del desarrollo, las transformaciones que sufre un óvulo fecundado (huevo->mórula->blástula->gástrula) hasta llegar a un individuo formado por  1015 células diferenciadas. 

![fig1](https://github.com/terceranexus6/charlas/blob/master/images/fig1.png)

En su trabajo, Turing describe lo siguiente:

>  … Se sugiere que un sistema de sustancias químicas llamadas morfógenos, reaccionando y difundiéndose a través del tejido, es el adecuado para describir el principal fenómeno de la morfogénesis. Tal sistema, aunque originalmente puede estar bastante homogéneo, más tarde puede desarrollar un patrón o estructura debido a una inestabilidad del equilibrio homogéneo la cual es disparada por una perturbación al azar. 

En este párrafo tiene cierto protagonismo la mención de los morfógenos. Esto fue criticado al principio, dado que el matemático apenas los define. Turing postula que el patrón emerge de la desestabilización producida por perturbaciones de un estado homogéneo, es decir, el matemático habla del rompimiento de la simetría, a causa de los cambios cualitativos que se dan en el cigoto durante su estado de bástula [fg 1].

Las limitaciones físicas que ocupan el modelo de morfogénesis química son las siguientes:

1. La continuidad
Las variables de tiempo (t) y espacio (x) toman valores continuos. La hipótesis de continuidad considera que el tejido (o el sustrato material de que se trate) es una masa continua, la misma hipótesis que se plantean los físicos en mecánica de fluídos.
 
2. Las características físicas
Las sustancias que forman las células, tienen propiedades electroquímicas y, el tejido como 	un todo, tiene propiedades mecánicas las cuales son descritas por la teoría de la elasticidad. 

3. La difusión
Los morfógenos al difundirse por el tejido, lo hacen en dirección contraria a la del 	gradiente de su concentración es decir, el flujo de los morfógenos, satisface la ley de Fick. 

4. La cinética
Los morfógenos, al difundirse por el tejido también reaccionan químicamente. Bajo una serie de premisas, la cinética química de estas reacciones la da la ley de acción de masas[*].
 
5. El tamaño y la forma 
Ambos, tamaño y forma del tejido en el que se plantea el modelo, son fijos. Es decir, se excluye la posibilidad de que el medio crezca, as´ı como que sus características geométricas cambien. 

###1.2 El modelo matemático

La formulación matemática de Turing toma forma de un par de ecuaciones en derivadas parciales, de tipo parabólico, a las que llamamos ecuaciones de reacción y difusión, definidas en Omega. Omega es un subconjunto de los pares ordenados de números reales. 

Para el caso de dos reactivos, cuya concentración en el punto ~r = (x, y) ∈ Ω al tiempo t, la denotamos por u(~r, t) y v(~r, t), respectivamente, aquellas —bajo las premisas 1-5— se escriben así: 

![1](https://github.com/terceranexus6/charlas/blob/master/images/1.png)

para todo (~r, t) ∈ Ω × R +, donde ∇2 es el operador laplaciano que, en coordenadas cartesianas, es 

∇2 (·) = ∂ 2 (·) ∂x2 + ∂ 2 (·) ∂y2 . 

Las difusividades, D1 y D2, son constantes positivas; mientras que las funciones f y g —que incluso en casos sencillos, son funciones no lineales de la concentración de los dos reactivos— dan la velocidad instantánea con la que ´estos reaccionan. La forma explícita de _f_ y _g_ depende de la cinética química involucrada en el proceso particular que se estudie. 

A fin de completar el problema matemático por estudiar, al sistema (1) se le deben a˜nadir las condiciones iniciales y las condiciones de frontera. Las primeras son 

![2](https://github.com/terceranexus6/charlas/blob/master/images/2.png)

donde las funciones u0(~r) y v0(~r) son dadas y representan la distribución inicial (en t = 0) de los morfógenos en Ω. Las condiciones de frontera que consideramos, son de tipo Neumann homogéneas es decir, el flujo de los reactivos es cero en la frontera, ∂Ω, de Ω. Luego 

![3](https://github.com/terceranexus6/charlas/blob/master/images/3.png)

La no linealidad del problema (1)-(2)-(3) hace que la búsqueda de soluciones explícitas para él, se convierta solo en un buen deseo y no en una realidad. En este punto, deberán usarse aproximaciones (Turing para ello, además de análisis cualitativo utilizó la primera computadora comercial, la precursora de la Ferranti Mark I, y fue de los primeros científicos en usarla para una investigación matemática) para el problema, o al menos definir cómo debieran ser éstas soluciones aún sin ser conocidas. La nolinealidad y aparición de parámetros con una importante interpretación físico-química, trae dificultades. Sin embargo también aporta una serie de ventajas en las concentraciones u y v. 

A continuación analizamos las restantes (4) y (5) el par de EDP que nos faltaban. 

![4](https://github.com/terceranexus6/charlas/blob/master/images/4.png)

Donde t y xx denotan la derivada parcial respecto a t y la segunda derivada parcial respecto a x, respectiamente. As´ı, empezamos considerando el sistema homog´eneo es decir, el que resulta de hacer D1 = D2 = 0. El resultado es el sistema no lineal de ecuaciones diferenciales ordinarias (EDO):

![5](https://github.com/terceranexus6/charlas/blob/master/images/5.png)

Aquí el punto sobre u y v denota la derivada respecto al tiempo de estas variables. Supongamos que (5) tiene un punto de equilibrio positivo, (u ∗ , v∗ ), por lo que ´este satisface f(u ∗ , v∗ ) = g(u ∗ , v∗ ) = 0, con u ∗ y v ∗ positivos. El sistema lineal que aproxima a (5) en una vecindad del equilibrio lo define la matriz de Jacobi 

![matriz](https://github.com/terceranexus6/charlas/blob/master/images/matrix.png)

donde las derivadas parciales J11 = ∂f/∂u, J12 = ∂f/∂v, J21 = ∂g/∂u y J22 = ∂g/∂v se evalúan en (u ∗ , v∗ ). Luego, el sistema lineal que aproxima a (5) alrededor de (u ∗ , v∗ ), es 

![6](https://github.com/terceranexus6/charlas/blob/master/images/6.png)

Las condiciones para que (u ∗ , v∗ ) sea asintóticamente estable localmente (estable ante perturbaciones temporales), se expresan en términos de la traza, tr J[f, g](u∗,v∗) , y del determinante, det J[f, g](u∗,v∗) , de J[f, g](u∗,v∗) . Aquellas son: 

![7](https://github.com/terceranexus6/charlas/blob/master/images/7.png)

Este par de condiciones garantizan, además, la hiperbolicidad del equilibrio (u ∗ , v∗ ). Por ello, usando el Teorema de Hartman-Grobman (véase [30]), la dinámica local del sistema (5) es, cualitativamente hablando, la misma que la del sistema lineal (6). 

Para simplificar desde ahora en vez de J[f, g](u∗,v∗) escribiremos J. Considerando ahora el cas n homogéneo en el que D1 y D2 son positivas, primero notamos que el equilibrio (u ∗ , v∗ ) determina una solución estacionaria (no cambia con el tiempo) y homogénea (no cambia con x) del sistema (4). 

![extra](https://github.com/terceranexus6/charlas/blob/master/images/extr.png)
Se puede verificar que para todo (x,t) se satisface la igualdad

![72](https://github.com/terceranexus6/charlas/blob/master/images/7-2.png)

Y su aproximación lineal a (4) alrededor de la solución estacionaria y homogénea (˜u(x, t), v˜(x, t)) 

![8](https://github.com/terceranexus6/charlas/blob/master/images/8.png)

Notemos que las diferencias u − u ∗ y v − v ∗ miden, para cada pareja (x, t), la desviación o perturbación de u y v, respecto a u ∗ y v ∗ , respectivamente. Introduzcamos una notación para ellas. Sean U y V tales que: 

![82](https://github.com/terceranexus6/charlas/blob/master/images/8-2.png)

Como Ut = ut , Uxx = uxx, Vt = vt y Vxx = vxx, entonces el sistema (8) expresando en términos de las perturbaciones, es 

![9](https://github.com/terceranexus6/charlas/blob/master/images/9.png)

La solución homogénea y estacionaria, (u ∗ , v∗ ), de (4), corresponde a la solución (0, 0) —también homogénea y estacionaria— de (9). Habiendo notado esto, recordemos cu´al es nuestra tarea: queremos averiguar las condiciones bajo las cuales el estado estacionario y homogéneo, (u ∗ , v∗ ), de (4)—equivalentemente (0, 0) para (9)— pierde su estabilidad ante perturbaciones espacio-temporales. Uno puede averiguarlo proponiendo que cada una de las componentes (recuérdese que son las perturbaciones), U y V, de la solución de este sistema se exprese como una combinación lineal infinita de funciones de onda, es decir, de funciones cuya forma es: 

![ecu1](https://github.com/terceranexus6/charlas/blob/master/images/ecu1.png)

donde λ es desconocida, k es el número de onda e i = √ −1. Si escribimos la función de onda propuesta como 

![ecu2](https://github.com/terceranexus6/charlas/blob/master/images/ecu2.png)

notamos que ésta consta de dos partes: una que cambia exponencialmente al aumentar t la cual está multiplicada por otra que oscila y es acotada para toda x. Por esta razón, en vez de considerar la suma infinita de funciones de onda, bastaría que un solo término de dicha suma crezca al aumentar t, para que la perturbación (U, V) desestabilice al estado (0, 0) (al estado (u ∗ , v∗ )). Luego, proponemos por solución de (9) a la pareja 

![10](https://github.com/terceranexus6/charlas/blob/master/images/10.png)

donde C1 y C2 son constantes desconocidas. Nuestra tarea la hemos llevado a los siguientes términos: investigar las condiciones bajo las cuales las perturbaciones crecen al aumentar t. Aquí están las condiciones suficientes para que se dispare el mecanismo morfogenético de Turing. 

1) tr J = (J11 + J22) < 0

2) det J = (J11J22 − J21J12) > 0

3) . [(D1J22 + D2J11)] > 0

4) . [(D1J22 + D2J11) 2 − 4D1D2 det J] > 0

Las dos primeras condiciones garantizan la estabilidad del estado estacionario y homogéneo (u ∗ , v∗ ) ante perturbaciones temporales; mientras que las dos siguientes, aseguran que ´este se desestabilice ante perturbaciones espacio-temporales. Al conjunto de parámetros cinéticos y de difusión para los que las condiciones 1-4 se cumplen, se le llama espacio de Turing. 

###2.3 Casos concretos estudiados por Turing

###Anillo discreto

Un anillo formado por N células muy parecidas. Cada una de estas células intercambian por difusión un material sólo con sus vecinas inmediatas. La difusividad de cada morfógeno se supone constante y el carácter discreto del sistema biológico hace necesaria una versión discreta del sistema (1) en una dimensión. 

###Anillo continuo

Turing considera ahora un anillo formado por tejido (una masa continua) en donde la concentración de los morfógenos depende del tiempo y ángulo. Dependiendo de una  variable λ˜,  las distribuciones posibles para este caso son Estacionaria si la variable es real y Oscilatoria si es un número complejo. 

El matemático concluye que, una vez se ha roto la simetría, pueden originarse hasta seis distribuciones espaciales ondulatorias distintas de morfógenos en el anillo. Cuatro de ´estas se dan en sistemas con dos morfógenos; mientras que las dos restantes, se dan solo si se consideran tres morfógenos. 

![fig2](https://github.com/terceranexus6/charlas/blob/master/images/fig2.png)

En esta imagen encontramos el patrón computacional resultado de una simulación numérica realizada por Turing, cumpliéndose las condiciones suficientes para el rompimiento de simetría homogénea. 

Turing consiguió este patrón realizando lo que se considera una delas primeras simulaciones computacionales. Turing sostiene que una de las cuatro posibilidades podría ser adecuada para explicar la filotaxia de algunas plantas cuyos reto˜nos o brotes, tengan la misma simetría que el anillo. También habla de la posibilidad de regenerar partes amputadas.

###Esfera

Turing reflexiona sobre esta forma porque hay organismos cuyos cigotos en el estado de blástula, tienen aproximadamente forma esférica. 

IMAGEN

El matemático inglés considero la superficie de una espera hueca, y sobre él un sistema de reacción-difusión, y variando los ángulos polar y azimutal, de forma que los morfógenos no sólo dependían (como hemos visto antes) del tiempo, si no de dichos ángulos. La ecuación obtenida es:

IMAGEN ECUACION

Turing añade:

> Es probable que la forma de varias estructuras cercanamente esféricas, tales como los esqueletos de las radiolarias, estén íntimamente relacionadas con patrones de tipo armónicos esféricos. Sin embargo, la aplicación más importante de la teoría parece ser a la gastrulación de una blástula.






























http://www.brandeis.edu/now/2014/march/turingpnas.html
http://www.abc.es/ciencia/20140311/abci-validan-teoria-turing-anos-201403101617.html







