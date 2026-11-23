Algoritmo Amortizacion_prestamo_simple
    // Ejercicio: Amortización de préstamo simple
    // Fuente: ZIP original

    // Variables y datos del problema
    Definir MON, TASA, INT, CUO Como Real
    Definir MES Como Entero

    // Entrada de datos y validaciones
    Escribir "Ingrese el monto del prestamo:"
    Leer MON
    // Proceso y cálculos
    Mientras MON <= 0 Hacer
        Escribir "El monto debe ser mayor que 0"
        Escribir "Ingrese el monto del prestamo:"
        Leer MON
    FinMientras

    Escribir "Ingrese la tasa de interes mensual (%):"
    Leer TASA
    Mientras TASA < 0 Hacer
        Escribir "La tasa no puede ser negativa"
        Escribir "Ingrese la tasa de interes mensual (%):"
        Leer TASA
    FinMientras

    Escribir "Ingrese el numero de meses:"
    Leer MES
    Mientras MES <= 0 Hacer
        Escribir "El numero de meses debe ser mayor que 0"
        Escribir "Ingrese el numero de meses:"
        Leer MES
    FinMientras

    INT <- MON * (TASA / 100) * MES
    CUO <- (MON + INT) / MES

    Escribir "Interes total: $", INT
    Escribir "Cuota mensual: $", CUO
FinAlgoritmo
