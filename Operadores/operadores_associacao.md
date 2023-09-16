# Operadores de associação

## O que são?

São operadores utilizados para verificar se um objeto está presente em uma sequênca.

~~~Python
curso = "Curso de Python"
frutas = ['laranja','uva','limão']
saques = [1500, 100]

'Python' in curso
>>> True

"maçã" not in frutas
>>> True

200 in saques
>>> False
~~~

**Explicação:**  
Neste exemplo, utilizamos os operadores de associação para verificar a presença de elementos em diferentes sequências: 

- `'Python' in curso`: Aqui, estamos verificando se a substring `'Python'` está presente na string `curso`. Como `'Python'` está dentro de `curso`, o resultado é `True`.

- `"maçã" not in frutas`: Neste caso, estamos usando o operador `not in` para verificar se a string `"maçã"` não está presente na lista `frutas`. Como `"maçã"` não está na lista, o resultado é `True`.

- `200 in saques`: Aqui, estamos verificando se o número `200` está presente na lista `saques`. Como `200` não está na lista, o resultado é `False`.

Os operadores de associação são úteis para realizar verificações de pertencimento em sequências, permitindo que você saiba se um elemento específico está contido em uma lista, string, tupla ou qualquer outra estrutura iterável. Eles são amplamente utilizados em Python para tomada de decisões com base na presença ou ausência de elementos em uma sequência.
 