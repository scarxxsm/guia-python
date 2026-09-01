# Respuestas de los ejercicios de práctica

Recuerda que cada ejercicio puede tener más de una solución, estás son las maneras que yo consideré optimas :)

---

### 1.0 - Perfil de usuario

<details>
<summary><b>✅ Respsuesta:</b></summary>

```python
nombre = input("Ingresa tu nombre: ")
edad = int(input("Ingresa tu edad en años: "))
estatura = float(input("Ingresa tu estatura en metros: "))

print(nombre)
print(edad)
print(estatura)
```

</details>

---

### 2.0 - Calculadora básica

<details>
<summary><b>✅ Respsuesta:</b></summary>

```python
num_1 = int(input("Ingresa un primer número: "))
num_2 = int(input("Ingresa un segundo número: "))
operacion = input("Ingresa operación (+, -): ")

if operacion == "+":
    print(num_1 + num_2)
elif operacion == "-":
    print(num_1 - num_2)
```

</details>

---

### 3.0 - Aprobado/Reprobado

<details>
<summary><b>✅ Respsuesta:</b></summary>

```python
calificacion = float(input("Ingresa tu calificación: "))

if calificacion >= 7:
    print("Aprobado")
else:
    print("Reprobado")
```

</details>

---

### 4.0 - Días de la semana

<details>
<summary><b>✅ Respsuesta:</b></summary>

```python
dia = int(input("Ingresa un número del 1 al 7: "))

match dia:
    case 1:
        print("Lunes")
    case 2:
        print("Martes")
    case 3:
        print("Miercoles")
    case 4:
        print("Jueves")
    case 5:
        print("Viernes")
    case 6:
        print("Sabado")
    case 7:
        print("Domingo")
    case _:
        print("No es un número valido")
```

</details>

---

### 5.0 - Tabla de multiplicar

<details>
<summary><b>✅ Respsuesta:</b></summary>

```python
numero = int(input("Ingresa un número: "))

for i in range(1,11):
    print(i * numero)
```

</details>