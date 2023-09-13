# Operadores de atribuição

## O que são?

São operadores utilizados para definir o valor inicial ou sobrescrever o valor de uma variável.

### Atribuição simples 
~~~Python
saldo = 500
print(saldo)
~~~
> 500  

Perceba que quando tiver somente um sinal de igual(=), se lê como "recebe" ou "atribui", então a leitura da primeira linha do codigo seria "saldo recebe 500". 

### Atribuição com adição

~~~Python
saldo = 500
saldo += 200
print(saldo)
~~~
> 700  

Aqui percebemos que o saldo recebeu 500, mas após isso o saldo recebeu mais 200, totalizando 700, que foi o print do programa.

### Atribuição com subtração

~~~Python
saldo = 500
saldo -= 100
print(saldo)
~~~
> 400  

Aqui percebemos que o saldo recebeu 500, mas após isso o saldo recebeu menos 100, totalizando 400 que foi a saida do programa.

### Atribuição com multiplicação

~~~Python
saldo = 500
saldo *= 2
print(saldo)
~~~
> 1000

Novamente o saldo recebe 500, só que agora ele recebe uma multiplicação por 2, o que ocasiona em um saldo de 1000.

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

Aqui seguimos o mesmo padrão dos demais, saldo inicial 500, recebe uma atribuição de divisão, uma inteira e uma com decimais, resultando na divisão do saldo pelo numero que foi colocado nessa atribuição.

### Atribuição com módulo/resto

~~~Python
saldo = 500
saldo %= 480
print(saldo)
~~~
> 20

seguindo o mesmo padrão dos demais, só que ultilizando o resto.

### Atribuição com exponenciação

~~~Python
saldo = 80
saldo **= 2
print(saldo)
~~~
> 6400

seguindo o mesmo padrão dos demais, só que ultilizando o expoente.
