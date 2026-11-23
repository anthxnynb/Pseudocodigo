Algoritmo Costo_total_viaje
    // Ejercicio: Costo total de un viaje con peajes
    // Fuente: ZIP original

    // Variables y datos del problema
    Definir DIS, CON, PCL, LIT, CC Como Real
    Definir CP, CTP, CT Como Real
    Definir NP Como Entero

    // Entrada de datos y validaciones
    Escribir "Ingrese la distancia del viaje en km:"
    Leer DIS
    // Proceso y cálculos
    Mientras DIS <= 0 Hacer
        Escribir "La distancia debe ser mayor que 0"
        Escribir "Ingrese la distancia del viaje en km:"
        Leer DIS
    FinMientras

    Escribir "Ingrese el rendimiento del auto en km por litro:"
    Leer CON
    Mientras CON <= 0 Hacer
        Escribir "El rendimiento debe ser mayor que 0"
        Escribir "Ingrese el rendimiento del auto en km por litro:"
        Leer CON
    FinMientras

    Escribir "Ingrese el precio del combustible por litro:"
    Leer PCL
    Mientras PCL < 0 Hacer
        Escribir "El precio no puede ser negativo"
        Escribir "Ingrese el precio del combustible por litro:"
        Leer PCL
    FinMientras

    Escribir "Ingrese la cantidad de peajes:"
    Leer NP
    Mientras NP < 0 Hacer
        Escribir "La cantidad de peajes no puede ser negativa"
        Escribir "Ingrese la cantidad de peajes:"
        Leer NP
    FinMientras

    Escribir "Ingrese el costo unitario de cada peaje:"
    Leer CP
    Mientras CP < 0 Hacer
        Escribir "El costo del peaje no puede ser negativo"
        Escribir "Ingrese el costo unitario de cada peaje:"
        Leer CP
    FinMientras

    LIT <- DIS / CON
    CC <- LIT * PCL
    CTP <- NP * CP
    CT <- CC + CTP

    Escribir "Litros necesarios: ", LIT
    Escribir "Costo de combustible: $", CC
    Escribir "Costo de peajes: $", CTP
    Escribir "Costo total del viaje: $", CT
FinAlgoritmo
