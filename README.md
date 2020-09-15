                                                      **DIAGRAMAS DE MÁQUINAS DE ESTADO** 


** 1.PLANTEAMIENTO DEL PROBLEMA **

Se denomina máquina de estados a un modelo de comportamiento de un sistema con entradas y salidas en donde las salidas dependen 
no solo de las señales de entradas actuales, sino también de las anteriores. Tienes diversas aplicaciones en las que se puede utilizar como por ejemplo la realización de circuitos secuenciales. Para nuestro caso utilizaremos este método para resolver diversos problemas planteados.

** 2.OBJETIVOS **

Objetivo general

- Diseñar diagramas y tablas de de estado a partir de los datos propuestos en los ejerciciosos.

Objetivo específicos

-Investigar sobre circuitos secuenciales que se puedan implementar por medio de máquinas de estado.

-Desarrollar el diseño de las máquinas de estado mediante grafos.


** 3.ESTADO DEL ARTE **

En 2017 SANTIAGO GONZALEZ de la UNIDAD ACADÉMICA SANTIAGO DE CHILE DE INGENIERÍA EN CIENCIAS ECONOMICAS diseño la propia tienda On-Line tenga un carácter comercial para la empresa que vende los productos, y no sólo como un lugar donde realizar compras. Para ello, se tomaron decisiones como la de incluir información general de la empresa en las pantallas iniciales, inclusión de banner en la página, permitir que cualquier usuario pudiera navegar por el catálogo y los productos, pedir información sobre ellos, etc. Además, el hecho de registrarse en la web tendría otros añadidos para los usuarios aparte del propio de poder comprar como serían la descarga del catálogo completo o de partes de él en un formato fácilmente portable como es el PDF con la utilización de diagramas de estado (SANTIAGO GONZALEZ, 2017, p.1) [1].

En 2018 WILSON BALDEÓN Y VERONICA MORA de la ESCUELA SUPERIOR POLITECNICA DE CHIMBORAZO ubicado en Riobamba-Ecuador diseño un circuito secuencial sincrónico con los latch básicos, los latch asincrónicos y los ÁLSÁRSV, que son los elementos fundamentales a partir de los cuales se construyen máquinas secuenciales sincrónicas, el siguiente paso es el estudio de las técnicas de análisis y diseño de máquinas o circuitos secuenciales sincrónicos y asincrónicos. Una máquina secuencial, en general, se caracteriza porque los valores que se encuentran presentes en sus salidas, en algún instante, dependen no solamente de los valores que se encuentran presentes en sus entradas en ese instante, sino también, de todos los valores que estuvieron en esas entradas, es decir, de la historia pasada de esas entradas, valga la redundancia. Una máquina se llama secuencial porque, tiene que pasar, paso a paso, por un conjunto de estados. Si el paso de un estado a otro esta sincronizado por una señal de reloj, la máquina se llama secuencial sincrónica. Si la máquina no tiene una señal que sincronice los cambios de estado sino más bien los cambios de estado son realizados en el instante que alguna de sus señales de entrada ha cambiado, la máquina se llama secuencial asincrónica.  (WILSON BALDEÓN Y VERONICA MORA, 2018, p.1) [2].


** 4.MARCO TEÓRICO **


Falta ¡¡¡¡¡¡¡

** 5.DIAGRAMAS **

•Diagramas de bloques.


•Diagramas esquemáticos.





** 6.LISTA DE COMPONENTE **

- Diseñador de diagramas online creatly



** 7.MAPA DE VARIABLES **


Falta 


** 8.EXPLICACIÓN DEL DISEÑO **

** 1. Dibuje el diagrama de estados para la máquina de estado finito cuya tabla de estados es la siguiente. Partiendo del estado s0, calcula la salida para la cadena de entrada 1000110. **

tabla ![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.3/blob/master/Img/3%20Dise%C3%B1o%201.PNG)


** Desarrollo: **

Para construir el diagrama empezamos a partir de la tabla de transición que tenemos como dato, obervamos que en la primera fila significa nuestro estado inicial y estado actual, entonces cuando la máquina toma el valor de 0 pasa al siguiente estado obteniendo en su salida 1 que nos da el valor de S0. Ahora seguimos con el siguiente estado teniendo en cuenta que nuestro estado actual se encuentra con el valor valor de 1. Mediante esta mecánica seguimos con los siguientes estados para construir nuestro diagrama, que es el siguiente:

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.3/blob/master/Img/3.1.jpeg)

** 2. Dibuje el diagrama de estados para la máquina de estado finito cuya tabla de estados es la siguiente. Partiendo del estado inicial s0, calcula la salida para la cadena de entrada abbccc. **

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.3/blob/master/Img/3%20Dise%C3%B1o%203.PNG)

** Desarrollo: **

