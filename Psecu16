Algoritmo Valor_futuro
    // Ejercicio: Valor futuro de una anualidad
    // Fuente: ZIP original

    // Variables y datos del problema
    Definir D, I, VF, TT Como Real
    Definir N Como Entero

    // Entrada de datos y validaciones
    Escribir "Ingrese el deposito mensual:"
    Leer D
    Escribir "Ingrese la tasa mensual en decimal:"
    Leer I
    Escribir "Ingrese el numero de meses:"
    Leer N

    // Proceso y cálculos
    TT <- D * N
    Si N <= 0 O D < 0 O I < 0 Entonces
        Escribir "Datos no validos"
    SiNo
        Si I = 0 Entonces
            VF <- TT
        SiNo
            VF <- D * (((1 + I) ^ N - 1) / I)
        FinSi
        Escribir "Total depositado: $", TT
        Escribir "Valor futuro: $", VF
    FinSi
FinAlgoritmo
