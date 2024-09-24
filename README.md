'''Escreva um programa em python que pergunte ao usuário a velocidade de um carro. 
Caso ultrapasse 80 km/h, exiba uma mensagem dizendo que o usuário foi multado. 
Nesse caso, exiba o valor da multa, cobrando R$20,00 por cada km que exceder 80 km/h.'''

velocidade = int(input("Em que velocidade está o carro?: "))
numero = velocidade - 80
multa = numero * 20
if velocidade > 80:
    print("O usuário foi multado")
    print("O valor da sua multa é R$:",multa)
else:
    print("Parabens! Você está dentro do limite de velocidade.")
