#Registros dos exercícios de meus estudos em Python

# Exercício 1: criar um "Alô mundo"

print ("Olá! Eu estou de volta e ainda sou digno. ^^)")

# Exercício 2: Pedir um número e mostrá-lo em seguida.

n = input ("Digite um número: ") #entrada
print ("O número digitado foi",n,".") #saída
#observação: a frase da saída fez a separação automática das palavras na concatenação

#Exercício 3: Pedir dois números e apresentar a soma.

#erro: a = input ("Digite o primeiro número:")
#erro: b = input ("Agora digite o segundo número:")
#erro: print ("A soma dos números digitados é:",a+b,".")
#a+b concatenou as variáveis e não as somou
#motivo do erro: necessário atribuir valor de número inteiro à variável

a = int(input("Digite o primeiro número:"))
b = int(input("Agora digite o segundo número:"))
print ("A soma dos números digitados é:",a+b,".")

#Exercício 4: Pedir 4 notas bimestrais e calcular a média

n1 = float(input("Digite a note do 1º bimestre: "))
n2 = float(input("Digite a note do 2º bimestre: "))
n3 = float(input("Digite a note do 3º bimestre: "))
n4 = float(input("Digite a note do 4º bimestre: "))
print ("A média das notas é:",(n1+n2+n3+n4)/4)

#modo2

n1 = int(input("Digite a note do 1º bimestre: "))
n2 = int(input("Digite a note do 2º bimestre: "))
n3 = int(input("Digite a note do 3º bimestre: "))
n4 = int(input("Digite a note do 4º bimestre: "))
lista = (n1,n2,n3,n4)
print ("A média das notas é:",mean(lista))
