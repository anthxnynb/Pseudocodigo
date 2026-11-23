Algoritmo Ahorro_interes_compuesto
    // Ejercicio: Ahorro con interés compuesto mensual
    // Fuente: ZIP original

    // Variables y datos del problema
    Definir CAP, DEP, TASA, SAL Como Real
    Definir N, MES Como Entero

    // Entrada de datos y validaciones
    Escribir "Ingrese el capital inicial:"
    Leer CAP
    // Proceso y cálculos
    Mientras CAP < 0 Hacer
        Escribir "El capital no puede ser negativo"
        Escribir "Ingrese el capital inicial:"
        Leer CAP
    FinMientras

    Escribir "Ingrese el deposito mensual:"
    Leer DEP
    Mientras DEP < 0 Hacer
        Escribir "El deposito no puede ser negativo"
        Escribir "Ingrese el deposito mensual:"
        Leer DEP
    FinMientras

    Escribir "Ingrese el numero de meses:"
    Leer N
    Mientras N <= 0 Hacer
        Escribir "El numero de meses debe ser mayor que 0"
        Escribir "Ingrese el numero de meses:"
        Leer N
    FinMientras

    Escribir "Ingrese la tasa mensual de interes (%):"
    Leer TASA
    Mientras TASA < 0 Hacer
        Escribir "La tasa no puede ser negativa"
        Escribir "Ingrese la tasa mensual de interes (%):"
        Leer TASA
    FinMientras

    SAL <- CAP
    Para MES <- 1 Hasta N Hacer
        SAL <- SAL + DEP
        SAL <- SAL * (1 + TASA / 100)
        Escribir "Saldo al finalizar el mes ", MES, ": $", SAL
    FinPara
    Escribir "Saldo final: $", SAL
FinAlgoritmo
