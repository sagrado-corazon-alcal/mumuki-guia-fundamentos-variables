Bueno, se acabó el juego. Hagamos ahora algo en serio.

Vamos a usar una celda del tablero para modelar el resultado de un partido entre [Racing](https://es.wikipedia.org/wiki/Racing_Club) e [Independiente](https://es.wikipedia.org/wiki/Club_Atlético_Independiente): las bolitas azules serán los goles del primero y las rojas serán los del segundo.

Por ejemplo, así se vería un partido en el que Racing metió 3 goles e Independiente 1:

<gs-board>
  GBB/1.0
    size 2 1
    cell 0 0 Rojo 1 Azul 3
    head 0 0
</gs-board>

> Tu trabajo será escribir la función `quienGano()`, que devuelva el **color** del equipo ganador. 

Para ahorrarte un poco de trabajo (y por si el fútbol no es lo tuyo) escribimos dos funciones en la Biblioteca; usalas en tu solución. 