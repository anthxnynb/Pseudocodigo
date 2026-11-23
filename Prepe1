Algoritmo Ahorro_aportes
    // Ejercicio: Ahorro con aportes variables
    // Fuente: ZIP original

    // Variables y datos del problema
    Definir S, A Como Real
    Definir N, I Como Entero

    // Entrada de datos y validaciones
    Escribir "Ingrese la cantidad de meses:"
    Leer N

    // Proceso y cálculos
    Si N <= 0 Entonces
        Escribir "N debe ser mayor que cero"
    SiNo
        S <- 0
        Para I <- 1 Hasta N Hacer
            Escribir "Ingrese el aporte del mes ", I, ":"
            Leer A
            Si A < 0 Entonces
                Escribir "El aporte no puede ser negativo; se toma como 0"
                A <- 0
            FinSi
            S <- (S + A) * 1.008
            Escribir "Saldo del mes ", I, ": $", S
        FinPara
        Escribir "Saldo final: $", S
    FinSi
FinAlgoritmo
