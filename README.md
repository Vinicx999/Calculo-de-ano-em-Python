# Calculo-de-ano=em-Python

#Código
nome = input("Digite seu nome: ")
idade = int(input("Digite sua idade: "))
saldo = float(input("Digite seu saldo: "))
perc = int (input("Digite o percentual de aumento: "))
ano = 2023 - idade
saldopc = (saldo*perc)/100 + saldo


#Print
print (nome, "o seu saldo é: ", saldo)
print (nome, "o seu saldo com acréscimo de", perc, "é: ", saldopc)
print (nome, "o ano que você nasceu é: ",2023 - idade) 
print (f"Você {nome} que nasceu em {ano} terá um saldo de {saldopc}R$ ,devido ao aumento de {perc}%")
