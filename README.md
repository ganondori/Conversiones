# Conversiones

# Conversion ASCII

////////////////////////////////////////////////////////////////////////////////

    Fernando Perdomo Troche (1092890)
    Código de conversión de cualquier caracter a ASCII.
    
////////////////////////////////////////////////////////////////////////////////

palabra = input("Por favor entre una palabra: ")    Pide una palabra

for char in palabra:                    Bucle que se repite por cada letra en la palabra

    ascii = ord(char)                   Función que permite convertir las letras a su forma Unicode o ASCII
    
    print(char + " - " + str(ascii))    Muestra por consola el resultado de la letra mas su forma en Unicode o ASCII
    
    
# Conversion Decimal - binario

////////////////////////////////////////////////////////////////////////////////

    Fernando Perdomo Troche (1092890).
    Código de conversión de decimal a binario.
    
////////////////////////////////////////////////////////////////////////////////

num = input("Escriba un número: ")  Pide un numero.

while int(num) >= 1:                    Entra en un bucle mientras el numero sea mayor o igual que 1 este seguirá.

    print(num," - ", int(num) % 2)      Escribe el número y su forma binaria al lado.
    
    num = int(num)/2                    El número insertado se divide entre 2.
