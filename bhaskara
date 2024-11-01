# Importando a biblioteca matemática
import math

# Entrada dos valores de a, b e c
a = float(input("Digite o valor de a: "))
b = float(input("Digite o valor de b: "))
c = float(input("Digite o valor de c: "))

# Cálculo do discriminante (delta)
delta = b**2 - 4*a*c

# Verificação do valor de delta para determinar as raízes
if delta == 0:
    raiz = -b / (2 * a)
    print("Essa equação tem raízes iguais:", raiz)
elif delta < 0:
    print("A equação não tem raízes reais")
else:
    raiz1 = (-b + math.sqrt(delta)) / (2 * a)
    raiz2 = (-b - math.sqrt(delta)) / (2 * a)
    print("A primeira raiz da equação é:", raiz1)
    print("A segunda raiz da equação é:", raiz2)
