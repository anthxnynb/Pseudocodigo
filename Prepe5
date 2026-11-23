Algoritmo Decimal_a_hexadecimal
    // Ejercicio: Conversión de decimal a hexadecimal
    // Fuente: ZIP original

    // Variables y datos del problema
    Definir NUM, RES Como Entero
    Definir HEX, DIG Como Caracter

    // Entrada de datos y validaciones
    Escribir "Ingrese un numero entero decimal no negativo:"
    Leer NUM
    // Proceso y cálculos
    Mientras NUM < 0 Hacer
        Escribir "El numero debe ser no negativo"
        Escribir "Ingrese un numero entero decimal no negativo:"
        Leer NUM
    FinMientras

    HEX <- ""
    Si NUM = 0 Entonces
        HEX <- "0"
    SiNo
        Mientras NUM > 0 Hacer
            RES <- NUM MOD 16
            Si RES < 10 Entonces
                DIG <- ConvertirATexto(RES)
            SiNo
                Segun RES Hacer
                    10:
                        DIG <- "A"
                    11:
                        DIG <- "B"
                    12:
                        DIG <- "C"
                    13:
                        DIG <- "D"
                    14:
                        DIG <- "E"
                    15:
                        DIG <- "F"
                FinSegun
            FinSi
            HEX <- Concatenar(DIG, HEX)
            NUM <- Trunc(NUM / 16)
        FinMientras
    FinSi

    Escribir "Representacion hexadecimal: ", HEX
FinAlgoritmo