Como en el primer enunciado partimos del estado (S0) que es nuestro estado inicial. Para el siguiente estado que toma la maquina cuando toma el valor 
de a, en este caso S0, se genera una transición y colocamos la entrada y su correspondiente salida. Seguimos con el siguiente estado, deonde la maquina 
pasa de S0 a S3 ya que cuando toma el valor de B obtiene este estado, se toma en cuenta la transición y se realiza el mismo procedimiento para los demas estados. Y nos queda el siguiente diagrama.

diagrama ![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.3/blob/master/Img/3.2.jpeg)

** 3. Halle la tabla de estados para la máquina de estado finito cuyo diagrama de estados es: **

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.3/blob/master/Img/3%20Dise%C3%B1o%205.PNG)

Para construir la tablea, primero observamos el estado de inicio que es S0, el cual representa a nuestro primer estado, luego colocamos en el primera fila y columna de nuestra tabla de de estados. Ahora tomamos en cuenta el camino que nos presentan las flechas de entrada y salida. Para el caso de los estados actuales tomamos en cuenta los valores que se encuentran en el medio de las flechas, ya que representan nuestros estados actuales. Y nuestra tabla nos queda de la siguiente forma:

tabla ![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/Diagrama%20electrico.png)

4. Construya una máquina de estado finito que modele una máquina expendedora de bebidas que acepta monedas de 5, 10 y 20 centavos. La máquina acepta monedas hasta que se introducen 25 centavos y devuelve cualquier cantidad que supere los 25 céntimos. Entonces, el cliente puede pulsar los botones y elegir una bebida de cola (C), cerveza (Z) o agua (A).

Realizamos una tablar para obtener uestras variables que son las 3 diferentes monedas que podemos ingresar a la máquina:
Entonces asignamos variables a los diferentes valores en binario de la tabla anterior:
B: cero centavos en binario (000)
C: 5 centavos en binario (001)
D: 10 centavos en binario (010)
E: 15 centavos en binario (010)
F:20 centavos en binario (100)
G: Para más de 25 Ctvs
Ahora en nuestras salidas si D está encendido habrá cambio para el usuarion en centimos, y si D está apagado no abrá cambió.
También si C está encendido habrá bebida, y si C está apagado no abrá bebida.
Ahora procedemos a realizar la tabla de transición con nuestros estados de transición y de salida.

Tomamos en cuenta la entraga de las bebidas con la siguiente tabla


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

tabla

                 
9.- DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN

EL diseño de nuestro circuito sumador restador de 8 bits se lo implemento tanto en el simulador proteus como en el laboratorio virtual llamado constructor digital. Es por ello que el ususario que requiera revisar el funcionamiento debe tener instalado los dos simuladores, en la carpeta llamada instaladores se encuentra el archivo que se podrá descargar para poder visualizar el circuito implementado:

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/Conf%201.PNG)

Como se observa ya solo es necesario iniciar la aplicación del constructor virtual no necesita instalación, para abrir el archivo del diseño, tambien se encuentra en la carpeta instaladores, donde solo es un bloc de notas el cual contiene el codigo del circuito implementado, ese es el archivo que se debe abrir.

Aqui observamos la imagen del circuito en el laboratorio virtual:

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/Conf%203.PNG)

Nota: Es necesario tener instalado la versión 8.9 de proteus ya que si se desea abrir la simulación en versiones antiguas puede ocurrir errores o no abrir el archivo.

Aqui observamos la imagen del circuito en el simulador proteus:

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/Conf%202.PNG)


Es necesario que el usuario revise el datasheet de todos los circuitos integrados utilizados para que tenga una idea de que voltajes o corrientes soportan cada integrado, ademas de poder reconocer cada pin y cual es su función.
En el datasheet podemos obervar todas las especificaciones que se tomó en cuenta en el diseño, todo esto con el objetivo de no mostrar errores en la simulación del circuito, y tomando en cuenta a una posible implementación con integrados reales en un futuro. Estos documentos los puede encontrar en la carpeta llamada fichas tecnias, del repositorio.


10.APORTACIONES

Además de la implementación en el laboratorio virtual se realizó una simulación en el programa proteus, para comprobar el funcionamiento del circuito.

En la carpeta instaladores se encuentra el archivo que contiene la simulación en proteus.

Aquí observamos el circuito terminado en el simulador:

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/Conf%202.PNG)

En esta simulación podemos observar cada bloque del sumador restador.

Ejemplo de simulación:

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/aporte.PNG)

Suma de 11111111 + 11111111 (255 + 255).


11.CONCLUSIONES

•	La implementación del circuito Sumador/Restador nos ayudó a comprender no solo el funcionamiento de los integrados sumadores como el 74HC283, ya que también observamos como mediante   el   uso   de   los   elementos   MSI   podemos   llevar   a   cabo   procesos   más complejos de una forma más rápida y sencilla que al utilizar elementos SSI. Es por ello que se utilizó multiplexores y comparadores que nos ayudaron a reducir el tamaña del circuito.
  
