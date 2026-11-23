Algoritmo Estadisticas_calificaciones
    // Ejercicio: Estadísticas de N calificaciones
    // Fuente: ZIP original

    // Variables y datos del problema
    Definir N, I, APR, REP Como Entero
    Definir NOTA, SUMA, P, MAY, MEN Como Real

    // Entrada de datos y validaciones
    Escribir "Ingrese la cantidad de calificaciones:"
    Leer N
    // Proceso y cálculos
    Mientras N <= 0 Hacer
        Escribir "La cantidad debe ser mayor que 0"
        Escribir "Ingrese la cantidad de calificaciones:"
        Leer N
    FinMientras

    SUMA <- 0
    APR <- 0
    REP <- 0

    Para I <- 1 Hasta N Hacer
        Escribir "Ingrese la calificacion ", I, " (0 a 10):"
        Leer NOTA
        Mientras NOTA < 0 O NOTA > 10 Hacer
            Escribir "La nota debe estar entre 0 y 10"
            Escribir "Ingrese la calificacion ", I, " (0 a 10):"
            Leer NOTA
        FinMientras

        SUMA <- SUMA + NOTA
        Si I = 1 Entonces
            MAY <- NOTA
            MEN <- NOTA
        SiNo
            Si NOTA > MAY Entonces
                MAY <- NOTA
            FinSi
            Si NOTA < MEN Entonces
                MEN <- NOTA
            FinSi
        FinSi

        Si NOTA >= 7 Entonces
            APR <- APR + 1
        SiNo
            REP <- REP + 1
        FinSi
    FinPara

    P <- SUMA / N
    Escribir "Promedio: ", P
    Escribir "Calificacion mayor: ", MAY
    Escribir "Calificacion menor: ", MEN
    Escribir "Cantidad de aprobados: ", APR
    Escribir "Cantidad de reprobados: ", REP
FinAlgoritmo
