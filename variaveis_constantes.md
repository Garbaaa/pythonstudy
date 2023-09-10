# Variáveis
Em linguagens de programação, podemos definir valores que podem sofrer alterações durante a execução do programa. Esses valores recebem o nome de variáveis, pois eles nascem com um valor e não necessariamente devem permanecer com o mesmo valor durante a execução do programa.

Exemplos:

~~~Python
age = 23
name = 'Guilherme'
print(f'Meu nome é {name} e eu tenho {age} ano(s) de idade.')
~~~
> Meu nome é Guilherme e eu tenho 23 ano(s) de idade.

~~~Python
age, name= (23, 'Guilherme')
print(f'Meu nome é {name} e eu tenho {age} ano(s) de idade.')
~~~
> Meu nome é Guilherme e eu tenho 23 ano(s) de idade.

## Alterando os valores

Perceba que não precisamos definir o tipo de dados da variável; o Python faz isso automaticamente para nós. Por isso, não podemos simplesmente criar uma variável sem atribuir um valor. Para alterar o valor de uma variável, basta fazer uma atribuição de um novo valor:

~~~Python
age, name= (23, 'Guilherme')
print(f'Meu nome é {name} e eu tenho {age} ano(s) de idade.')
~~~
> Meu nome é Guilherme e eu tenho 23 ano(s) de idade.  

No mesmo programa podemos alterar o valor de *age* ou de *name*.
~~~Python
age, name= (31, 'Luis')
print(f'Meu nome é {name} e eu tenho {age} ano(s) de idade.')
~~~
> Meu nome é Luis e eu tenho 31 ano(s) de idade.

# Constantes

Assim como as variáveis, as constantes são utilizadas para armazenar valores. Uma constante nasce com um valor e permanece com ele até o final da execução do programa, ou seja, o valor é imutável.

## Python não tem constantes

Não existe uma palavra reservada para informar ao interpretador que o valor é constante. Em algumas linguagens, por exemplo, Java e C, utilizamos final e const, respectivamente, para declarar uma constante.  
Em Python, usamos a convenção que diz ao programador que a variável é uma constante. Para fazer isso, você deve criar a variável com o nome todo em letras maiúsculas:

~~~Python
ABS_PATH = '/home/guilherme/Documents/python/'
DEBUG = True
STATES = [
    'SP',
    'RJ',
    'MG',
]
AMOUNT = 30.2
~~~

# Boas práticas
- O padrão de nomes deve ser snake case.  
- Escolher nomes sugestivos.
- Nome de constantes todo em maiúsculo.
Exemplo: 
~~~Python
taxa_juros = 30%
age = 20
MAXIMO_TENTATIVAS_ENTRADA = 3
~~~