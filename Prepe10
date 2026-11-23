Algoritmo Numero_perfecto
    // Ejercicio: Números perfectos
    // Fuente: ZIP original

    // Variables y datos del problema
    Definir N, DIV, SUMA Como Entero

    // Entrada de datos y validaciones
    Escribir "Ingrese un numero entero positivo:"
    Leer N
    // Proceso y cálculos
    Mientras N <= 0 Hacer
        Escribir "El numero debe ser mayor que 0"
        Escribir "Ingrese un numero entero positivo:"
        Leer N
    FinMientras

    SUMA <- 0
    DIV <- 1
    Mientras DIV <= Trunc(N / 2) Hacer
        Si N MOD DIV = 0 Entonces
            SUMA <- SUMA + DIV
        FinSi
        DIV <- DIV + 1
    FinMientras

    Si SUMA = N Y N > 1 Entonces
        Escribir N, " es un numero perfecto"
    SiNo
        Escribir N, " no es un numero perfecto"
    FinSi
FinAlgoritmo
