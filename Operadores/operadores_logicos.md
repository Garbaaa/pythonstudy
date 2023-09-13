#  Operadores lógicos

## O que são?

São operadores utilizados em conjunto com os operadores de comparação, para montar uma expressão lógica. Quando um operadores de comparação é utilizado, o resultado retronado é um booleano, dessa forma podemos combinar operadores de comparação com os operadores lógicos, Exemplo:  
op_comparacao+op_logico+op_comparacao...N...

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

### Operador and (e)

~~~Python
saldo = 1000
saque = 200
limite = 100

saldo >= saque  and saque <= limite
~~~
> False

Explicação simplificada.  
Eu estou contratando e quero uma pessoa que fale inglês e português, três pessoas vieram fazer a entrevista.


Fala | Inglês | Português
 |---|---|---|
Paula  | Fala|  Não fala
Joana   |  Não fala | fala
Jõao  | Fala | fala

Nesse caso, eu quero uma pessoa que fale inglês "and" português, quem dessas pessoas levaria um "true" ou ganharia o novo emprego?  
*O João, por que ele fala inglês and português.*  
No python, ultilizamso o and para representar o operador and, mas em C, por exemplo, ultilizamos o &&.

### Operador or (ou)


~~~Python
saldo = 1000
saque = 200
limite = 100

saldo >= saque  or saque <= limite
~~~
> True

Explicação simplificada.  

Seguindo o mesmo exemplo anterior, só que agora eu preciso de alguém que fale ou inglês ou português. 
Quais seriam os possiveis novos empregados da empresa?  
*Todos seriam possiveis empregados*  
A unica forma de exclusão nessa opção é se não houver nenhuma das linguas que estou querendo, ou condições. 
