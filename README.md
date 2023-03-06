# RETO 4

Aquí solucionaré la tarea dejada en el reto 4, el cual consiste en:

1. Plantear el algoritmo para obtener los números primos hasta n, usando pseudocódigo y diagramas de flujo.

2. Revise el procedimiento matemático para hallar raices cuadradas (son divisiones y restas), plantee el algoritmo en pseudocódigo y en diagrama de flujo.


# 1)

[variables]
n: int
i: int
b: int
a: int

inicio

n = ingrese un número entero

Para i en rango ( 2 hasta n+1):

    a = 0
    
    Para b en rango (1 hasta n+1):
    
        si i%b residuo 0
        
        a = a+1
        
    si a ==2:
    
        imprimir i
        



![Diagrama sin título drawio (1)](https://user-images.githubusercontent.com/124614177/223003483-3f71f783-aa24-4067-9ddb-1fd4799599b3.png)


# 2)

n: int

f: int

inicio 

f:=0

n = ingrese un número 

Mientras n >= 0 hacer

    Si f*f=n hacer
    
        imprimir f
        
    Sino
    
        f = f+1
        
terminar mientras       




![Diagrama sin título drawio](https://user-images.githubusercontent.com/124614177/223001863-da0e5a94-f477-4fa7-9768-211f2d4d5312.png)
