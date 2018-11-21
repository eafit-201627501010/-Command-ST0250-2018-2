# Command-ST0250-2018-2
Son comandos que hacen un código mas fácil y útil sin usar redundante
## Integrantes
- David Sánchez Arboleda
- Mar Sánchez Fernández
- Federico Jaramillo Franco
## Nombre del patron de diseño
Command
## Explicacion
Las herramientas permiten que objetos hagan peticiones de objetos con aplicaciones sin especificar, envolviendo la solicitud en un objeto. Este objeto puede ser almacenado y pasado al igual que otros objetos de alrededor. La clave de este patrón es una clase abstracta Command, que declara una interfaz para la ejecución de operaciones. En la forma más simple esta interfaz incluye un resumen de las operaciones ejecutadas.
El patrón Command lo que permite es desacoplar al objeto que invoca a la operación de aquél que tiene el conocimiento necesario para realizarla.
## Modelo
## Lenguaje implementado
Java
## Ejecucion
•	Parametrizar objetos para llevar a cabo acciones, sobretodo objetos MenuItem.
•	Especificar, encolar, y ejecutar llamadas en diferentes momentos. Un objeto Comando puede tener una línea de vida independiente de la llamada original. Si el receptor del llamado puede ser representado como una dirección de espacio independiente, luego se puede transferir el objeto Comando para el llamado a un proceso diferente y realizar el llamado ahí.
•	Soporte deshacer. La operación ejecutarComando( ) puede almacenar estados para revertir efectos en el propio comando. La interfaz debe tener una operación adicional (unExecute) que reversa el efecto de una llamada previa a ejecutar. Los comandos ejecutados están almacenados en una lista de historial.
•	Soportar cambios en registro en las que se pueden reaplicar en caso de que el sistema colapse. Para agregar operaciones de cargar y guardar en la interfaz comando, se debe mantener un registro permanente de cambios. Recuperarse de un colapso requiere recargar los comandos de registro del disco y re ejecutarlos con la operación ejecutar.
•	Estructurar un sistema alrededor de operaciones de alto nivel construidas sobre operaciones primitivas ya que una estructura es común en los sistemas de información que soportan transacciones.
## Referencias
Codigofacil.com, youtube.com, libro programación/patrones





