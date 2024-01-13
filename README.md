# Juego del Ahorcado

Esta es una implementación simple del clásico juego del Ahorcado en Python. El juego selecciona una palabra al azar, y el jugador debe adivinar las letras para descubrir la palabra oculta.

## Cómo Jugar

1. Ejecuta el script de Python `hangman.py`.
2. El juego mostrará el estado inicial con guiones representando las letras de la palabra oculta.
3. Ingresa una letra cuando se te solicite.
4. Sigue adivinando letras hasta que descubras la palabra o te quedes sin intentos.

## Descripción del Código

El código está organizado en funciones para diferentes aspectos del juego:

- `elegir_palabra`: Selecciona una palabra al azar de una lista predefinida.
- `pedir_letra`: Recibe la entrada del usuario para una letra, asegurándose de que sea una única letra válida.
- `mostrar_nuevo_tablero`: Muestra el estado actual de la palabra con letras reveladas y guiones.
- `chequear_letra`: Verifica si la letra adivinada es correcta, actualiza el estado del juego y determina si se ha ganado o perdido.
- `perder`: Muestra un mensaje cuando el jugador se queda sin intentos.
- `ganar`: Muestra un mensaje cuando el jugador adivina correctamente la palabra.

## Uso

1. Clona el repositorio:

   ```bash
   git clone https://github.com/tuusuario/juego-ahorcado.git
