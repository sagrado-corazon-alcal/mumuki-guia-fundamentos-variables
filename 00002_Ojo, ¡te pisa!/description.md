Como recién viste, en una **variable** se puede _guardar_ un **valor** para utilizarlo más tarde; esto se escribe, por ejemplo `numerito := 2`. A esta acción de **darle un valor** a una variable la llamamos **asignación**.

Algo importante es que en una variable sólo puede guardarse **un valor**, y cada asignación _"pisa"_ a la anterior: lo que había antes se pierde. Vamos con otro ejemplo:

```puppet
function noHacerEstoTampoco() {
  numerito := 2
  numerito := 8
  numerito := 25
  return (numerito)
}
```

> Escribí en el editor el valor que creés que devuelve la función `noHacerEstoTampoco()`.