•	Mientras más bits de código se quiera mostrar en displays, se requiere de un proceso más complicado, y en la vida real no existe integrados decodificadores de código binario a BCD.

•	En la realización de la simulación se pudo ratificar el funcionamiento de nuestro circuito sumador – restador, de entrada, tenemos dos números de 8 bits, lo cual nos dará una salida de hasta 9 bits en la mayor suma que se puede realizar.


12.RECOMENDACIONES

•	Debemos ser ordenados para armar el circuito para que si tenemos alguna falla podamos encontrar rápido el error.

•	Se recomienda no mezclar integrados de tecnología TTL con tecnología Cmos ya que sus diseños admiten diferentes valores de voltajes y corriente, en este diseño de lo realizo debido a la escasez de modelos de integrados en la plataforma de Tinkercad. 

•	Se recomienda tener conocimientos previos sobre circuitos sumadores y sus tablas de verdad, en conjunto con el datasheet de cada elemento que se usa en el circuito. 

•	Es preciso planificar un cronograma con diagramas de Grant en las diferentes aplicaciones que existen y para el desarrollo se recomienda el software Project. 



13.CRONOGRAMA

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/cronograma.JPG)


14.BIBLIOGRAFÍA

Alulema, D. (2020). Circuitos Digitales. Quito, Ecuador.

Floyd, T. (2006). Fundamentos de sistemas digitales. Madrid: Pearson.

Siliceo, R. (2018). Algoritmo de las operaciones aritmeticas aplicadas a los codigos binarios, octal, hexadecimal y BCD con sus respectivas conversiones. Ciudad de Mexico.



15.ANEXOS

15.1 MANUAL DE USUARIO

Para poder usar el circuito sumador - restador es necesario que el usuario este familiarizado con el código binario natural, a continuación dejamos una imagen en la que se puede observar una parte del cógido con sus equivalentes en decimal, ademas de el link para que el usuario pueda ver una la tabla completa del codigo binario natural.

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/manual%201.PNG)


En esta tabla se encuentran los números del 1 al 10, esto es necesario ya que para usar el circuito debera ingresar los números en código binario.

Aquie dejamos el link donde se encuentra una tabla más completa:

https://es.convertbinary.com/numeros/

Ahora para poder ingresar los números en código binario se lo hará mediante 8 switch, que corresponden a los 8 bits de que el usuario tiene permitido usar, es decir solo se puede sumar o restar números que no sobrepasen el valor de 255 (1111 1111), esto aplica tanto para la simulación en proteus y en el lab virtual.

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/manual%202.PNG)

Observamos la ubicación con su etiqueta donde el usuario debe ingresar los números en proteus.

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/manual%203.PNG)

Observamos la ubicación donde el usuario debe ingresar los números en el constructor virtual, en este caso el conjunto de switchs de la derecha corresponden al prmer número y el conjunto de la izquierda de la pantalla corresponden al segundo número.

Nota: Se debe tomar en cuenta que el switch final ubicado a la derecha corresponde al bit más significativo, y el switch final ubicado a la izquierda corresponde al bit menos significativo de los números a ingresar.

Para que el usuario puede observar el resultado ya sea de la suma o resta se debe escoger en un switch el cual controla la operación como vemos a continucación:

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/manual%204.PNG)


Para el caso de proteus.

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/manual%205.PNG)


Para el caso del constructor virtual. En este caso solo se encuentra habilitado el switch de la derecha, para el uso del control de operación.

Nota: El switch de control en estado abierto significa que el circuito mostrará la operación resta, si el switch se encuentra cerrado, el circuito mostrará la operación suma.


En el simulador proteus el usuario puede observar el resultado en displays de 7 segmentos como mostramos continuación:

![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/manual%206.PNG)


En el caso del constuctor virtual se observará en leds que corresponden al resultado en binario natural.


![alt text](https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Img/manual%207.PNG)



15.2 HOJAS TÉCNICAS

Datasheet 74HC4511

https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Hojas%20tecnicas/Datasheetcd4511b.pdf

Datasheet 7404

https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Hojas%20tecnicas/datasheet7404.pdf

Datasheet 7408

https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Hojas%20tecnicas/datasheet7408.pdf

Datasheet 74157

https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Hojas%20tecnicas/datasheet74157.pdf

Datasheet 74283

https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Hojas%20tecnicas/datasheet%207483.pdf

Datasheet 7485

https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Hojas%20tecnicas/datasheet7485.pdf

Display 7 segmentos

https://github.com/Proyecto-Digitales/PRODUCTO-UNIDAD-N.2/blob/master/Hojas%20tecnicas/TOS-5161AS-B_Oasis.pdf
