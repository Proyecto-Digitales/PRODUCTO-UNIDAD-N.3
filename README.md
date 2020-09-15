                                                    DIAGRAMAS DE MÁQUINAS DE ESTADO


1.PLANTEAMIENTO DEL PROBLEMA

Se denomina máquina de estados a un modelo de comportamiento de un sistema con entradas y salidas en donde las salidas dependen 
no solo de las señales de entradas actuales, sino también de las anteriores. Tienes diversas aplicaciones en las que se puede utilizar como por ejemplo la realización de circuitos secuenciales. Para nuestro caso utilizaremos este método para resolver diversos problemas planteados.

2.OBJETIVOS

Objetivo general

- Diseñar diagramas y tablas de de estado a partir de los datos propuestos en los ejerciciosos.

Objetivo específicos

- Investigar sobre circuitos secuenciales que se puedan implementar por medio de máquinas de estado.

- Desarrollar el diseño de las máquinas de estado mediante grafos.


3.ESTADO DEL ARTE

En 2017 SANTIAGO GONZALEZ de la UNIDAD ACADÉMICA SANTIAGO DE CHILE DE INGENIERÍA EN CIENCIAS ECONOMICAS diseño la propia tienda On-Line tenga un 
carácter comercial para la empresa que vende los productos, y no sólo como un lugar donde realizar compras. Para ello, se tomaron decisiones como 
la de incluir información general de la empresa en las pantallas iniciales, inclusión de banner en la página, permitir que cualquier usuario pudiera 
navegar por el catálogo y los productos, pedir información sobre ellos, etc. Además, el hecho de registrarse en la web tendría otros añadidos para los 
usuarios aparte del propio de poder comprar como serían la descarga del catálogo completo o de partes de él en un formato fácilmente portable como es 
el PDF con la utilización de diagramas de estado (SANTIAGO GONZALEZ, 2017, p.1) [1].

En 2018 WILSON BALDEÓN Y VERONICA MORA de la ESCUELA SUPERIOR POLITECNICA DE CHIMBORAZO ubicado en Riobamba-Ecuador diseño un circuito secuencial sincrónico 
con los latch básicos, los latch asincrónicos y los ÁLSÁRSV, que son los elementos fundamentales a partir de los cuales se construyen máquinas secuenciales 
sincrónicas, el siguiente paso es el estudio de las técnicas de análisis y diseño de máquinas o circuitos secuenciales sincrónicos y asincrónicos. Una máquina
secuencial, en general, se caracteriza porque los valores que se encuentran presentes en sus salidas, en algún instante, dependen no solamente de los valores que 
se encuentran presentes en sus entradas en ese instante, sino también, de todos los valores que estuvieron en esas entradas, es decir, de la historia pasada de esas
entradas, valga la redundancia. Una máquina se llama secuencial porque, tiene que pasar, paso a paso, por un conjunto de estados. Si el paso de un estado a otro esta
sincronizado por una señal de reloj, la máquina se llama secuencial sincrónica. Si la máquina no tiene una señal que sincronice los cambios de estado sino más bien los 
cambios de estado son realizados en el instante que alguna de sus señales de entrada ha cambiado, la máquina se llama secuencial asincrónica.  (WILSON BALDEÓN Y VERONICA 
MORA, 2018, p.1) [2].


4.MARCO TEÓRICO

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.3/blob/master/Img/marco%20teorico%201.png) 

Figura 1. Marco teórico

5.DIAGRAMAS

•Diagramas de estado.

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.3/blob/master/Img/3.1.jpeg)

Diagrama. Ejercicio 1  

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.3/blob/master/Img/3.2.jpeg)

Diagrama Ejercicio 2

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.3/blob/master/Img/3%20Dise%C3%B1o%205.PNG)

Diagrama de estados. Ejercicio 4

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.3/blob/master/Img/3.5.jpeg)

Diagrama de estados. Ejercicio 5


6.LISTA DE COMPONENTE

- Diseñador de diagramas online creatly


7.EXPLICACIÓN DEL DISEÑO

1. Dibuje el diagrama de estados para la máquina de estado finito cuya tabla de estados es la siguiente. Partiendo del estado s0, 
calcula la salida para la cadena de entrada 1000110.

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.3/blob/master/Img/3%20Dise%C3%B1o%201.PNG) 

Tabla 1. Ejercicio 1

Desarrollo:

