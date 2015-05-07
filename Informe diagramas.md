# TP 4 
## **Comparación de métodos para diagramar un algoritmo**

Existen varios métodos para diagramar un algoritmo, que varían en complejidad, requerimiento de conocimiento técnico, sencillez en la lectura, etc. 
Entre los más conocidos se encuentran:
* Diagrama de flujo
* Diagrama Nassi-Shneiderman
* Pseudocódigo
* Código fuente

### Diagrama de flujo
El diagrama de flujo es una representación gráfica de un algoritmo o proceso, que representa los flujos de trabajo paso a paso de los componentes de un sistema.
Utiliza flechas, bloques y rombos para dibujar el proceso, representando el avance con las flechas y con las figuras las estructuras de control.
#### Este método de diagramar posee ventajas y desventajas:
1. *Ventajas:*
  1. Es sencillo de leer siguiendo las flechas para evaluar los caminos del algoritmo.
  2. Los conocimientos técnicos necesarios para comprender la lectura son mínimos.
2. *Desventajas:*
  1. Si el algoritmo es muy largo, la lectura puede ser algo tediosa.
  2. Para lenguajes no estructurados, resulta prácticamente imposible diagramar con este método.

### Diagrama Nassi-Shneiderman
Representa la estructura de los algoritmos combinando la descripción textual del pseudocódigo con la representación gráfica del diagrama de flujo.
Posee un diseño *top down*, es decir que va de complejo a simple, diviendo el algoritmo en sub-algoritmos más pequeños y más simples.
Utiliza bloques anidados para representar cada algoritmo, donde cada estructura de control posee un tipo de bloque característico.
#### Las ventajas y desventajas que posee este método son:
1. *Ventajas:*
  1. Se puede analizar fácilmente cada paso que realiza el programa, al estar individualmente compartimentalizado.
2. *Desventajas:*
  1. Si el algoritmo es muy largo, el diagrama resultante acaba ocupando mucho espacio.
  2. Es requerimiento necesario conocer el significado de cada bloque, así como la forma de leerlo.
  2. Para lenguajes no estructurados, resulta prácticamente imposible diagramar con este método.

### Pseudocódigo
Consiste en una descripción compacta e informal de alto nivel de abstracción de un algoritmo.
Utiliza las convenciones estructurales de cualquier lenguaje real de programación, pero está adaptado para la lectura e interpretación humana.
#### Las ventajas y desventajas que posee este método son:
1. *Ventajas:*
  1. Es independiente del lenguaje en que se haya escrito el algoritmo.
  2. Al ser escrito en "lenguaje humano" permite la perfecta lectura y comprensión del algoritmo con mínimo conocimiento técnico previo.
  3. Puede utilizarse para programación estructurada, orientada a objetos, etc.
2. *Desventajas:*
  1. Es necesario realizar una conversión a un lenguaje de bajo nivel para que la computadora lo pueda procesar.

### Código
Consiste en escribir el algoritmo utilizando un lenguaje de bajo nivel, es decir, que pueda ser interpretado por la máquina.
Posee convenciones estructurales que ayudan a la codificación, así como a la comprensión de la lectura por parte de una persona.
#### Las ventajas y desventajas que posee este método son:
1. *Ventajas:*
  1. Lo que se escribe es directamente lo que la máquina puede comprender, dando menos espacio a ambigüedades.
  2. Puede utilizarse para programación estructurada, orientada a objetos, etc.
2. *Desventajas:*
  1. Cada lenguaje de programación posee su sintáxis específica.
  2. Es necesario conocer ampliamente el lenguaje de programación a utilizar para poder leer, interpretar y comprender el algoritmo.

## **Conclusión**
En lo personal, el método de diagramar depende mucho de cual sea el objetivo a alcanzar. 
Si el mismo consiste en comprender un proceso, los diagramas gráficos como el diagrama de flujo y el de Nassi-Shneiderman son los más claros, aunque mi preferencia personal es el diagrama de flujo debido a la extrema sencillez y claridad de su lectura.
Si se desea escribir un algoritmo para que sea interpretado por la computadora, escribir inicialmente en pseudocódigo es bastante práctico ya que sin aplicar la sintáxis específica del lenguaje, permite diseñar el algoritmo, evaluar su lógica y su procesamiento, y luego realizar el pasaje a código de bajo nivel a partir del pseudocódigo generado.