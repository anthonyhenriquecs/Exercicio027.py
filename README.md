# Exercicio027.py
#Faça um programa que leia o nome completo de uma pessoa, mostrando em seguida o primeiro e o último nome separadamente.

n = str(input('digite seu nome: ')).strip()
nome = n.split()
print('Primeiro nome:{}'.format(nome[0]))
print('Ultimo nome: {} '.format(nome[len(nome)-1]))
