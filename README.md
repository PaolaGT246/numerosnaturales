# numerosnaturales
# Solicitar un número natural al usuario
numero = int(input("Ingrese un número natural: "))

# Verificar si el número está entre 1 y 12
if 1 <= numero <= 12:
    print("El número", numero, "está dentro de la primera docena.")
else:
    print("El número", numero, "no está dentro de la primera docena.")
