# -*- coding: utf-8 -*-

#**Calculadora Inteligente**
"""

#calculadora inteligente

#Recebendo números do usuário
num1 = float(input('Digite o primeiro número:'))
num2 = float(input('Digite o segundo número:'))

#Escolher a operação
print('Escolha a operação:')
print('1 - Soma')
print('2 - Subtração')
print('3 - Multiplicação')
print('4 - Divisão')

operação = input('Digite a operação Desejada (1/2/3/4):')

#Usando Condicional para realizar a operação
if operação == '1':
   resultado = num1 + num2
   print(f'O resultado da soma é: {resultado}')
elif operação ==  '2':
   resultado = num1 - num2
   print(f'O resultado da Subtração é: {resultado}')
elif operação == '3':
   resultado = num1 * num2
   print(f'O resultado da Multiplicação é: {resultado}')
elif operação == '4':
   if num2 != 0:
      resultado = num1 / num2
      print(f'A divisão é: {resultado}')
   else:
      print(f'Erro! Não é possível dividir por zero')
else:
  print(f'Operaçao Inválida! Escolha entre 1,2,3 ou 4.')
