Algoritmo Energia_electrica
    // Ejercicio: Cálculo de energía eléctrica
    // Fuente: ZIP original

    // Variables y datos del problema
    Definir POT, HRS, TAR, CON, COS Como Real

    // Entrada de datos y validaciones
    Escribir "Ingrese la potencia del electrodomestico en W:"
    Leer POT
    // Proceso y cálculos
    Mientras POT <= 0 Hacer
        Escribir "La potencia debe ser mayor que 0"
        Escribir "Ingrese la potencia del electrodomestico en W:"
        Leer POT
    FinMientras

    Escribir "Ingrese las horas de uso diario (0 a 24):"
    Leer HRS
    Mientras HRS < 0 O HRS > 24 Hacer
        Escribir "Las horas deben estar entre 0 y 24"
        Escribir "Ingrese las horas de uso diario (0 a 24):"
        Leer HRS
    FinMientras

    Escribir "Ingrese la tarifa por kWh:"
    Leer TAR
    Mientras TAR < 0 Hacer
        Escribir "La tarifa no puede ser negativa"
        Escribir "Ingrese la tarifa por kWh:"
        Leer TAR
    FinMientras

    CON <- (POT / 1000) * HRS * 30
    COS <- CON * TAR

    Escribir "Consumo mensual: ", CON, " kWh"
    Escribir "Costo mensual: $", COS
FinAlgoritmo
