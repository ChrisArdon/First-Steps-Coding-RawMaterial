# The `print()` function
The `print()` function in Python is used to display text or other information to the console or terminal. It takes one or more arguments, which can be of various data types (e.g. strings, numbers, lists, etc.), and prints them to the console or terminal window. For example, the following code will print the string "Hello, World!" to the console:
`print("Hello, World!")`

You can also pass multiple arguments to the `print()` function, which will print them all in order, separated by a space by default. For example:
`print("The answer is:", 42)`


# Concatenation
In Python, concatenation refers to the operation of joining two or more strings together to form a single string. This can be done using the `+` operator. For example:
```
string1 = "Hello"
string2 = "World"
print(string1 + " " + string2)
```
This will print "Hello World" to the console.

Another way to concatenate strings is by using the `+=` operator. For example:
```
string1 = "Hello"
string2 = "World"
string1 += " "
string1 += string2
print(string1)
```
This will also print "Hello World" to the console.

In python 3.6 and above, f-strings (formatted string literals) were introduced which makes it more easier to concatenate strings and variables.
```
string1 = "Hello" string2 = "World" print(f'{string1} {string2}')
```


# Ejercicios

## Imprimir nombre, edad y gusto musical
```
nombre = "Chris"
edad = 25
musica = "metal"
print(f"Mi nombre es {nombre} y tengo {edad}. Me gusta el {musica}")
```


