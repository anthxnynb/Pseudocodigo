Algoritmo Decimal_a_binario
    // Ejercicio: Conversión de base decimal a binario (método manual)
    // Fuente: ZIP original

    // Variables y datos del problema
    Definir NUM, RES Como Entero
    Definir BIN Como Caracter

    // Entrada de datos y validaciones
    Escribir "Ingrese un numero entero decimal no negativo:"
    Leer NUM
    // Proceso y cálculos
    Mientras NUM < 0 Hacer
        Escribir "El numero debe ser no negativo"
        Escribir "Ingrese un numero entero decimal no negativo:"
        Leer NUM
    FinMientras

    BIN <- ""
    Si NUM = 0 Entonces
        BIN <- "0"
    SiNo
        Mientras NUM > 0 Hacer
            RES <- NUM MOD 2
            BIN <- Concatenar(ConvertirATexto(RES), BIN)
            NUM <- Trunc(NUM / 2)
        FinMientras
    FinSi

    Escribir "Representacion binaria: ", BIN
FinAlgoritmo
