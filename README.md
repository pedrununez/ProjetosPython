# ProjetosPython
Aprendi a definir se o numero é impar ou par apartir de uma soma usando python

#Peça ao usuário para inserir dois números e, usando estruturas condicionais, determine e exiba se
#a soma dos números é par ou ímpar.
numero = int(input("insira primeiro numero\n"))
numero2 = int(input("insira primeiro numero\n"))
soma = numero + numero2
if soma % 2 == 0:
    print('numero par')
else:
    print('numero impar')
