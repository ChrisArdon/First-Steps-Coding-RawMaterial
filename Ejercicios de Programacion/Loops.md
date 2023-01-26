# Ejemplos

### Numero primo
```
# Pedimos al usuario que ingrese un numero
num = int(input("Ingrese un numero: "))
if num == 1:
    # Si el usuario ingresa 1, se le notifica que no es numero primo
    print(f"{num} no es numero primo")
elif num > 1:
    # Revisamos si hay factores
    for i in range(2, num):  # Revisamos todos los numeros dentro del rango dado
        if (num % i) == 0:  # Si el numero se divide por cualquera y da mod = 0 entonces no es primo
            print(f"{num} no es un numero primo")
            # imprimimos la multiplicacion que hace que el numero no sea primo
            print(i, "*", num//i, "es", num)
            break
    else:
        # si no, entonces si es un numero primo
        print(num, "es un numero primo")
else:
    print(num, "No es un numero primo")
```

### Numeros primos en un rango
```
n1 = int(input("Ingrese el numero inicial: "))
n2 = int(input("Ingrese el numero final: ")) 

primos = []
for num in range(n1, n2 + 1):
    if num > 1:
        for i in range(2, num):
            if (num % i) == 0:
                break
        else:
            primos.append(num)
print(primos)
```