# Creador de contraseñas aleatorio 
Import random 

letras_min = "abcdefghijklmnñopqrstuvwxyz"
letras_mayus= "ABCDEFGHIJKLMNÑOPQRSTUVWXYZ"
numeros = "0123456789"
simbolos = "@#$&-+()/?*!%[]{}=×÷π><"

unir = f'{letras_min}{letras_mayus}{numeros}{simbolos}'

n = int(input("ingresa la longitud de la contraseña"))

contraseña = random.sample(unir, n)

pass_final = "".join(contraseña)

print(pass_final)
