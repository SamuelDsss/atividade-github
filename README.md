# atividade-github
Este repositório contém a atividade prática sobre GitHub.

print('cédulas disponives : 50 , 20 , 10 e 5')

saque = int(input('Digite o valor desejado: '))
nota50 = 0
nota20 = 0
nota10 = 0
nota5  = 0
while(saque >= 5):
    if(saque >= 50):
        nota50 = nota50 + 1
        saque = saque - 50
    elif(saque >= 20):
        nota20 = nota20 + 1
        saque = saque - 20
    elif(saque >= 10):
        nota10 = nota10 + 1
        saque = saque - 10
    elif(saque >= 5):
        nota5 = nota5 + 1
        saque = saque - 5
print(nota50, nota20, nota10, nota5)