Para construir el diagrama empezamos a partir de la tabla de transición que tenemos como dato, obervamos que en la primera fila significa 
nuestro estado inicial y estado actual, entonces cuando la máquina toma el valor de 0 pasa al siguiente estado obteniendo en su salida 1 que 
nos da el valor de S0. Ahora seguimos con el siguiente estado teniendo en cuenta que nuestro estado actual se encuentra con el valor valor de 1. 
Mediante esta mecánica seguimos con los siguientes estados para construir nuestro diagrama, que es el siguiente:

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.3/blob/master/Img/3.1.jpeg)

Diagrama. Ejercicio 1  

2. Dibuje el diagrama de estados para la máquina de estado finito cuya tabla de estados es la siguiente. 
Partiendo del estado inicial s0, calcula la salida para la cadena de entrada abbccc.

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.3/blob/master/Img/3%20Dise%C3%B1o%203.PNG)

Tabla 2. Ejercicio 2

Desarrollo:

Como en el primer enunciado partimos del estado (S0) que es nuestro estado inicial. Para el siguiente estado que toma la maquina cuando toma el valor 
de a, en este caso S0, se genera una transición y colocamos la entrada y su correspondiente salida. Seguimos con el siguiente estado, deonde la maquina 
pasa de S0 a S3 ya que cuando toma el valor de B obtiene este estado, se toma en cuenta la transición y se realiza el mismo procedimiento para los demas estados. 
Y nos queda el siguiente diagrama.

diagrama ![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.3/blob/master/Img/3.2.jpeg)

Diagrama Ejercicio 2

3. Halle la tabla de estados para la máquina de estado finito cuyo diagrama de estados es:

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.3/blob/master/Img/3%20Dise%C3%B1o%205.PNG)

Diagrama. Ejercicio 3

Para construir la tabla, primero observamos el estado de inicio que es S0, el cual representa a nuestro primer estado, 
luego lo colocamos en el primera fila y columna de nuestra tabla de de estados. Ahora tomamos en cuenta el camino que nos presentan las flechas de entrada y salida. 
Para el caso de los estados actuales tomamos en cuenta los valores que se encuentran en el medio de las flechas, ya que representan nuestros estados actuales. 
Y nuestra tabla nos queda de la siguiente forma:

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.3/blob/master/Img/3%20Dise%C3%B1o%207.PNG)

Tabla 3. Ejercicio 3


4. Construya una máquina de estado finito que modele una máquina expendedora de bebidas que acepta monedas de 5, 10 y 20 centavos.
La máquina acepta monedas hasta que se introducen 25 centavos y devuelve cualquier cantidad que supere los 25 céntimos. 
Entonces, el cliente puede pulsar los botones y elegir una bebida de cola (C), cerveza (Z) o agua (A).


Realizamos una tabla para obtener nuestras variables que son las 3 diferentes monedas que podemos ingresar a la máquina.
Entonces asignamos variables a los diferentes valores en binario de la tabla anterior:

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.3/blob/master/Img/3%20Dise%C3%B1o%20maquina%201.PNG)

Tabla 4. Ejercicio 4

B: cero centavos en binario (000)
C: 5 centavos en binario (001)
D: 10 centavos en binario (010)
E: 15 centavos en binario (011)
F:20 centavos en binario (100)
G: Para más de 25 Ctvs

Ahora en nuestras salidas si D está encendido habrá cambio para el usuarion en centimos, y si D está apagado no abrá cambió.
También si C está encendido habrá bebida, y si C está apagado no abrá bebida.
Ahora procedemos a realizar la tabla de transición con nuestros estados de transición y de salida.

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.3/blob/master/Img/3%20Tabla%20maquina%201.PNG)

Tabla 5. Ejercicio 4

Realizamos nuestro diagrama de estados:

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.3/blob/master/Img/3.4.jpeg)

Diagrama de estados. Ejercicio 4

Tomamos en cuenta la entraga de las bebidas con la siguiente tabla

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.3/blob/master/Img/3%20Tabla%20%202%20maquina%201.PNG)


Tabla 5. Ejercicio 4

Entonces nuestra tabla de transición queda de la siguiente forma:

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.3/blob/master/Img/Tabla%20con%20bebidas.PNG)


5. Construya una máquina de estados finito que modele un circuito de riego automático como el mostrado en la figura. El circuito deberá accionar la bomba en las siguientes condiciones:

a. El circuito accionará la bomba solamente cuando la tierra esté seca, pero antes debe comprobar las siguientes condiciones:

i. Para evitar que la bomba se estropee por funcionar en vacío, nunca se accionará la bomba cuando el depósito de agua esté vacío.

ii. Si hay restricciones en el riego (época de verano), sólo se podrá regar de noche.

iii. En el resto del año (si no hay restricciones) se podrá regar de día y de noche (si la tierra está seca).

b. Para la implementación del circuito se dispone de las siguientes entradas:

