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
if operacion == "-":
    print(num_1 - num_2)

```

</details>