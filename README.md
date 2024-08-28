# Cod```python
def adicionar(x, y):
    return x + y

def subtrair(x, y):
    return x - y

def multiplicar(x, y):
    return x * y

def dividir(x, y):
    if y == 0:
        return "Erro! Divisão por zero."
    return x / y

print("Selecione a operação:")
print("1. Adição")
print("2. Subtração")
print("3. Multiplicação")
print("4. Divisão")

# Recebe a entrada do usuário
operacao = input("Digite o número da operação (1/2/3/4): ")

num1 = float(input("Digite o primeiro número: "))
num2 = float(input("Digite o segundo número: "))

if operacao == '1':
    print(f"{num1} + {num2} = {adicionar(num1, num2)}")

elif operacao == '2':
    print(f"{num1} - {num2} = {subtrair(num1, num2)}")

elif operacao == '3':
    print(f"{num1} * {num2} = {multiplicar(num1, num2)}")

elif operacao == '4':
    print(f"{num1} / {num2} = {dividir(num1, num2)}")
