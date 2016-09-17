Aunque no lo dijimos de manera explícita, seguramente ya te diste cuenta: las variables son también **expresiones**, y por lo tanto pueden usarse en los mismos lugares que todas las que ya conocías:

* como **argumentos** de funciones o procedimientos;
* en un `repeat`, indicando cuántas iteraciones hará;
* en un `if` o `while`, como parte de la condición;
* y como valor de retorno de una función.

Y claro, también pueden usarse en una **asignación**, o sea que ¡le asignamos un valor a una variable usando una variable! :fearful:

Veamos algunos ejemplos de esto:

<table class="table table-striped">
  <tr>
    <th>Código</th>
    <th>Valor de `cuantoVale`</th>
  </tr>
  <tr>
    <td>```puppet
una := 25
cuantoVale := una * 2```
    </td>
    <td>50</td>
  </tr>
</table>

