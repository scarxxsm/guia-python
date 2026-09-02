# Proyecto final 

Recomencación: evita el uso de IA, si tienes dudas consulta las carpetas de estudio de la fase o contactame por [instagram](https://www.instagram.com/oscaralexis_sm?igsh=MWhwdnl3c2xpb2JsdQ==)

De igual manera, en esta carpeta encontrarás un archivo "Respuesta_proyecto", en donde estará una manera de resolver el proyecto final, te recomiendo revisarla después de intentarlo por tu cuenta.
---
**Simulador de cajero**

Como proyecto final de la Fase 1, construirás un cajero interactivo en la terminal donde el usuario validará su identidad y gestionará su dinero mediante un menú dinámico.

*Datos iniciales del sistema (Variables fijas):*

- PIN_CORRECTO = "5716"
- saldo = 1000.0 (Monto inicial para poder probar retiros)

*Requisitos:*

- Acceso: Bucle ``while`` que pide el PIN  de 4 dígitos con un máximo de 3 intentos. Si falla los 3, se activa la cláusula ``else`` del ``while`` para mostrar el mensaje "Tarjeta Bloqueada".
- Menú principal: Usa match-case para elegir entre:

 1. Ver Saldo (Muestra el saldo actual)
 2. Depositar (Pide una cantidad y la suma al saldo)
 3. Retirar (Evalúa con un if que el saldo sea suficiente antes de restar)
 4. Salir (Termina el programa con un mensaje de despedida)


*Flujo del programa:*

Ingresar PIN correcto de 3 dígitos **-->**
Seleccionar modo de uso (1. Ver Saldo, 2. Depositar, 3. Retirar, 4. Salir) **-->**
Realizar operación necesaria. **-->** 
Repetir menú (hasta elegir 4. Salir).