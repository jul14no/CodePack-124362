# CodePack-124362
Desenvolvimento 4


def calculadora(num1, num2, operacao):
    if operacao == 1:
        return num1 + num2
    elif operacao == 2:
        return num1 - num2
    elif operacao == 3:
        return num1 * num2
    elif operacao == 4:
        return num1 / num2 if num2 != 0 else "Divisão por zero não é permitida"
    else:
        return 0
resultado = calculadora(10, 5, 1) 
print(resultado)
