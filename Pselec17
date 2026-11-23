Algoritmo Validacion_fecha
    // Ejercicio: Validación de fecha
    // Fuente: ZIP original

    // Variables y datos del problema
    Definir DIA, MES, ANIO, DM Como Entero
    Definir BIS Como Logico

    // Entrada de datos y validaciones
    Escribir "Ingrese el dia:"
    Leer DIA
    Escribir "Ingrese el mes:"
    Leer MES
    Escribir "Ingrese el anio:"
    Leer ANIO

    // Proceso y cálculos
    DM <- 0
    BIS <- Falso

    Si ANIO > 0 Y MES >= 1 Y MES <= 12 Y DIA >= 1 Entonces
        Si ANIO MOD 400 = 0 O (ANIO MOD 4 = 0 Y ANIO MOD 100 <> 0) Entonces
            BIS <- Verdadero
        FinSi

        Si MES = 2 Entonces
            Si BIS Entonces
                DM <- 29
            SiNo
                DM <- 28
            FinSi
        SiNo
            Si MES = 4 O MES = 6 O MES = 9 O MES = 11 Entonces
                DM <- 30
            SiNo
                DM <- 31
            FinSi
        FinSi
    FinSi

    Si DM > 0 Y DIA <= DM Entonces
        Escribir "La fecha es valida"
    SiNo
        Escribir "La fecha no es valida"
    FinSi
FinAlgoritmo
