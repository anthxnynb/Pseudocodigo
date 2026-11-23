Algoritmo Costo_envio
    // Ejercicio: Costo de envío con peso volumétrico
    // Fuente: ZIP original

    // Variables y datos del problema
    Definir PR, L, A, H, PV, PC, CT Como Real

    // Entrada de datos y validaciones
    Escribir "Ingrese el peso real en kg:"
    Leer PR
    Escribir "Ingrese largo en cm:"
    Leer L
    Escribir "Ingrese ancho en cm:"
    Leer A
    Escribir "Ingrese alto en cm:"
    Leer H

    // Proceso y cálculos
    Si PR < 0 O L < 0 O A < 0 O H < 0 Entonces
        Escribir "Datos no validos"
    SiNo
        PV <- (L * A * H) / 5000
        Si PR >= PV Entonces
            PC <- PR
        SiNo
            PC <- PV
        FinSi
        CT <- PC * 2.50
        Escribir "Peso volumetrico: ", PV, " kg"
        Escribir "Peso a cobrar: ", PC, " kg"
        Escribir "Costo total: $", CT
    FinSi
FinAlgoritmo
