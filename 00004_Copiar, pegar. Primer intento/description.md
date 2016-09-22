Empecemos con un problema: tenemos una celda con una cierta cantidad de bolitas verdes y queremos _copiarlas_ en la celda inmediatamente al Norte. Obviamente, no sabemos de antemano cuántas bolitas habrá y queremos escribir un procedimiento que nos sirva siempre, sin importar cuántas bolitas haya.

Intentemos pensar la estrategia que seguiríamos:

1. Nos movemos al Norte, que es donde hay que poner las bolitas.
2. Una vez que estamos allí, ponemos la misma cantidad de bolitas que había en la celda inicial... pero, ¿cómo hacemos para saber eso si ya nos movimos y el cabezal sólo puede mirar la celda actual? :fearful:
3. Bueno, recordando que las funciones **no tienen efecto real** sobre el tablero, podríamos armar una función que vuelva al Sur y nos diga cuántas bolitas hay.
4. Ya con ese dato podemos hacer un viejo y querido `PonerN` y terminar nuestra tarea.

Un poco confuso, ¿no? :confused:

Como no queremos que te rompas la cabeza (por ahora :smirk:), te vamos a dar el código Gobstones que implementa nuestra estrategia para que lo pruebes:

```puppet
procedure CopiarVerdesAlNorte() {
  Mover(Norte)
  PonerN(bolitasVerdesAlSur(), Verde)
}

function bolitasVerdesAlSur() {
  Mover(Sur)
  return (nroBolitas(Verde))
}
```

> Copiá esta primera versión en el editor y mirá cómo cumple el objetivo.