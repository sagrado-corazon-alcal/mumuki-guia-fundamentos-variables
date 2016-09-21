Como viste en los ejercicios previos, con una **variable** podemos _etiquetar_ un **valor** para utilizarlo más tarde; esto se escribe, por ejemplo `numerito := 2`. A esta acción de **darle un valor** a una variable la llamamos **asignación**.

Algo importante es que una variable sólo puede etiquetar **un valor** a la vez, y cada vez que le asignamos un nuevo valor lo que había antes se pierde - podés pensarlo como una etiqueta real: sólo podés pegarla en un lugar a la vez. 

Veamos otro ejemplo:

```puppet
function direccionMisteriosa() {
  resultado := Norte
  resultado := Este
  resultado := Sur
  return (resultado)
}
```

> Al igual que en el ejercicio anterior, escribí en el editor el valor que creés que devuelve la función `direccionMisteriosa()`.