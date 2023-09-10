# Função `input()`

A função builtin input() é usada quando desejamos ler dados da entrada padrão (teclado). Ela recebe um argumento do tipo string, que é exibido para o usuário na saída padrão (tela). A função lê a entrada, converte-a para uma string e retorna o valor.  

Exemplo de uso:

~~~Python
nome = input('Informe o seu nome: ')
print(nome)
~~~
> Informe o seu nome: Paulo  
> Paulo

# Função `print()`

A função builtin print() é usada quando desejamos exibir dados na saída padrão (tela). Ela recebe um argumento obrigatório do tipo varargs de objetos e quatro argumentos opcionais (sep, end, file e flush). Todos os objetos são convertidos para strings, separados por sep e terminados por end. A string final é exibida para o usuário.  

Exemplo de uso:

~~~Python
nome = 'Paulo'
sobrenome = 'Garba'

print(nome, sobrenome)
print(nome, sobrenome, end="...\n")
print(nome, sobrenome, sep"#")
~~~
> Paulo Garba  
> Paulo Alex...  
> Paulo#Garba