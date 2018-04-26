Como dijimos al principio, el cabezal de Gobstones sólo puede "mirar" la celda sobre la cual está parado y eso resulta incómodo si nuestro problema implica, por ejemplo, comparar cosas que están en celdas distintas. Sin embargo, ahora que conocemos una herramienta para **recordar** eso ya no será una dificultad. :smirk:

Para ejemplificar, tu tarea ahora será escribir la función `maximaCantidadDeBolitas` que indique cuál es la mayor cantidad de bolitas entre la celda actual y su vecina al Este. Por ejemplo, si en la celda actual hay 10 bolitas y en la de al lado 14, el resultado será 14.

<gs-board>
  GBB/1.0
  size 2 1
  cell 0 0 Rojo 4 Azul 6
  cell 1 0 Verde 10 Negro 4
  head 0 0
</gs-board>

Te damos como ayuda la función `nroBolitasTotal` que cuenta todas las bolitas de una celda y la función `maximo` que escribiste en el ejercicio anterior.