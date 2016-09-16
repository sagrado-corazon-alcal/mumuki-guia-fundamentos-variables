Como viste en los ejercicios previos, en una **variable** se puede _guardar_ un **valor** para utilizarlo más tarde; esto se escribe, por ejemplo `numerito := 2`. A esta acción de **darle un valor** a una variable la llamamos **asignación**.

Algo importante es que en una variable sólo puede guardarse **un valor** a la vez, y cada asignación _"pisa"_ a la anterior: lo que había antes se pierde. Vamos con otro ejemplo:

```puppet
function feoFeoFeo() {
  sinSentido := Norte
  sinSentido := Este
  sinSentido := Sur
  return (sinSentido)
}
```

> Escribí en el editor el valor que creés que devuelve la función `feoFeoFeo()`.