i. S: Señal que indica si la tierra está seca: Tierra seca: S=1; Tierra húmeda: S=0

ii. R: Señal que indica si hay restricciones en el riego (es verano): Hay restricciones: R=1 No hay restricciones: R=0

iii. D: Señal que indica si es de día o de noche: Día: D=1; Noche: D=0

iv. V: Señal que indica si el depósito de agua está vacío: Vacío: V=1; Hay agua: V=0

c. Y la salida B, que accionará la bomba para regar: Bomba funcionando: B=1; Bomba apagada B=0.

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.3/blob/master/Img/3%20Enunciado%205.PNG)

Desarrollo:

Tenemos como condición que la bomba solo se activará cuando la tierra se encuentra seca. Tomando en cuenta también cuando esté húmeda.

Nuestro diseño tendrá una restricción para que en verano se active en la noche. En el esto del año se puede activar la bomba durante todo el día.

Nuestras variables serán:

S = 1 (tierra seca)

S = 0 (tierra húmeda)

Día: D=1

Noche: D=0

Vacío: V=1

Hay agua: V=0

Bomba funcionando: B=1

Bomba apagada B=0

Todas estas variables van a depender de si tienen restricciones previas.

Realizamos la tabla de cambio de estados:

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.3/blob/master/Img/Tabla%20final.PNG)


Tabla 6. Ejercicio 5


Ahora construimos el diagrama de estados:

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.3/blob/master/Img/3.5.jpeg)

Diagrama de estados. Ejercicio 5



                 
8.- DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

En este informe se ocupó la herramienta creately, que tiene la siguiente interfaz: 

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.3/blob/master/Img/a.PNG)

Como se observa primero hay que registrarse para poder comenzar a diseñar diagramas. Y ya solo es cuestión de dar clic en iniciar aplicación:


![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.3/blob/master/Img/c.PNG)

Ya podemos comenzar a diseñar. 

Para la aportacion ingresamos al siguiente link, en el que se debe tener ya una cuenta registrada, y así podremos simular la aportación:

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.3/blob/master/Img/Aportacion%20pagina.PNG)

Link: https://www.tinkercad.com/things/7gmmgvcxDMV-maquina-de-estado

9.APORTACIONES

Para nuestra aportación, diseñaremos un circuito secuencial para un led en el cual se pueda visualizar 3 colores distintos, uno a la vez; adicional del estado apagado; estos estados de colores deben ser cambiados con un pulsador; ayudarse con un arduino y los diagramas de estado para su realización.

Construimos nuestra de tabla de transición:

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.3/blob/master/Img/Aporte%206.jpeg)

Diagrama de estado

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.3/blob/master/Img/Aporte%205.jpeg)

Código del programa para el arduino

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.3/blob/master/Img/Aporte%203.jpeg)

 
![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.3/blob/master/Img/Aporte%202.jpeg)

Salidas finales que se obtendrán en los cambios de estado.

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.3/blob/master/Img/Aporte%201.jpeg)

Simulación ejemplo

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.3/blob/master/Img/Aporte%20simulaci%C3%B3n.PNG)


10.CONCLUSIONES

•	Los diagramas de estado es una manera sencilla para emular los cambios de movimiento entre estados de un circuito secuencial.
  
•	Con los diagramas de estado podemos analisar el movimiento de un objeto a travez de diverso estados a lo largo de su existencia.

•	El elemento de memoria de una máquina de estado contiene el valor de estado variable, cuando la máquina cuenta con los servicios, el estado variable es actualizado con el estado de la róxima etapa.  

• La máquina de estado de moore puede notar que no importa cual sea el estado de entrada ya que la salida depende del estado actual contenido dentro del estado de memoria.

• La máquina de estado de mealy su salida esta echa para depender de ambos, el estado actual y la entrada. 

12.RECOMENDACIONES

•	La representación de maquinas de estado se realiza mediante un diagrama de estado sin embargo tambien se puede utilizar un diagrama de flujo.

•	Se recomienda utilizar herramientas como creatly para el diseño de diagramas de estado. 

•	Se recomienda tener conocimientos previos sobre diagramas de estado y circuitos secenciales. 

•	Es preciso planificar un cronograma con diagramas de Grant en las diferentes aplicaciones que existen y para el desarrollo se recomienda el software Project. 



13.CRONOGRAMA

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.3/blob/master/Img/cronograma.PNG)


14.BIBLIOGRAFÍA

Alulema, D. (2020). Circuitos Digitales. Quito, Ecuador.

Floyd, T. (2006). Fundamentos de sistemas digitales. Madrid: Pearson.

Siliceo, R. (2018). Maquinas de estadp, diseño de grafos. Ciudad de Mexico.





