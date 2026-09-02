# Respuesta a simulador de cajero
Recuerda que el ejercicio puede tener más de una solución, está fue la maneras que yo consideré optima :)

---

<details>
<summary><b>✅ Respsuesta:</b></summary>

```python
intentos = 3
saldo = 1000

while intentos > 0:
    pin = int(input("Ingresa el PIN correcto: "))
    
    if pin == 5716:
        print("PIN correcto, accediendo al sistema...\n")
        
        while True:
            print("\tMenu: \n"
            + "1 - Ver saldo\n"
            + "2 - Depositar\n"
            + "3 - Retirar\n"
            + "4 - Salir\n")
            op = int(input("Opción: "))

            match op:
                case 1:
                    print(f"Tu saldo es {saldo}\n")
                case 2:
                    dep = float(input("Cantidad a depositar: "))
                    saldo += dep
                    print(f"{dep} fue depositado con éxito\n")
                case 3:
                    ret = float(input("Cantidad a retirar: "))
                    if ret <= saldo:
                        saldo -= ret
                        print(f"{ret} fue retirado con éxito\n")
                    else: 
                        print(f"No tienes el saldo suficiente, deseas retirar: {ret} mientras que tu saldo actual es {saldo}")
                case 4:
                    print("Cerrando seción...")
                    break
                case _:
                    print("Opción invalida")
        break

    else:
        intentos -= 1
        print(f"Contraseña incorrecta, te quedan {intentos} intentos\n")
else:
    print("Tarjeta Bloqueada")
```

</details>

Sugerencias y dudas: [Instagram](https://www.instagram.com/oscaralexis_sm?igsh=MWhwdnl3c2xpb2JsdQ==)