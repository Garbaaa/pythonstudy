#  Operadores lógicos

## O que são?

Os operadores lógicos são utilizados em conjunto com os operadores de comparação para criar expressões lógicas que avaliam condições em programas Python. Quando um operador de comparação é usado, o resultado retornado é um valor booleano (True ou False). Portanto, podemos combinar operadores de comparação usando operadores lógicos para criar condições mais complexas. Por exemplo:

op_comparacao + op_logico + op_comparacao...N...

### Exemplo
~~~Python
saldo = 1000
saque = 200
limite = 100

saldo >= saque
>>> True 

saque <= limite
>>> False
~~~

### Operador `and` (E)

~~~Python
saldo = 1000
saque = 200
limite = 100

saldo >= saque  and saque <= limite
~~~
> False

Explicação simplificada.  
Imagine que você está contratando uma pessoa para um trabalho que requer fluência em inglês e português. Três candidatos comparecem para a entrevista.


| Nome  | Fala Inglês | Fala Português |
|-------|-------------|-----------------|
| Paula | Sim         | Não             |
| Joana | Não         | Sim             |
| João  | Sim         | Sim             |


Neste caso, você deseja uma pessoa que fale inglês "and" português. Quem dos candidatos seria escolhido ou receberia o emprego?   

**Resposta:**  
*João, porque ele fala inglês and português.*   

Em Python, usamos o operador and para representar a operação lógica "E". Em outras linguagens, como C, é comum usar && para a mesma operação.

### Operador `or` (OU)


~~~Python
saldo = 1000
saque = 200
limite = 100

saldo >= saque  or saque <= limite
~~~
> True

Explicação simplificada.  

Continuando com o exemplo anterior, agora você precisa contratar alguém que fale inglês "ou" português. Quais dos candidatos seriam possíveis novos funcionários da empresa?   

**Resposta:**   
*Todos eles seriam possíveis novos funcionários.*    

A única forma de exclusão nessa opção é se nenhum dos candidatos falar nenhuma das línguas desejadas ou atender às condições especificadas.  
Em Python, usamos o operador or para representar a operação lógica "OU". Este operador retorna True se pelo menos uma das condições for verdadeira.


### Operador `not` (NÃO)

O operador not é um operador lógico que nega o valor de uma expressão booleana. Ele inverte o valor booleano, tornando True em False e vice-versa.  
Exemplo: 

~~~Python
ativo = True
inativo = not ativo
print(inativo)

~~~
> False

**Explicação:**   

Neste exemplo, temos uma variável ativo que é definida como True, o que significa que algo está ativo. Em seguida, usamos o operador not para negar o valor de ativo, resultando em False. Portanto, a variável inativo se torna False.

O operador not é útil quando queremos verificar se algo não é verdadeiro. Ele pode ser usado para inverter condições e tomar decisões com base na negação de valores booleanos.

Em resumo, o operador not é uma ferramenta poderosa para lidar com valores booleanos, permitindo que você avalie negações de condições e crie lógica de decisão baseada na negação de estados booleanos.
