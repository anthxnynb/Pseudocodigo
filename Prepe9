Algoritmo Armstrong
    // Ejercicio: Número de Armstrong de tres dígitos
    // Fuente: ZIP original

    // Variables y datos del problema
    Definir N, T, D, S Como Entero

    // Entrada de datos y validaciones
    Escribir "Ingrese un numero de tres digitos:"
    Leer N

    // Proceso y cálculos
    Si N < 100 O N > 999 Entonces
        Escribir "Debe ingresar un numero de tres digitos"
    SiNo
        T <- N
        S <- 0
        Mientras T > 0 Hacer
            D <- T MOD 10
            S <- S + D ^ 3
            T <- Trunc(T / 10)
        FinMientras
        Si S = N Entonces
            Escribir N, " es un numero de Armstrong"
        SiNo
            Escribir N, " no es un numero de Armstrong"
        FinSi
    FinSi
FinAlgoritmo
