# Tarea Reservas de Aulas
## Profesor: Andrés Rubio del Río
## Alumno: Ezequiel Expósito Lara.

Desde el IES Al-Ándalus nos acaban de comentar que por favor eliminemos la restricción de tamaño en los datos de la aplicación. Por lo que decidimos utilizar estructuras dinámicas de datos, en concreto Listas. Para las diferentes clases del modelo que contienen las colecciones de objetos del dominio (las que están incluidas en el paquete **dao**) deberemos sustituir los **Array** por **ArrayList** y, cómo no, ajustar los diferentes métodos para que sigan haciendo lo mismo que antes, pero utilizando las nuevas estructuras de datos. Como observarás, los métodos privados que teníamos antes desaparecen ya que ahora no serán necesarios.

El diagrama de clases queda como te muestro a continuación y poco a poco te iré explicando los diferentes pasos a realizar:

![Diagrama de clases para reservasaulas](src/main/resources/reservasAulas.png)

He subido a GitHub un esqueleto de proyecto gradle que ya lleva incluidos todos los test necesarios que el programa debe pasar. Dichos test están todos comentados y deberás ir descomentándolos conforme vayas avanzando con la tarea. La URL del repositorio es en la que te encuentras.

Por tanto, tu tarea va a consistir en completar los siguientes apartados:

1. Lo primero que debes hacer es realizar un fork del repositorio donde he colocado el proyecto gradle con la estructura del proyecto y todos los test necesarios.
2. Clona tu repositorio remoto recién copiado en github a un repositorio local que será donde irás realizando lo que a continuación se te pide. Añade tu nombre al fichero `README.md` en el apartado "Alumno". Haz tu primer commit.
3. Modifica la clase `Aulas` para que utilice un `ArrayList` en vez de un `Array`. Modifica también los métodos, eliminando los necesarios, para que sigan haciendo lo mismo pero utilizando esta estructura. Ten en cuenta que el método `representar` ahora también devuelve una lista. Haz un commit.
4. Modifica la clase `Profesores` para que utilice un `ArrayList` en vez de un `Array`. Modifica también los métodos, eliminando los necesarios, para que sigan haciendo lo mismo pero utilizando esta estructura. Ten en cuenta que el método `representar` ahora también devuelve una lista. Haz un commit.
5. Modifica la clase `Reservas` para que utilice un `ArrayList` en vez de un `Array`. Modifica también los métodos, eliminando los necesarios, para que sigan haciendo lo mismo pero utilizando esta estructura. Ten en cuenta que el método `representar` ahora también devuelve una lista. Haz un commit.
6. Haz los ajustes necesarios en la clase `IUTextual` para que todo siga funcionando igual. Haz un commit.



###### Se valorará:
- La nomenclatura del repositorio de GitHub y del archivo entregado sigue las indicaciones de entrega.
- La indentación debe ser correcta en cada uno de los apartados.
- El nombre de las variables debe ser adecuado.
- Se debe utilizar la clase `Entrada` para realizar la entrada por teclado.
- El proyecto debe pasar todas las pruebas que van en el esqueleto del mismo y toda entrada del programa será validada para evitar que el programa termine abruptamente debido a una excepción.
- Se deben utilizar los comentarios adecuados.
- Se valorará la corrección ortográfica tanto en los comentarios como en los mensajes que se muestren al usuario.

