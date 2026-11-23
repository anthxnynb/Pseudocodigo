Algoritmo MCD_Euclides
    // Ejercicio: Máximo común divisor (Euclides)
    // Fuente: ZIP original

    // Variables y datos del problema
    Definir A, B, RES Como Entero

    // Entrada de datos y validaciones
    Escribir "Ingrese el primer numero entero positivo:"
    Leer A
    // Proceso y cálculos
    Mientras A <= 0 Hacer
        Escribir "El numero debe ser mayor que 0"
        Escribir "Ingrese el primer numero entero positivo:"
        Leer A
    FinMientras

    Escribir "Ingrese el segundo numero entero positivo:"
    Leer B
    Mientras B <= 0 Hacer
        Escribir "El numero debe ser mayor que 0"
        Escribir "Ingrese el segundo numero entero positivo:"
        Leer B
    FinMientras

    Mientras B <> 0 Hacer
        RES <- A MOD B
        A <- B
        B <- RES
    FinMientras

    Escribir "El maximo comun divisor es: ", A
FinAlgoritmo
