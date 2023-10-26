# JavaTrikiNetbeans
NetBeans
Para crear un juego de Triki en Java utilizando Netbeans, se deben seguir los siguientes pasos:

Crea un nuevo proyecto de tipo Aplicación Java en Netbeans y dale un nombre, por ejemplo, Triki.
Crea una clase llamada Triki que extienda de JFrame y que implemente la interfaz ActionListener. Esta clase será la ventana principal del juego y contendrá los elementos gráficos y la lógica del mismo.
Crea un atributo de tipo JButton[][] que represente el tablero de 3x3 del juego. Cada botón tendrá un texto vacío, un tamaño de 100x100 píxeles y un color de fondo blanco. También tendrán un ActionListener que llame al método jugar cuando se presionen.
Crea un atributo de tipo JLabel que muestre el turno del jugador, el ganador o el empate. Este label tendrá un tamaño de 300x50 píxeles y estará centrado en la parte inferior de la ventana.
Crea un atributo de tipo String que almacene el símbolo del jugador actual, ya sea “X” o “O”. Este atributo se inicializará con “X” y se alternará cada vez que se juegue un turno.
Crea un constructor para la clase Triki que inicialice los atributos y los añada al panel de contenido de la ventana. También configura las propiedades de la ventana, como el tamaño, el título, el cierre por defecto y la visibilidad.
Crea un método llamado jugar que reciba como parámetro el botón que se ha presionado. Este método debe comprobar si el botón está vacío y si es así, asignarle el símbolo del jugador actual, cambiar el turno del jugador y verificar si hay ganador o empate. Si el botón no está vacío, debe mostrar un mensaje de error.
Crea un método llamado verificarGanador que compruebe si hay alguna línea horizontal, vertical o diagonal formada por el mismo símbolo. Si es así, debe mostrar el mensaje de ganador y deshabilitar los botones. Si no hay ganador, debe llamar al método verificarEmpate.
Crea un método llamado verificarEmpate que compruebe si todos los botones están ocupados por algún símbolo. Si es así, debe mostrar el mensaje de empate y deshabilitar los botones.
