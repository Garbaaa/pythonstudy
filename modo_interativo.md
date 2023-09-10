# Modo Interativo em Python
O interpretador Python oferece a possibilidade de os desenvolvedores escreverem código e verem os resultados imediatamente, o que é extremamente útil para experimentações rápidas e testes. Este recurso é conhecido como "modo interativo".

### Iniciando o Modo Interativo
Existem duas maneiras de iniciar o modo interativo: executando o interpretador Python diretamente digitando "python" no terminal ou usando o script com a opção -i (por exemplo, "python -i app.py").

No Visual Studio Code, no Prompt de Comando do Windows ou no Terminal do Linux, você pode iniciar o modo interativo digitando simplesmente "python". Isso abrirá uma sessão interativa onde você pode inserir código Python diretamente e ver os resultados imediatamente. Para sair do modo interativo, você pode digitar "exit()" e pressionar Enter, o que encerrará a sessão interativa.

O modo interativo é uma ótima maneira de testar pequenos trechos de código, depurar problemas ou experimentar funcionalidades do Python sem a necessidade de criar um programa completo. É uma ferramenta valiosa para desenvolvedores Python em todos os níveis de experiência.

## Função `dir()`

A função `dir()` é uma função incorporada do Python que pode ser usada de duas maneiras distintas.

### Sem argumentos

Quando chamada sem argumentos, a função `dir()` retorna uma lista de nomes no escopo local atual. Isso significa que você receberá uma lista de todos os nomes de variáveis, funções e objetos disponíveis no ambiente em que a função foi chamada. Isso é útil para explorar o escopo atual do seu código.

Exemplo:  
dir() # Retorna uma lista de nomes no escopo local atual
- ['\_\_annotations\_\_', \_\_builtins\_\_',\_\_doc\_\_',\_\_loader\_\_',\_\_name\_\_',\_\_package\_\_',\_\_spec\_\_']  
Supondo que eu adicione um **import math** ou qualquer outro import, ele irá aparecer ali.


### Com um argumento

Quando chamada com um argumento, a função `dir()` retorna uma lista de atributos válidos para o objeto especificado como argumento. Isso é especialmente útil quando você deseja descobrir quais métodos e atributos estão disponíveis para um objeto específico.

Exemplo:  
dir(100) # Retorna uma lista de atributos válidos para o objeto 100

- ['\_\_abs\_\_', '\_\_add\_\_', '\_\_and\_\_', '\_\_bool\_\_', '\_\_ceil\_\_', '\_\_class\_\_', '\_\_delattr\_\_', '\_\_dir\_\_', '\_\_divmod\_\_', '\_\_doc\_\_', '\_\_eq\_\_', '\_\_float\_\_', '\_\_floor\_\_', '\_\_floordiv\_\_', 
'\_\_format\_\_', '\_\_ge\_\_', '\_\_getattribute\_\_', '\_\_getnewargs\_\_', '\_\_getstate\_\_', '\_\_gt\_\_', '\_\_hash\__\', '\_\_index\_\_', '\_\_init\_\_', '\_\_init_subclass\_\_', '\_\_int\_\_', '\_\_invert\_\_', '\_\_le\_\_', '\_\_lshift\_\_', '\_\_lt\_\_', '\_\_mod\_\_', '\_\_mul\_\_', '\_\_ne\_\_', '\_\_neg\_\_', '\_\_new\_\_', '\_\_or\_\_', '\_\_pos\_\_', '\_\_pow\_\_', '\_\_radd\_\_', '\_\_rand\_\_', '\_\_rdivmod\_\_', '\_\_reduce\_\_', '\_\_reduce_ex\_\_', '\_\_repr\_\_', '\_\_rfloordiv\_\_', '\_\_rlshift\_\_', '\_\_rmod\_\_', '\_\_rmul\_\_', '\_\_ror\_\_', '\_\_round\_\_', '\_\_rpow\_\_', '\_\_rrshift\_\_', '\_\_rshift\_\_', '\_\_rsub\_\_', '\_\_rtruediv\_\_', 
'\_\_rxor\_\_', '\_\_setattr\_\_', '\_\_sizeof\_\_', '\_\_str\_\_', '\_\_sub\_\_', '\_\_subclasshook\_\_', '\_\_truediv\_\_', '\_\_trunc\_\_', '\_\_xor\_\_', 'as_integer_ratio', 'bit_count', 'bit_length', 'conjugate', 'denominator', 'from_bytes', 'imag', 'numerator', 'real', 'to_bytes'] 

## Função `help()`

A função help() é uma função incorporada do Python que permite acessar o sistema de ajuda integrado da linguagem. Ela é usada para obter informações sobre módulos, funções, classes, métodos ou variáveis do Python. A função help() pode ser usada de duas maneiras diferentes.

### Modo Interativo

Quando chamada sem argumentos, a função help() entra no modo interativo de ajuda, permitindo que você explore a documentação e obtenha informações sobre qualquer parte do Python. Você pode navegar pelas informações de ajuda digitando comandos interativos, como nomes de módulos, funções ou tópicos que deseja explorar. Para sair do modo interativo de ajuda, basta pressionar a tecla "q".

Exemplo:

`help()`  # Entra no modo interativo de ajuda  
Esse modo é basicamente uma documentação offline do Python.

### Especificando um Argumento

Você também pode usar a função help() especificando um argumento, como um nome de módulo, função, classe, método ou variável, para obter informações detalhadas sobre esse elemento específico. Isso é útil quando você deseja uma descrição completa e exemplos de uso de um objeto em particular.

Exemplo:

`help(100)` # Obtém informações sobre o objeto 100  
Ao fornecer um argumento para a função help(), você receberá a documentação relacionada a esse objeto, se estiver disponível. Isso pode incluir descrições, parâmetros, retornos e exemplos de uso.

A função help() é uma ferramenta poderosa para explorar e entender a documentação do Python e pode ser particularmente útil para aprender sobre novas bibliotecas, entender a sintaxe de funções e métodos e solucionar problemas ao trabalhar com a linguagem Python.
