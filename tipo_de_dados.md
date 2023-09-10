
# Tipos de dados em Python

## 📚 Por que usamos tipos de dados?

Os tipos servem para definir as caracteristicas e comportamentos de um valor (objeto) para o interpretador.  
Por exemplo:  
- Com esse tipo eu sou capaz de realizar operações matemáticas. (inter ou float) 
- Esse tipo para ser armazenado em memória irá consumir 24 bytes.

## Os tipos built-in são:
    

| Dado| Tipo | 
|--- |--- |
| Texto | str |
| Númerico | int, float, complex |
| Sequência | list, tuple, range |
| Mapa | dict |
| Coleção | set, fronzenset |
| Booleano | bool |
| Binário | bytes, bytearray, memoryview |

## Números inteiros
Números interiso são representados pela classe **int** e possuem precisão ilimitada.  
São exemplos válidos de números inteiros:  
- 1, 10, 100, -1, -10, -100... 99001823

## Números de ponto flutuante 
Números de ponto flutuante são usados para representar os números racionais e sua implementação é feita pela classe **float**.  
São exemplos válidos de números de ponto flutuante:
- 1.5, -10.543, 0.76... 997532.032

## Booleano
É usado para representar verdadeiro ou falso, e é implementado pela classe **bool**. Em Python o tipo booleano é uma subclasse de **int**, uma vez que qualquer número diferente de 0 representa verdadeiro e 0 representa falso.  
São exemplos válidos de booleanos: 
- True e False

## Strings 
Strings ou cadeia de caracteres são usadas para representar valores alfanúmerico, em Python as strings são definidas utilizando a classe **str**.  
São exemplos válidos de string:
- "Python", 'Python', """Python""", ""Python"", "p"