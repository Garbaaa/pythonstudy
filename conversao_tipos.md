# Conversão de tipos

Em alguns momentos, é necessário converter o tipo de uma variável para realizar operações específicas. Isso é especialmente relevante quando lidamos com variáveis do tipo string que armazenam números e precisamos realizar operações matemáticas com esses valores.  
Por exemplo:

~~~Python
a = input('Digite o valor para A ') #10
b = input('Digite o valor para B ') #20
print(a+b)
~~~
> 1020 

O resultado dessa operação é 1020, o que indica uma concatenação de strings. No entanto, nosso objetivo inicial era realizar uma operação matemática. Por que não conseguimos fazer isso?

A resposta está relacionada ao tipo de variável. Quando utilizamos a função `input()`, o tipo da variável é automaticamente definido como string (ou str). Portanto, para realizar operações matemáticas, precisamos converter o tipo da variável para um tipo numérico apropriado.

Podemos fazer isso usando funções de conversão, como `int()` ou `float()`, dependendo do tipo de cálculo que desejamos realizar.

Por exemplo, para realizar uma soma correta, devemos converter as variáveis a e b para inteiros:

~~~Python
a = int(input('Digite o valor para A ')) #10
b = int(input('Digite o valor para B ')) #20
print(a+b)
~~~
> 30  

Portanto, a conversão de tipos é essencial para garantir que possamos realizar as operações corretas com as variáveis, especialmente quando elas contêm dados de tipos diferentes.