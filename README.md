# War Horses

Es un juego entre dos adversarios en el que cada uno controla un caballo sobre
un tablero de ajedrez. Las casillas que alcance cada caballo se pintan de un color (rojo o verde)
y no podrán ser usadas por ninguno de los jugadores. En el tablero hay tres casillas especiales
o bonos. Si un caballo alcanza una casilla especial pinta de su color la casilla donde se encontraba
el bono y las cuatro casillas adyacentes que no hayan sido pintadas. Si cuando sea el turno de
un jugador, éste no puede hacer ningún movimiento porque no tiene casillas disponibles, el
adversario podrá volver a mover su caballo. El juego termina cuando ninguno de los dos jugadores
pueda moverse. Gana el juego quien pinte más casillas con su color. A continuación se muestra
un posible estado del juego después de que cada jugador ha realizado dos movimientos.



War horses presenta tres niveles de dificultad (principiante, amateur, y experto) que el usuario
puede seleccionar al iniciar el juego. Se debe construir un árbol minimax con decisiones
imperfectas. La profundidad límite del árbol depende del nivel seleccionado por el usuario. Para
el nivel principiante se utiliza un árbol de profundidad 2, para amateur de profundidad 4, y para
experto de profundidad 6.

##Aclaraciones generales

- El juego siempre lo inicia la máquina quien jugará con el caballo que pinta las casillas de rojo
- Las posiciones iniciales de los caballos son aleatorias
- Las posiciones de las tres casillas con bono son aleatorias, pero no pueden quedar en casillas
adyacentes (incluidas las diagonales)
- Se debe mostrar en cada momento la cantidad de casillas que cada jugador ha pintado
- Al final del juego se debe indicar quién es el ganador
