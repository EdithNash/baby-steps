POO
--
Programacion Orientado a Objetos es un estilo de programar el cual nos permite plasmar otros tipos de datos para resolver los problemas de la vida real, es decir cualquier problema en el que nos enfrentemos podremos representarlo en código por medio de clases.

Todos los objetos tienen un conjunto de características que los identifican e igualmente tienen diferentes acciones.

**Clases**

Para poder crear estos objetos necesitaremos clases. Las **clases** son las estructuras de código que representaran nuestros objetos. 

Como mencionamos todos los objetos tienen características, estas serán representadas en las clases por medio de variables y las acciones que pueda realizar este objeto se podrán representar por medio de métodos.

**Instancias**

Sin embargo las clases solo son el concepto de nuestro objeto, para que podamos tener un objeto "real" necesitaremos crealo o como mejor se le conoce hacer una **instancia** de la clase. 

Con las instacias ya podemos hacer uso de nuestro objeto. Por ejemplo tenemos nuestra clase Rana (la cual hace representación del concepto de una rana, igual lo podemos ver como una plantilla)

Pilares de la Programación Orientada a Objetos
--
**Encapsulamiento**
--
La encapsulación define los niveles de acceso para elementos de esa clase.

Existen tres niveles de acceso:

**Público:** funciones de toda clase pueden acceder a los datos o métodos de una clase que se define con el nivel de acceso público. Este es el nivel de protección de datos más bajo

**Protegido:** el acceso a los datos está restringido a las funciones de clases heredadas, es decir, las funciones miembro de esa clase y todas las subclases

**Privado:** el acceso a los datos está restringido a los métodos de esa clase en particular. Este es nivel más alto de protección de datos

**Herencia**
--
La herencia es el mecanismo mediante el cual objetos más específicos(hijitos) incorporan la estructura y comportamiento
de elementos más generales(papá)

Gracias a la herencia es posible especializar o extender la funcionalidad de una clase, derivando de ella nuevas clases.

**Polimorfismo**
--
Se referire a la posibilidad de declarar métodos con el mismo nombre que pueden tener diferentes argumentos dentro de una misma clase.

Se puede clasificar el polimorfismo en dos clases:

• Polimorfismo dinámico (o polimorfismo paramétrico) es aquél en el que el código no incluye ningún tipo de especificación sobre el tipo de datos sobre el que se trabaja. Así, puede ser utilizado a todo tipo de datos compatible.

• Polimorfismo estático (o polimorfismo ad hoc) es aquél en el que los tipos a los que se aplica el polimorfismo deben ser explicitados y declarados uno por uno antes de poder ser utilizados.

**Abstracción**
--
La abstracción consiste en aislar un elemento de su contexto o del resto de los elementos que lo acompañan. En programación, el término se refiere al énfasis en el "¿qué hace?" más que en el "¿cómo lo hace?"

Podemos declarar metodos en una clase padre pero no especificamos como hacerlo hasta en las clases hijas lo indicamos.

A través de la abstracción conseguimos extraer las cualidades principales sin detenernos en los detalles.
