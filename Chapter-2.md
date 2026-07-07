## Spanish - Español
# Capítulo 2 - Resolución de Problemas de IA
## Objetivos del capítulo
- Conocer un poco de la historia de algunos problemas y algoritmos que ayudaron a dar pasos en el desarrollo de la Inteligencia Artificial actual
- Explicar la lógica en la que se utiliza la teoría de grafos para simplificar y resolver problemas y acertijos de dificultad sencilla
- Entender como utilizar esa lógica para aplicarla a problemas de dificultad más avanzada y que se utilizan en algoritmos de Inteligencia Artificial 
- Utilizar y aplicar el algoritmo Minimax y los árboles de juego para entender la manera en que la Inteligencia Artificial puede "jugar" un juego determinista de ciertas características

## Conceptos Principales
### Espacio Estatal, Transiciones y Costos
Dentro del uso de la teoría de grafos para resolver problemas de lógica simple, se requiere llamar a cada nodo, a cada conexión y cada resultado del camino que se siguió por una manera específica. El espacio estatal es el conjunto de nodos o estados posibles en los que se puede encontrar el desarrollo del ejercicio. Las transiciones son las conexiones que hay entre un estado y otro, por ende, no todos los estados estan conectados entre sí. Y los costos son los peso que se le asignan a cada estado o a cada conexión dependiendo del tipo de juego o problema que estemos resolviendo.
#### Ejemplo Práctico 
Un acertijo común es el del barco, el zorro, el pollo y la comida para pollos. El acertijo dice que en el barco cabe la persona que lo maneja y uno de los otros elementos, y el objetivo es pasar todos los elementos sanos y salvos al otro lado del río. En este acertijo hay estados que no sirven, por ejemplo, no se pueden quedar sin vigilancia el zorro y el pollo o el pollo y la comida para pollos, debido a que uno de los elementos no sobreviviría. Las transiciones son los viajes del barco y los costos representan el estado en el que se encuentran los elementos. Al construir un diagrama de estados y conexiones, se puede determinar la ruta más corta para completar el acertijo. 

### Juego Determinista de Suma Cero para Dos Jugadores con Información Perfecta
Para lograr entender el siguiente concepto, es importante enfatizar en esta definición con anterioridad. Un juego con estas características específicas se refiere a un juego en el que el resultado no depende de suerte ni de probabilidades, simplemente de la lógica, participan dos jugadores por partida unicamente, la victoria de un jugador equivale exactamente a la derrota del otro, es decir, por una victoria no se suman puntos a ninguno de los dos jugadors, lo que hace del juego una suma cero. Además, no existen elementos de azar ni secretos en el juego, tales como tres en raya, ajedrez, entro otros. Con esta definición podemos entender el siguiente concepto.

### Algoritmo Minimax
El algoritmo Minimax es un algoritmo que sirve para que una máquina o Inteligencia Artificial logre llegar al final de un problema, en este caso un juego con las características anteriormente mencionadas, de la manera más sencilla y breve posible analizando todas y cada una de las posibilidades dentro de los estados y las transiciones disponibles. Poniendo por ejemplo el juego determinista, el algoritmo permite que a cada estado se le agregue un costo, (+1, -1 o 0) y llegue al estado con el costo final que desea. De esta manera, la IA analiza un árbol de juego, que no es más que un diagrama de estados y transiciones con los posibles mnovimientos del rival. Sin embargo, debido a los complejas problemas de la vida cotidiana, utilizar este algoritmo no siempre es sencille o la más fiable táctica dentro de una IA.

## Ideas para futuros proyectos
- Aplicar el algoritmo Minimax para crear un juego (de características anteriormente explicadas) en el que el jugador pueda competir contra la máquina. Se puede agregar interfaz gráfica y sistema de puntuación y registro de victorias propias. 

- Aplicar el algoritmo Minimax para implementarlo en una labor de búsqueda y análisis en el chatbot especializado en código (mencionado en la idea de proyectos del capítulo pasado), con el fin de determinar el camino más sencillo para corregir un error en el código.

## Conclusión
La IA, en sus funciones de busqueda y análisis, tiene complejos algoritmos para poder resolver distintons problemas de busqueda y análisis para una situación específica. Sin embargo, muchos de estos algoritmos para problemas simples se quedan cortos debido a la dificultad de algunos de los problemas que la vida cotidiana presenta. Es por esto, que es necesario entender y comprender varios algoritmos para que la IA tenga la capacidad de resolver estos problemas complejos. 

## English - Inglés
# Chapter 2 - AI Problem Solving

## Chapter Objectives
- To learn a little about the history of some problems and algorithms that helped advance the development of modern Artificial Intelligence
- To explain the logic behind using graph theory to simplify and solve simple problems and puzzles
- To understand how to apply this logic to more advanced problems used in Artificial Intelligence algorithms
- To use and apply the Minimax algorithm and game trees to understand how Artificial Intelligence can "play" a deterministic game with certain characteristics

## Main Concepts
### State Space, Transitions, and Costs
When using graph theory to solve simple logic problems, each node, connection, and outcome along the path must be named in a specific way. The state space is the set of all possible nodes or states in which the problem can be solved. Transitions are the connections between states; therefore, not all states are connected. Costs are the weights assigned to each state or connection, depending on the type of game or problem being solved.

#### Practical Example
A common riddle is the boat, fox, chicken, and chicken feed puzzle. The riddle states that the boat can hold the person piloting it and one of the other items, and the goal is to get all the items safely to the other side of the river. In this puzzle, some states are unusable. For example, the fox and the chicken, or the chicken and the chicken feed, cannot be left unattended because one of the elements would not survive. The transitions represent the ship's journeys, and the costs represent the state the elements are in. By constructing a state and connection diagram, the shortest path to complete the puzzle can be determined.

### Deterministic Zero-Sum Game for Two Players with Perfect Information
To understand the next concept, it's important to emphasize this definition beforehand. A game with these specific characteristics refers to a game where the outcome doesn't depend on luck or probability, but simply on logic. Only two players participate per game, and one player's victory is exactly equivalent to the other's defeat; that is, neither player scores points for a win, making it a zero-sum game. Furthermore, there are no elements of chance or secrets in the game, unlike games like tic-tac-toe, chess, and others. With this definition, we can understand the next concept.

### Minimax Algorithm
The Minimax algorithm is an algorithm that allows a machine or Artificial Intelligence to reach the end of a problem—in this case, a game with the characteristics mentioned above—in the simplest and shortest way possible by analyzing each and every possibility within the available states and transitions. Taking the deterministic game as an example, the algorithm allows each state to have a cost (+1, -1, or 0) and reach the state with the desired final cost. In this way, the AI ​​analyzes a game tree, which is simply a diagram of states and transitions showing the opponent's possible moves. However, due to the complexity of everyday problems, using this algorithm is not always simple or the most reliable tactic for an AI.

## Ideas for Future Projects
- Apply the Minimax algorithm to create a game (with the characteristics explained previously) in which the player can compete against the computer. A graphical interface and a scoring system for recording wins can be added.

- Apply the Minimax algorithm to implement a search and analysis task in the chatbot specializing in code (mentioned in the project ideas of the previous chapter), in order to determine the simplest path to correct a code error.

## Conclusion
AI, in its search and analysis functions, has complex algorithms to solve various search and analysis problems for a specific situation. However, many of these algorithms for simple problems fall short due to the difficulty of some everyday problems. Therefore, it is necessary to understand and comprehend various algorithms so that AI has the capacity to solve these complex problems.
