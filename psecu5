Algoritmo Cuota_prestamo
    // Ejercicio: Cuota de préstamo con interés simple
    // Fuente: ZIP original

    // Variables y datos del problema
    Definir C, T, IT, CU Como Real
    Definir N Como Entero

    // Entrada de datos y validaciones
    Escribir "Ingrese el capital:"
    Leer C
    Escribir "Ingrese la tasa anual en decimal:"
    Leer T
    Escribir "Ingrese el plazo en meses:"
    Leer N

    // Proceso y cálculos
    Si C < 0 O T < 0 O N <= 0 Entonces
        Escribir "Datos no validos"
    SiNo
        IT <- C * T * (N / 12)
        CU <- (C + IT) / N
        Escribir "Interes total: $", IT
        Escribir "Cuota mensual: $", CU
    FinSi
FinAlgoritmo
