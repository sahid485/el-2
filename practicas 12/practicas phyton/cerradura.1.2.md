# Programa creado por QUIROZ CERVANTES SAHID EMILINAO 
# Programa Suma de 2 numeros

print(" Cerradura: La Suma De 2 Numeros Reales Siempre Da Otro Numero Real. ")
print(" A + B Pertenece R ")
print("")

# El Programa indicara la cerradura
print(" El Siguiente Programa Realiza La Propiedad De Cerradura. ")
print("")

# Solicitar al usuario que capture 2 numeros 
num1 = float(input(" Captura El Primer Numero: "))
num2 = float(input(" Captura El Segundo Numero: "))

# Calcula la suma de 2 numeros ingresados por el usuario
res = num1 + num2

# Condicional para verificar si el resultado de la sunma es entero o racional
if res.is_integer(): 
    result = "Entero "
else:
    result = "56Racional "
    
# Muestra el resultado de la suma y su tipo
print("")
print(" La suma de {} mas {} es: {} ".format(num1, num2, res))
print(" El resultado de la suma es de tipo ",result)

----------------------------------------------------------------------------------------

# Programa creado por Leyva Gonzalez Irving Antonio
# Programa Multiplicacion de 2 numeros
print(" Cerradura: La Multiplicacion De 2 Numeros Reales Siempre Da Otro Numero Real. ")
print(" A * B Pertenece R ")
print("")

# El Programa indicara la cerradura
print(" El Siguiente Programa Realiza La Propiedad De Cerradura. ")
print("") 

# Solicitar al usuario que capture 2 numeros 
num1 = float(input(" Captura El Primer Numero: "))
num2 = float(input(" Captura El Segundo Numero: "))

# Calcula la multi de 2 numeros ingresados por el usuario
res = num1 * num2

# Condicional para verificar si el resultado de la multi es entero o racional
if res.is_integer(): 
    result = "Entero "
else:
    result = "Racional "
    
# Muestra el resultado de la Multi y su tipo
print("")
print(" La multiplicacion de {} por {} es: {} ".format(num1, num2, res))
print(" El resultado de la multiplicacion es de tipo ",result)