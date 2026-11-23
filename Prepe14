Algoritmo Promedio_de_N_notas
    // Ejercicio: pseudocódigo Promedio de N notas
    // Fuente: ZIP original

    // Variables y datos del problema
    Definir N, I Como Entero
    Definir NOTA, SUMA, P Como Real
    // Entrada de datos y validaciones
    Escribir "Ingrese la cantidad de notas:"
    Leer N
    // Proceso y cálculos
    Mientras N <= 0 Hacer
        Escribir "La cantidad de notas debe ser mayor que 0"
        Escribir "Ingrese la cantidad de notas:"
        Leer N
    FinMientras
    SUMA <- 0
    Para I <- 1 Hasta N Hacer
        Escribir "Ingrese la nota ", I, " (0 a 10):"
        Leer NOTA
        Mientras NOTA < 0 O NOTA > 10 Hacer
            Escribir "La nota debe estar entre 0 y 10"
            Escribir "Ingrese la nota ", I, " (0 a 10):"
            Leer NOTA
        FinMientras
        SUMA <- SUMA + NOTA
    FinPara
    P <- SUMA / N
    Escribir "El promedio de las notas es: ", P
FinAlgoritmo
