# Operadores de atribuição

## O que são?

Os operadores de atribuição são utilizados para definir o valor inicial de uma variável ou sobrescrever o valor existente.

### Atribuição simples 
~~~Python
saldo = 500
print(saldo)
~~~
> 500  

Perceba que quando usamos apenas um sinal de igual (=), podemos ler como "recebe" ou "atribui". Portanto, a linha de código acima pode ser lida como "saldo recebe 500".

### Atribuição com adição

~~~Python
saldo = 500
saldo += 200
print(saldo)
~~~
> 700  

Neste caso, o saldo inicialmente recebeu 500, mas em seguida recebeu mais 200, resultando em um total de 700, como indicado na saída do programa.

### Atribuição com subtração

~~~Python
saldo = 500
saldo -= 100
print(saldo)
~~~
> 400  

Aqui, o saldo inicialmente recebeu 500, mas depois foi subtraído 100, resultando em um saldo de 400, como mostrado na saída do programa.

### Atribuição com multiplicação

~~~Python
saldo = 500
saldo *= 2
print(saldo)
~~~
> 1000

Novamente, o saldo inicialmente é 500, mas desta vez é multiplicado por 2, resultando em um saldo de 1000.

### Atribuição com divisão

~~~Python
saldo = 500
saldo /= 5
print(saldo)
~~~
> 100.0

~~~Python
saldo = 500
saldo //= 5
print(saldo)
~~~
> 100

Nesses casos, o saldo inicial é 500 e, em seguida, há uma atribuição de divisão, uma normal (com decimais) e uma com divisão inteira, resultando na divisão do saldo pelo número especificado.

### Atribuição com módulo/resto

~~~Python
saldo = 500
saldo %= 480
print(saldo)
~~~
> 20

Da mesma forma que os exemplos anteriores, mas usando o operador de módulo, que retorna o resto da divisão.

### Atribuição com exponenciação

~~~Python
saldo = 80
saldo **= 2
print(saldo)
~~~
> 6400

Mais uma vez, seguindo o mesmo padrão dos outros operadores, mas usando a exponenciação para elevar o saldo ao quadrado.