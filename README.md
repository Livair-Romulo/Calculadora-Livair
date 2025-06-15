# Calculadora-Livair
Minha primeira calculadora
# Calculadora simples usando if

print("Calculadora em Python")
print("Operações disponíveis: +, -, *, /")

# Entrada dos valores
num1 = float(input("Digite o primeiro número: "))
operacao = input("Digite o operador (+, -, *, /): ")
num2 = float(input("Digite o segundo número: "))

# Verifica e realiza a operação
if operacao == "+":
    resultado = num1 + num2
    print("Resultado:", resultado)

if operacao == "-":
    resultado = num1 - num2
    print("Resultado:", resultado)

if operacao == "*":
    resultado = num1 * num2
    print("Resultado:", resultado)

if operacao == "/":
    if num2 != 0:
        resultado = num1 / num2
        print("Resultado:", resultado)
    else:
        print("Erro: divisão por zero não é permitida.")

# Caso o operador não seja válido
if operacao != "+" and operacao != "-" and operacao != "*" and operacao != "/":
    print("Operador inválido.")
