def binario_para_decimal(binario):
    if binario == "":
        return 0
    return int(binario[0]) * (2 ** (len(binario) - 1)) + binario_para_decimal(binario[1:])

binario = input("Digite um número binário: ")
print(binario_para_decimal(binario))