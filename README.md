Cómo ejecutar la calculadora:
Primero ingresar un número.
Segundo seleccionar una operación (suma, resta, multiplicación y división). Al seleccionar una operación se limpia la pantalla.
Tercero ingresar el segundo número para realizar el cálculo.

Configuración del proyecto:
La interfaz gráfica se crea utilizando una tabla de cuatro filas y cuatro columnas.
Se dan estilos a la tabla mediante la clase "calculadora"
Se dan estilos a los botones de las columnas de la tabla, mejorando gráfica de la de calculadora.
Se agregan estilos para crear el display de la claculadora, con el ID "resultado".
La funcionalidad se logra mediante tres variables principales: una que almacena el operandoA al presionar el boton de operación, otra que almacena el tipo de operación justo en el mismo momento cuando se almacena el operandoA, el operandoB se guarda al presionar el boton de igual y en este mismo momento se manda llamar la función resolver.
Al momento de llamar a la función resolver se cuenta ya con operandoA, operandoB y operación por lo que únicamente se calcula el resultado.
