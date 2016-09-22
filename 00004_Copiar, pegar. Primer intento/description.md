Empecemos con un problema: tenemos una celda con una cierta cantidad de bolitas verdes y queremos _copiarlas_ en la celda inmediatamente al Este. Obviamente, no sabemos de antemano cuántas bolitas habrá y queremos escribir un procedimiento que nos sirva siempre, sin importar cuántas bolitas haya.

No queremos que te rompas la cabeza (por ahora :smirk:), así que te vamos a dar una solución por vos. Con lo que sabés hasta ahora, lo mejor que podrías hacer es esto:

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