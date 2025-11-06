---
{"dg-publish":true,"permalink":"/repertorio-de-instrucciones/"}
---

Toda instrucción de máquina es una secuencia de bits que el procesador divide en 2 partes fundamentales:
- Códigos de operación (OPcode)
- Operandos (datos o direcciones)
## Código de operación (OP code)
Interpretado por la unidad de control(UC) del procesador.
- Si la instrucción es aritmética o lógica (ADD o SUB), la UC dirigirá la operación a la ALU
- Si la instrucción es de memoria (LOAD o STOR), la UC gestionará el bus de datos y direcciones para comunicarse con la memoria o registros.
## Operandos (Campo de direccionamiento)
Indican el dato o la ubicación de los datos con los que se va a trabajar.
Tipos de operando:
- Operando fuente: los datos de entrada para la operación.
- Operando destino: la ubicación donde se guardará el resultado.
- Referencia a siguiente instrucción: usando instrucciones de salto.
### Formatos de instrucción
Las instrucciones se pueden clasificar por cuántos operandos
- Instrucciones de 0 dirección:
	- Push y Pop
- Instrucciones de 1 dirección:
	- Utilizan un registro especial (AC).
	- LOAD D -> "Carga D en el acumulador"
- Instrucciones de 2 direcciones:
	- Uno de los operandos actua a la vez como fuente y destino.
	- SUB Y, B -> Y=Y-B, Destino(Salida)=Y; Fuente (Entrada)=B.
	- OPERACIÓN \[Destino], \[Fuente].
	- MOV Y, B -> "Mueve el contenido de B hacia Y".
- Intrucciones de 3 direcciones:
	- Especifica 3 fuentes (A, B) y una salida (Y).
	- OPERACIÓN \[DESTINO], \[FUENTE_1], \[FUENTE_2],.
	- ADD Y, A, B -> Y=A+B.
	- SUB R3, R1, R2 -> R3=R1-R2