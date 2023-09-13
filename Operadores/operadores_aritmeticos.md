# Operadores aritméticos

## O que são?
Os operadores aritméticos executam operações matemáticas, como adição, subtração com operandos. 

### Adição, subtração e multiplicação
- Adição:
~~~Python
print(1 + 1)
~~~
> 2  
- Subtração:
~~~Python
print(2 - 1)
~~~
> 1  
- Multiplicação:
~~~Python
print(4 * 2)
~~~
> 8

### Divisão e divisão inteira

- Divisão:
~~~Python
print(12 / 3)
~~~
> 4 
- Divisão inteira:
~~~Python
print(12 // 5)
~~~
> 2  

Observe que na divisão inteira, o resultado da divisão normal seria 2.4, mas ao usar //, obtemos o resultado inteiro da divisão.

### Módulo e exponenciação

- Módulo:
~~~Python
print(10 % 3)
~~~
> 1 
- Exponenciação:
~~~Python
print(2 ** 3)
~~~
> 8  

## Precedência dos operadores

Na matemática, há regras que indicam a ordem das operações a serem executadas. Isso é importante, pois a ordem das operações pode afetar o resultado.  
Por exemplo:

x = 10 - 5 * 2  
x é igual a 10 ou 0?

A regra geral é a seguinte ordem de precedência:  
- Parêntesis;
- Expoêntes;
- Multiplicações e devisões (da esquerda para a direita);
- Somas e subtrações (da esquerda para a direita).

Portanto, no exemplo acima, x é igual a 0.

~~~Python
print(10 - 5 * 2)
~~~
> 0

~~~Python
print((10 - 5) * 2)
~~~
> 10

~~~Python
print(10 ** 2 * 2)
~~~
> 200

~~~Python
print(10 ** (2 * 2))
~~~
> 10000

~~~Python
print(10 / 2 * 4)
~~~
> 20.0