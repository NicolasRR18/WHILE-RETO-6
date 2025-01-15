# WHILE-RETO-6

=============================================================

El objetivo era resolver el reto 6, el cual consistia en
realizar algoritmos que cumplieran con las necesidades 
planteadas en cada punto, y para los primeros 3 puntos
adjuntar un .
A continuacion adjunto la imagen del repo del profe Felipe:

============================================================

![image](https://github.com/user-attachments/assets/795335fa-2d2b-4317-a538-03b0e244eef1)

============================================================

 >-Asi que adjuntare capturas mostrando como estan
 >diseñados los codigos para cumplir con cada punto del reto,
 >los realice en visual studio code, a su vez adjuntaré
 >los codigos para que puedan ser copiados y probados.

============================================================

![image](https://github.com/user-attachments/assets/fa92ae99-898f-4ead-8800-dbb160973953)

![image](https://github.com/user-attachments/assets/0e282d86-4c45-451c-afdc-e074c958bdb7)

```

def cuadrados(n:int) -> int:
    return n ** 2

if __name__ == "__main__":
    n = 1
    while n <= 100:
        cuadrado = cuadrados(n)
        print(str(n) + " tienes como cuadrado " + str (cuadrado), sep=" ")
        n += 1
    print ("y hasta aquí el listado")

```

============================================================

![image](https://github.com/user-attachments/assets/b021bc7f-4dfe-4484-9742-5878e780a650)

![image](https://github.com/user-attachments/assets/4c2d7192-4345-4972-962a-87d02f55f3ee)

```

def impares(n:int) -> int:
    return 2 * n + 1
def pares(x:int) -> int:
    return 2 * x

if __name__ == "__main__":
    n = 0
    x = 0
    print ("Listado de numeros impares hasta el 999: ")
    while (2 * n) + 1  <= 999:
        impar = impares(n)
        print(str(impar))
        n += 1
    print ("y hasta aquí el listado")
    
    print ("Listado de numeros pares hasta el 1000: ")
    while 2 * x  <= 1000:
        par = pares(x)
        print (str(par))
        x += 1
    print ("y hasta aquí el listado")

```

============================================================

![image](https://github.com/user-attachments/assets/2e81c9c7-c6de-484e-a802-88ed386e2e14)

![image](https://github.com/user-attachments/assets/464822d2-6209-4258-be67-1677e5595f9d)

```

def par(n : int) -> float:
    return n % 2

if __name__ == "__main__":
    n = int(input("Ingrese un numero cualquiera"))
    while n >= 2:
        modulo = par(n)
        if modulo == 0:
            print(n)
        n -= 1
    print ("")   

```

============================================================

![image](https://github.com/user-attachments/assets/8977113f-a00f-46f6-b5a3-78e0fb227794)

```

n = int(input("Ingrese un numero cualquiera mayor a 0"))
multiplicacion: int = 1
x = n
while x > 0:
    multiplicacion *= x
    x -= 1   
print (" el factorial de "+ str(n) +" es " + str(multiplicacion))

```

============================================================

![image](https://github.com/user-attachments/assets/cf9813ac-98f2-407f-831c-437831ecdab9)

```

def division(n : int, x : int) -> float:
    return n % x

if __name__ == "__main__":
    n = int(input("Ingrese un numero cualquiera"))
    x = n
    while 50 >= n >= 2 and x >= 2 :
        if n % x == 0 :
            print(x)
        x -= 1

```

============================================================

![image](https://github.com/user-attachments/assets/9cc0c538-0e0e-4609-aade-a95b2d22ca5e)

```

a = 1
while a < 100:
    i = 1
    c = 0
    while i < a: 
        if a % i == 0:
            c = c +1
        i += 1    

    if c >= 2:
        print(end="")
    else:
        print(a)
    a += 1

```

============================================================

# NICOLAS RAMIREZ RODRIGUEZ 1000506513
