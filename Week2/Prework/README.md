# ECC-Laboratoria  (Prework Week2)

### Preguntas de Prework

1. Entra a https://www.hackingwithswift.com/sixty y en la página [online.swiftplayground.run](http://online.swiftplayground.run/) haz las siguientes secciones:

2. 1. Complex Types
   2. Operators and conditions
   3. Looping
   4. Functions
   5. Structs
   
3. Entra a https://developer.apple.com/design/human-interface-guidelines/ios/overview/themes/ y contesta lo siguiente:

4. 1. Enlista y describe los temas principales de diseño
   
      - **Claridad.** En todo el sistema, el texto es legible en todos los tamaños, los iconos son precisos y lúcidos, los adornos son sutiles y apropiados, y un enfoque más agudo en la funcionalidad motiva el diseño. El espacio negativo, el color, las fuentes, los gráficos y los elementos de la interfaz resaltan sutilmente el contenido importante y transmiten interactividad.
      - **Deferencia.** El movimiento fluido y una interfaz nítida y hermosa ayudan a las personas a comprender e interactuar con el contenido sin competir nunca con él. El contenido generalmente llena toda la pantalla, mientras que la translucidez y el desenfoque a menudo sugieren más. El uso mínimo de biseles, degradados y sombras paralelas mantiene la interfaz clara y aireada, a la vez que garantiza que el contenido sea primordial.
      - **Profundidad.** Las capas visuales distintas y el movimiento realista transmiten jerarquía, imparten vitalidad y facilitan la comprensión. El tacto y la capacidad de detección aumentan el placer y permiten el acceso a la funcionalidad y al contenido adicional sin perder contexto. Las transiciones proporcionan una sensación de profundidad a medida que navega por el contenido.
   
      ## 
   
   2. Enlista y describe los principios de diseño
   
      ### Integridad estética
   
      La integridad estética representa lo bien que la apariencia y el comportamiento de una aplicación se integran con su función. Por ejemplo, una aplicación que ayuda a las personas a realizar una tarea seria puede mantenerlos enfocados mediante el uso de gráficos sutiles y discretos, controles estándar y comportamientos predecibles. Por otro lado, una aplicación inmersiva, como un juego, puede ofrecer una apariencia cautivadora que promete diversión y emoción, al tiempo que fomenta el descubrimiento.
   
      ### Consistencia
   
      Una aplicación coherente implementa estándares y paradigmas familiares mediante el uso de elementos de interfaz proporcionados por el sistema, iconos conocidos, estilos de texto estándar y terminología uniforme. La aplicación incorpora características y comportamientos de la manera que las personas esperan.
   
      ### Manipulación directa
   
      La manipulación directa del contenido en pantalla involucra a las personas y facilita la comprensión. Los usuarios experimentan una manipulación directa cuando giran el dispositivo o usan gestos para afectar el contenido en pantalla. A través de la manipulación directa, pueden ver los resultados inmediatos y visibles de sus acciones.
   
      ### Realimentación
   
      La retroalimentación reconoce acciones y muestra resultados para mantener informadas a las personas. Las aplicaciones integradas de iOS proporcionan comentarios perceptibles en respuesta a cada acción del usuario. Los elementos interactivos se resaltan brevemente cuando se tocan, los indicadores de progreso comunican el estado de las operaciones de larga duración, y la animación y el sonido ayudan a aclarar los resultados de las acciones.
   
      ### Metáforas
   
      Las personas aprenden más rápidamente cuando los objetos y acciones virtuales de una aplicación son metáforas de experiencias familiares, ya sea enraizadas en el mundo real o digital. Las metáforas funcionan bien en iOS porque las personas interactúan físicamente con la pantalla. Mueven las vistas para exponer el contenido debajo. Arrastran y deslizan el contenido. Alternan interruptores, mueven controles deslizantes y se desplazan por los valores del selector. Incluso hojean páginas de libros y revistas.
   
      ### Control de usuario
   
      En todo iOS, las personas, no las aplicaciones, tienen el control. Una aplicación puede sugerir un curso de acción o advertir sobre consecuencias peligrosas, pero generalmente es un error que la aplicación se haga cargo de la toma de decisiones. Las mejores aplicaciones encuentran el equilibrio correcto entre habilitar a los usuarios y evitar resultados no deseados. Una aplicación puede hacer que las personas sientan que tienen el control manteniendo elementos interactivos familiares y predecibles, confirmando acciones destructivas y facilitando la cancelación de operaciones, incluso cuando ya están en marcha.
   
   3. Dentro de la sección de **User Interaction**, describe lo siguiente:
   
   4. 1. Authentication
   
         Solicite a los usuarios que se autentiquen solo a cambio de valor, como personalizar la experiencia, acceder a funciones adicionales, comprar contenido o sincronizar datos. Si su aplicación requiere autenticación, use Iniciar sesión con Apple para ofrecer a las personas una forma simple y segura de iniciar sesión. Cuando admite Iniciar sesión con Apple, las personas obtienen una experiencia de inicio de sesión consistente en la que pueden confiar y la comodidad de no tener que recordar Múltiples cuentas y contraseñas.
   
         **Si no usas Iniciar sesión con Apple, usa Password AutoFill.** Esta característica genera y completa automáticamente contraseñas y códigos de seguridad para que las personas puedan pasar menos tiempo en las pantallas de autenticación. Todas las aplicaciones deberían ser compatibles con esta función. 
   
      2. Data Entry
   
         Ya sea tocando elementos de la interfaz o usando el teclado, ingresar información puede ser un proceso tedioso. Cuando una aplicación ralentiza el proceso al pedir mucha información antes de hacer algo útil, las personas pueden desanimarse rápidamente e incluso pueden abandonar la aplicación por completo.
   
         **Cuando sea posible, presente opciones.** Haga que la entrada de datos sea lo más eficiente posible. Considere usar un selector o una tabla en lugar de un campo de texto, por ejemplo, porque es más fácil elegir de una lista de opciones predefinidas que escribir una respuesta.
   
         **Obtenga información del sistema siempre que sea posible.** No obligue a las personas a proporcionar información que se pueda recopilar automáticamente o con el permiso del usuario, como información de contacto o calendario.
   
      3. Gestures
   
         Las personas interactúan con un dispositivo iOS realizando gestos en la pantalla táctil. Estos gestos provocan una estrecha conexión personal con el contenido y mejoran la sensación de manipulación directa de los objetos en pantalla.
   
         **Como regla general, use gestos estándar.** Las personas están familiarizadas con los gestos estándar y no aprecian verse obligados a aprender diferentes formas de hacer lo mismo. En los juegos y otras aplicaciones inmersivas, los gestos personalizados pueden ser una parte divertida de la experiencia. En otras aplicaciones, es mejor usar [gestos estándar](https://developer.apple.com/design/human-interface-guidelines/ios/user-interaction/gestures/#standard-gestures) para que no sea necesario un esfuerzo adicional para descubrirlos o recordarlos.
   
   5. Dentro de la sección de **Visual Design**, describe lo siguiente:
   
   6. 1. Adaptability and Layout
   
         - Esta sección describre los diferentes tipos de resolución de pantalla que existen en los dispositivos iOS.
   
           Existe una herramienta llamada Auto Layout que sirve para construir interfaces adaptativas. En esta herramienta también podemos poner restricciones o reglas que rigen el contenido de nuestra aplicación.
           Ajusta automaticamente el diseño de la aplicación de acuerdo a las restricciones de acuerdo a los cambios en el ambiente (rasgos).
           Existe una amplia gama de rasgos :
   
           - Diferente tamño de pantalla, resoluciones y gama de colores.
           - Vista dividida
             Diferentes orientaciones del dispositivo(vertical y horizontal) 
           - Multiarea
   
         Tiene algunas consideraciones generales de diseño 
   
         1. Asegúrese de que el contenido primario sea claro en su tamaño predeterminado.
         2. Mantenga una apariencia general consistente en toda su aplicación.
         3. Utilice el peso visual y el equilibrio para transmitir importancia. 
         4. Utilice la alineación para facilitar el escaneo y para comunicar la organización y la jerarquía.
         5. Si es posible, admite las orientaciones vertical y horizontal.
         6. Esté preparado para los cambios de tamaño de texto. 
         7. Proporcione objetivos táctiles amplios para elementos interactivos.
         8. Obtenga una vista previa de su aplicación en múltiples dispositivos.
         9. Aplique márgenes de legibilidad al mostrar texto en dispositivos más grandes. 
   
      2. Branding
   
         Da recomendaciones al usuario de como agregar un sello único a la aplicación, sin perder de vista el diseño discreto y elegante. 
   
         **Incorpora una marca refinada y discreta.**
   
         Se refiere a dar al usuario una familiariadad con la plicació con ciertos detalles que la hagan única pero sin caer en los excesos, ya que puede llegar a ser un distractor.
   
         **No permita que la marca se interponga en el camino del excelente diseño de la aplicación.**
   
         Quiere decir que tengamos en cuenta las guías de diseño de iOS. Debe ser intuitiva, de fácil navegación, fácil de usar y el comtenido centrado.
   
         **Diferir al contenido sobre la marca.**
   
         Se tienen que considerar formas muy poco invasivas para definir la marca. Que sea algo muy sutil para que esto no interfiera con el diseño y el contenido.
   
      3. Color
   
         El color es un excelente comunicador y nos ayuda a dar vitalidad y a darle contexto al usuario sobre lo que esta pasando acerca de la aplicación . Un excelente aliado para ayudar a que nuestra aplicación sea más intuitiva.
   
         **Use el color juiciosamente para la comunicación.**
         Se recomienda usar el color de manera cautelosa, ya que el uso demasiado de alguno en especifico puede ser demasiado habitual para el usuario y generar conflictos al momento de presentar un error.
   
         **Use colores complementarios en toda su aplicación.**
         Usar colores que no causen conflicto entre si para generar un buen ambiente al usuario.
   
         **Evite usar el mismo color para elementos interactivos y no interactivos.**
         Esto puede perder al usuario en la plicación y dejaría de ser intuitiva.
   
         **Evite usar colores que dificulten que las personas perciban contenido en su aplicación.**
         Se debe de evitar que el color del texto se difumine con el color de fondo. Pero también existen personas con algún impedimento visual que pueden usar nuestra aplicación y se debe de tomar en cuenta.
   
   7. Dentro de la sección de **Controls**, describe lo siguiente:
   
   8. 1. Buttons
   
         - Los botones inician acciones especificas de nuestra aplicación. 
           Se proporcionan varios diseños predefinidos o también se pueden hacer personalizados.
   
         Existen diferentes tipos de botones, pero cada uno tiene un propósito en especifico. Además se debe buscar que el texto de los botones sea corto y sea de acuerdo a la acción que ejecuta.
   
      2. Labels
   
         Un label describe un elemento en la pantalla o proporciona un mensaje corto.
         Son elementos que los usuarios no pueden modificar y ofrecen un texto corto.
   
         Es importante mantener las etiquetas legibles, esto quiere decir que se entienda el texto de la misma y respetar el tipo de fuente o el texto en ella.
   
5. Enlista tus 10 apps favoritas

   - Instagram

   - YouTube

   - WhatsApp

   - Facebook

   - Spotify

   - Netflix

   - Clue

   - Uber 

   - Maps

   - Messenger

     

6. Enlista y describe los cuatro pilares de la programación orientada a objetos

   ###### **Abstracción**

   Este permite identificar las características y comportamientos de un objeto y con los cuales se construirá la clase. A través de este fundamento es posible reconocer los atributos y métodos de un objeto.

   ###### **Encapsulamiento**

   Es la característica de la POO que permite el ocultamiento de la complejidad del código, pertenece a la clase privada de la clase y que no puede ser vista desde ningún otro programa.

   El encapsulamiento está relacionado con el acceso a un código desde el código de otra clase.

   ###### **Herencia** 

   Es el pilar más fuerte que asegura la reutilización de código, ya que a partir de esta característica es posible reutilizar (heredar) las características y comportamientos de una clase superior llamada clase padre, a sus clases hijas.

   Esto implica que las características heredadas de la clase padre, no se vuelvan a definir, sino con el simple hecho de ser heredadas se pueden utilizar y en el caso de comportamientos ejecutarlos o modificarlos.

   ###### **Polimorfismo** 

   A través de esta característica es posible definir varios métodos o comportamientos de un objeto bajo un mismo nombre, de forma tal que es posible modificar los parámetros o reescribir su funcionamiento, o incrementar más funcionalidades a un método.

   

7. Dentro del paradigma de programación orientada a objetos:

8. 1. ¿Qué es un objeto?

      Es la unidad individual que en tiempo de ejecución realiza las tareas de un programa. Estos objetos interactúan unos con otros, en contraposición a la visión tradicional en la cual un programa es una colección de subrutinas (funciones o procedimientos), o simplemente una lista de instrucciones para el computador. Cada objeto es capaz de recibir mensajes, procesar datos y enviar mensajes a otros objetos de manera similar a un servicio.

   2. ¿Qué es una clase?

      Una clase es la declaración de un tipo de objeto. Las clases son similares a los  tipos abstractos de datos y equivalen a modelos que describen cómo se construyen ciertos tipos de objetos. Cada vez que se construye un objeto a partir de una clase estamos creando lo que se llama una **instancia** de esa clase.

      Una clase, por el contrario, describe una familia de elementos similares. En la practica, una clase es un esquema o plantilla que se usa para definir o crear objetos.

   3. ¿Qué es un método?

      Son aquellas funciones que permite efectuar el objeto y que nos rinden algún tipo de servicio durante el transcurso del programa.
      Determinan a su vez como va a responder el objeto cuando recibe un mensaje.

   4. ¿Qué es una propiedad?

      Una propiedad es un identificador con un determinado tipo de dato que accede normalmente a un campo en forma directa o a través de un método.

      Lo más adecuado si queremos implementar correctamente la programación orientada a objetos es que los campos sean privados y si necesitamos acceder a ellos se haga mediante propiedades.

      Una propiedad nos permite agregar un método que valide si el dato que queremos asignar a la propiedad se puede almacenar en el campo.

9. Investiga y describe la arquitectura de diseño MVC

   El MVC o Modelo-Vista-Controlador es un patrón de arquitectura de software que, utilizando 3 componentes (Vistas, Models y Controladores) separa la lógica de la aplicación de la lógica de la vista en una aplicación. Es una arquitectura importante puesto que se utiliza tanto en componentes gráficos básicos hasta sistemas empresariales

   

   ![img](https://codigofacilito.com/photo_generales_store/29.jpg)

   

    el **MVC**,  nos permite separar los componentes de nuestra aplicación dependiendo de la responsabilidad que tienen, esto significa que cuando hacemos un cambio en alguna parte de nuestro código, esto no afecte otra parte del mismo. 

   MODELO

   Se encarga de los datos, generalmente (pero no obligatoriamente) consultando la base de datos. Actualizaciones, consultas, búsquedas, etc. todo eso va aquí, en el modelo.

   CONTROLADOR

   Se encarga de... controlar, recibe las órdenes del usuario y se encarga de solicitar los datos al modelo y de comunicárselos a la vista.

   VISTAS

   Son la representación visual de los datos, todo lo que tenga que ver con la interfaz gráfica va aquí. Ni el modelo ni el controlador se preocupan de cómo se verán los datos, esa responsabilidad es únicamente de la vista.

10. ¿Qué es un ViewController?

    Es un elemento que nos permite combinar contenido de diferentes view controllers,dentro una única interfaz.

    Facilitan la navegación y permiten crear nuevos tipos de interfaces, basándonos en contenido ya existente.

    Un container view controller es como cualquier otro view controller. Gestiona una vista principal y algo de contenido. La diferencia es que un container view controller obtiene parte de su contenido de otros view controllers. Ese contenido proviene de las views de otros view controllers, que además están incluidas en su propia jerarquía de vistas.

    cada uno de los view controllers que gestionamos desde el container view controller es conocido como Child View Controller.

    El container view controller establece el tamaño y posición de cualquier child view controller, pero es el propio child view controller quien gestiona el contenido que se muestra en su view.

    

11. ¿Qué es un Storyboard?

      El Storyboard es un conjunto imágenes mostradas en secuencia, con el fin de previsualizar una animación o cualquier otro medio gráfico o interactivo.

    Básicamente el stoyboard es un guion gráfico, que nos permite la previsualización de nuestra multimedia antes de que se terminada. En este se plantean las ideas principales de nuestro guion técnico y literario, en este se dejan en claro los detalles de cada escena.

    se introdujeron en iOS 5 como una forma de renovar el diseño de la interfaz para iOS. En ese momento, no agregaron muchas funciones que no estaban disponibles con las XIB más antiguas, pero en versiones posteriores Apple ha agregado nuevas funciones útiles, como guías de diseño que las hacen mucho más útiles, y posiblemente indispensables desde iOS 7)

12. ¿Qué es un IBAction?

    Actions

    Una acción es un pedazo de código que está vinculado a algún tipo de evento que puede ocurrir en la aplicación. Cuando ese evento tiene lugar, el código de la acción es ejecutado. Se puede definir una acción para prácticamente cualquier cosa, desde manipular datos o actualizar interfaz de usuario, etc. Utilizaremos las acciones para conducir la ejecución de la aplicación en **respuesta a eventos** del usuario o del sistema.

    Una acción es una función, básicamente, la cual señalamos con la etiqueta @IBAction:

    ![IBAction](http://www.kamyacademy.com/wp-content/uploads/2014/09/IBAction.png)

    **IBAction** es como la palabra clave void, simplemente indica que el método es una acción y que se puede conectar con el storyboard Interface Builder (de ahi el prefijo IB).

13. ¿Qué es un IBOutlet?

    Outlets

    Los Outlets son el modo de hacer referencia a los objetos de la interfaz (los objetos que has añadido a su storyboard) desde el código fuente. Puedes crear un Outlet presionando Control y arrastrando el objeto en particular desde tu storyboard al archivo del view controller.

    Esto crea una propiedad para el objeto en el archivo de view controller, lo que le permite acceder y manipular ese objeto desde el código en tiempo de ejecución.

    [![Outlet](http://www.kamyacademy.com/wp-content/uploads/2014/09/Outlet.png)](http://www.kamyacademy.com/wp-content/uploads/2014/09/Outlet.png)

    La palabra reservada IBOutlet le dice al Xcode que te puedes conectar a esta propiedad desde Interface Builder.

    

14. ¿Qué es la notación CamelCase y cuáles son sus tipos? ¿Conoces otro tipo de notación?

15. ¿Qué es un IDE y cuáles son sus elementos principales?