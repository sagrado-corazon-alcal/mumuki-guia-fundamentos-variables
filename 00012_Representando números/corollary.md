A esta idea de ir modificando una variable usando el valor que ya tenía y algo más se la suele conocer como **acumulador** o **contador**, y muchas veces en la comunidad se la sobreutiliza.

No caigas en el vicio de querer usar variables para todo, ¡no olvides todo lo que ya aprendiste y el poder de las funciones! Como siempre te decimos, la solución **más simple** es la mejor. Mirá cómo también se podría haber resuelto sin usar variables:

```puppet
function numero() {
  return (centena() + decena() + unidad())
}

function centena() {
  return (cifra() * 100)
}

function decena() {
  Mover(Este)
  return (cifra() * 10)
}

function unidad() {
  MoverN(2, Este)
  return (cifra())
}
```