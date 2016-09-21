Como viste en los ejercicios previos, con una **variable** podemos _etiquetar_ un **valor** para utilizarlo más tarde, escribiendo por ejemplo `numerito := 2`. A este comando que sirve para **darle un valor** a una variable lo llamamos **asignación** y lo escribimos `:=` (_dos puntos igual_).

Una variable sólo puede etiquetar **un valor**, y cada vez que le asignamos uno nuevo el anterior se pierde - podés pensarlo como una etiqueta real: sólo podés pegarla en un lugar a la vez. 

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