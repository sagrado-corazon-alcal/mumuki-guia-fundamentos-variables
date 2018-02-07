Te toca ahora escribir una función que _decodifique_ un número de tres cifras guardado en el tablero, como por ejemplo 514:

<gs-board>
  GBB/1.0
    size 3 1
    cell 0 0 Rojo 5
    cell 1 0 Rojo 1
    cell 2 0 Rojo 4
    head 0 0
</gs-board>

Como ves en la imagen, cada una de sus tres cifras aparece en una celda distinta, y la lectura se hace de izquierda a derecha (o sea, como leemos normalmente en esta parte del mundo). El cabezal va a empezar siempre en el origen.

La idea es que uses una **variable** para ir armando el número, sumando cada una de sus cifras. Como experimentaste en el ejercicio anterior, en una asignación se puede usar el valor que ya tenía la variable, y de esta forma ir **acumulando** un resultado.

> Escribí la función `numero()`, que devuelva el número codificado en el tablero. Para leer cada una de sus cifras del tablero, te regalamos una función `cifra()`, buscala en la Biblioteca.