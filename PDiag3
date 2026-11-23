Algoritmo Estadisticas_Ventas
    // Ejercicio: Diagnóstico 3 - Estadísticas de ventas hasta -1
    // Fuente: Diagnóstico, ejercicio 3 (enunciado del chat)

    Definir D, C, DM Como Entero
    Definir V, S, P, MAX Como Real
    // Acumuladores y control de dias validos
    S <- 0
    D <- 0
    C <- 0
    DM <- 0
    MAX <- 0
    Escribir "Venta diaria (-1 para terminar):"
    Leer V
    // Las ventas negativas distintas de -1 no cuentan como dias
    Mientras V <> -1 Hacer
        Si V < 0 Entonces
            Escribir "Venta no valida; ingrese cero o un valor positivo"
        SiNo
            D <- D + 1
            S <- S + V
            Si V > 500 Entonces
                C <- C + 1
            FinSi
            Si D = 1 O V > MAX Entonces
                MAX <- V
                DM <- D
            FinSi
        FinSi
        Escribir "Siguiente venta (-1 para terminar):"
        Leer V
    FinMientras
    // Resumen, evitando dividir por cero
    Escribir "Total de ventas: $", S
    Escribir "Dias con venta superior a $500: ", C
    Si D > 0 Entonces
        P <- S / D
        Escribir "Promedio de ventas: $", P
        Escribir "Dia de mayor venta: ", DM
        Escribir "Mayor venta: $", MAX
    SiNo
        Escribir "Promedio: no hay ventas registradas"
        Escribir "No hay dia con mayor venta"
    FinSi
FinAlgoritmo
