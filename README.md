# Programaci-n-imperativa
#EJMPL LIST
nombres = [ "Juan", "María", "Carlos", "Ana" , "Laura", "Carmen", "Luis"]
nombres.sort()
nombres_con_L = [nombre for nombre in nombres if nombre.startswith("C")]
for nombre in nombres_con_L:
   print(nombre)
   # SUMA EJPLO
def suma_numeros(n):
    suma = 0  # Inicializamos la variable 'suma' con 0
    for numero in range(1, n+1):  # Usamos un bucle for para sumar los números del 1 hasta n
        suma += numero  # En cada iteración, sumamos el valor de 'numero' a 'suma'
    return suma  # Retornamos el resultado de la suma

# Llamamos a la función con N=10
resultado = suma_numeros(10)
print("La suma de los primeros 10 números es:", resultado)

   
