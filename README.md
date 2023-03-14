# tareabd
**Objetos en Python**

Un objeto es una concreción o instancia de una clase. Seguro que, si te digo que te imagines un coche, en tu mente comienzas a visualizar la carrocería, el color, las ruedas, el volante, si es diésel o gasolina, el color de la tapicería, si es manual o automático, si acelera o va marcha atrás, etc.

Pues todo lo que acabo de describir viene a ser una clase y cada uno de los de coches que has imaginado, serían objetos de dicha clase.

![](Aspose.Words.216abe6e-eca3-48a6-b9cd-8d656967fc3f.001.png)

El esquema anterior define la clase Coche (es una versión muy, muy simplificada de lo que es un coche, jajaja, pero nos sirve de ejemplo). Dicha clase establece una serie datos, como ruedas, color, aceleración o velocidad y las operaciones acelera() y frena().

Cuando se crea una variable de tipo Coche, realmente se está instanciando un objeto de dicha clase. En el siguiente ejemplo se crean dos objetos de tipo Coche:

\>>> c1 = Coche('rojo', 20)

\>>> print(c1.color)

rojo

\>>> print(c1.ruedas)

4

\>>> c2 = Coche('azul', 30)

\>>> print(c2.color)

azul

\>>> print(c2.ruedas)

4
