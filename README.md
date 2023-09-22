# Proyecto-Parcial-1
### Codigo 1
-# hints o pistas
numero: int = 10
numero = "dos"
numero

### Código 2
num =""
n = int(input("dame un numero entero positivo: "))
if n%2 == 0:
    num = "par"
else:
    num = "impar"

### Codigo 3
n = int(input("dame un numero entero positivo: "))
(num:= "par" if n%2 == 0 else "impar")
num

#### Codigo 4
(num := "par" if int(input("dame un numero entero positivo: "))%2 == 0 else "impar")
num

### Codigo 5
-# casting
-# converión de tipos 
num_str = "3"
num_int = int(num_str)
print(f"num_int: {num_int}") #fstrings

num_float = 3.14
num_int = int(num_float)
print(f"num_int: {num_int}")

num_str = str(num_float)
print(f"num_str: {num_str}")
num_str

### Codigo 6

True
False
if 5 > 4:
    print(True)
    
print(5 > 7)

received = input("dame un numero entero positivo: ")
print(received)
print(type(received))

### Codigo 7

nombre: str = "hugo"
nombre
print(type(nombre))
nombre.capitalize()
nombre.upper()

#### Codigo 8

num: int = 10
pi:float = 3.14
es_alumno: bool = True
name: str = "Hugo"

print(f'{num}-{pi}-{es_alumno}-{name}')

### Codigo 9

print(5.+4)
print(5-4)
print(5*4)
print(5/4)
print(5//4) #división entera
print(5%4)  #modulo o residuo
print(5**3) # x a la y

### Codigo 10

print( True and False)
print( True or False)
print( not False)

### Codigo 11
n1: int = 10
n2:int = 20

if n1 > n2:
    print(f"{n1} es mayor que {n2}")

### Codigo 12
n1 = 10
if n1 > n2:
    print(f"{n1} es mayor que {n2}")
else:
    print(f"{n1} es menor que {n2}")


### Codigo 13
edad: int = 18

if edad > 18:
    print("eres mayor de edad")
elif edad == 18:
    print("acabas de llegar a la mayoria de edad")
else:
    print("eres menor de edad")


### Codigo 14
match True:
    case "edad > 18":
        print("acabas de llegar a la mayoria de edad")
    case "edad == 18":
        print("acabas de llegar a la mayoria de edad")
    case _:
        print("eres menor de edad")
        

### Codigo 15
-# Listas
def suma(a, b):
    return a + b

def resta(a, b):
    return a - b

def multiplicacion(a, b):
    return a * b

def division(a, b):
    return a / b

operaciones = [suma, resta, multiplicacion, division]

print(operaciones[0](5, 4))
print(operaciones[1](5, 4))
print(operaciones[2](5, 4))
print(operaciones[3](5, 4))

for operacion in operaciones:
    print(operacion(5, 4))

lista = [1,2,3,4,5, True, "hola", [1, 2, 3]]


### Codigo 16
-#slices

print(lista)
print(lista[:])

### Codigo 17
def suma(a, b):
    pass

print(suma(3,4))

### Codigo 18
def operaciones(a,b):
    return [a+b, a-b, a*b, a/b]

respuestas = operaciones(5,4)
print(respuestas)
w,x,y,z = operaciones(5,4)
print(w)


### Codigo 19
res_suma,_ ,_,_ = operaciones(5,4)
res_suma


### Codigo 20
-#tuple
tupla_funciones = (suma, resta, multiplicacion, division)
print(tupla_funciones[1](5,4))
tupla = (1,2,3,4,5, True, 4.5,  "hola", [1, 2, 3])

### Codigo 21
-#tupla[0] = 10
lista.append(10)
lista


### Codigo 22
tupla.__add__((10,10))

### Codigo 23
tupla[0].__mod__(2)


### Codigo 24
def suma(a: int, b: int) -> int:
    return a + b

def operacion(a: int, b: int) -> (int, int):
    return (a+b, a-b)

(a,b)= operacion(5,6)
a,b = operacion(6,5)  
print(a,b)


### Codigo 25
#range

numeros = range(10)
print(numeros)


### Codigo 26
for i in numeros:
    print(i, end=" ")


### Codigo 27
for i in numeros:
    print(i)


### Codigo 28
numeros = range(5, 10)
numeros


### Codigo 29
for i in numeros:
    print(i, end=" ")


### Codigo 30
numeros_pares = range(2, 11, 2)
for par in numeros_pares:
    print(par, end=" ")


### Codigo 31
for item in range(2, 11, 2):
    print(item, end=" ")


### Codigo 32
numeros


### Codigo 33
list(numeros)


### Codigo 34
lista = [3, 6, 7, 40, 34, 67, 89]
max(lista)


### Codigo 35
list = [3, 6, 7, 40, 34, 67, 89]
min(lista)


### Codigo 36
sum(lista)


### Codigo 37
sorted(lista)


### Codigo 38
print(lista.sort())


### Codigo 39
lista.sort(reverse=True)
lista


### Codigo 40
# set conjuntos

mi_set = {1,2,3,3,3,3,3}
mi_set


### Codigo 41
data = [11,12,13,14,45,1,2,3,4,5,6,7,8,9,1,2,1,2,1,2,1,2]

set(data)


### Codigo 42
data2 = {1,56,57,58}

mi_set.union(data2)


### Codigo 43
#diccionarios

mi_dict = {"llave": "valor"}
mi_dict["llave"]


### Codigo 44
mi_dict.keys()


### Codigo 45 
mi_dict.values()


### Codigo 46
# do a dict with the days of the week
days_of_week = {
    "Monday": 1,
    "Tuesday": 2,
    "Wendnesday": 3,
    "Thursday": 4,
    "Friday": 5,
    "Saturday": 6,
    "Sunday": 7,
}

for e in mi_set:
    print(e)
    
    for key in days_of_
    .
