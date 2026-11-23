Algoritmo Clasificar_Beca
    // Ejercicio: Diagnóstico 2 - Clasificación para beca
    // Fuente: Diagnóstico, ejercicio 2 (enunciado del chat)

    Definir P Como Real
    Definir R, B Como Entero
    Definir C Como Caracter
    // Datos de postulacion
    Escribir "Promedio (0 a 10):"
    Leer P
    Escribir "Materias reprobadas:"
    Leer R
    Escribir "Es de primer ciclo? (S/N):"
    Leer C
    Si P < 0 O P > 10 O R < 0 O (C <> "S" Y C <> "N") Entonces
        Escribir "Datos invalidos"
    SiNo
        // Se evalua de mayor a menor porcentaje de beca
        Si P >= 9 Y R = 0 Y C = "S" Entonces
            B <- 100
        SiNo
            Si P >= 8 Y R <= 1 Entonces
                B <- 70
            SiNo
                Si P >= 7 Y R <= 2 Entonces
                    B <- 40
                SiNo
                    B <- 0
                FinSi
            FinSi
        FinSi
        Escribir "Porcentaje de beca: ", B, "%"
        Si B > 0 Entonces
            Escribir "Beca aprobada"
        SiNo
            Escribir "Beca rechazada"
        FinSi
    FinSi
FinAlgoritmo
