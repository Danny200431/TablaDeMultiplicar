# Algoritmo: Tabla de Multiplicar

Este algoritmo solicita un número al usuario y muestra su tabla de multiplicar del 1 al 10.

## Descripción

El algoritmo sigue estos pasos:

1. Solicita al usuario que introduzca un número.
2. Usa un bucle desde 1 hasta 10.
3. En cada iteración, multiplica el número ingresado por el índice del bucle.
4. Muestra el resultado en formato de tabla de multiplicar.

## Ejemplo de ejecución

![Ejemplo de ejecución de la tabla de multiplicar](TablaDeMultiplicar.png)

## Pseudocódigo

```pseudocode
Algoritmo TablaDeMultiplicar
    Escribir "Introduce un número: "
    Leer numero

    Para i = 1 hasta 10 hacer
        resultado = numero * i
        Escribir numero, " x ", i, " = ", resultado
    FinPara
FinAlgoritmo

