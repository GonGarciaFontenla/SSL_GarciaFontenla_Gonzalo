# TaTeTi (3 en raya) - Simulación en C

Este programa simula el conocido juego "TaTeTi" o "3 en raya" utilizando el lenguaje de programación C. 

## Descripción

El programa consta de una serie de funciones que son fundamentales para su correcto funcionamiento:

### Funciones

- **Intro_Primer_Num:** Recibe el primer valor que ingresa el usuario.
  
- **tablero:** Muestra el tablero donde se va a jugar la partida. Se ejecuta varias veces para ir refrescando el tablero a medida que la partida avanza.
  
- **Enter_User:** Recibe los movimientos del usuario.
  
- **Enter_Machine:** Genera al azar los movimientos que hace el rival (la computadora).
  
- **ganador:** Determina si la partida finaliza en victoria, derrota o empate.
  
- **loop:** A partir de las funciones definidas anteriormente, las ejecuta en un ciclo hasta el final de la partida.

## Librerías Utilizadas

El programa utiliza las siguientes librerías:

- `time.h`
- `stdlib.h`
