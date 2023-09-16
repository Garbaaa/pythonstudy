# Operadores de identidade

## O que são?

Os operadores de identidade são utilizados para comparar se dois objetos testados ocupam a mesma posição na memória. Eles verificam se duas variáveis ou objetos fazem referência ao mesmo local de memória, ou seja, se são essencialmente o mesmo objeto.

Exemplo: 

~~~Python
estudo = 'Estudo de Python'
nome_estudo = estudo
saldo, limite = 200, 200

estudo is nome_estudo
>>> True

estudo is not nome_estudo
>>> False

saldo is limite
>>> True
~~~

**Explicação:**  
Neste exemplo, temos três situações diferentes:

- `estudo is nome_estudo`: Aqui, `estudo` e `nome_estudo` apontam para a mesma string na memória, então o resultado é `True`. Eles são essencialmente o mesmo objeto.

- `estudo is not nome_estudo`: Neste caso, estamos negando a condição anterior. Como `estudo` e `nome_estudo` apontam para o mesmo objeto, a negação é `False`.

- `saldo is limite`: No contexto das variáveis `saldo` e `limite`, ambos têm o mesmo valor (`200`). Portanto, `saldo is limite` retorna `True`.

Os operadores de identidade são úteis quando você deseja verificar se duas variáveis se referem ao mesmo objeto na memória. Isso é comumente usado para evitar copiar objetos desnecessariamente e economizar espaço na memória quando se trabalha com tipos imutáveis em Python.