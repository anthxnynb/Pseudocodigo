Algoritmo ContarAprobadosReprobados
    // Ejercicio: pseudocódigo Aprobados o reprobados
    // Fuente: ZIP original

    // Variables y datos del problema
   Definir N, X, A, R Como Entero
   Definir NOTA Como Real
    // Entrada de datos y validaciones
   Escribir "Ingrese el numero de alumnos:"
    Leer N
    // Proceso y cálculos
     A <- 0
     R <- 0
   Mientras N <=0 hacer
    Escribir "La cantidad ingresada no puede ser menor ni igual a 0"
    Escribir "Ingrese el numero de alumnos:"
    Leer N
   FinMientras
   Para X <- 1 Hasta N Hacer
       Escribir "Ingrese la calificacion del alumno: ", X
       Leer NOTA
   Mientras NOTA <0 o NOTA >10 hacer
    Escribir "La nota no puede ser negativa ni mayor a 10"
    Escribir "Ingrese la calificacion del alumno: ", X
    Leer NOTA
   FinMientras
      Si NOTA >= 7 Entonces
          A <- A + 1
       SiNo
            R <- R + 1
       FinSi
   FinPara

    Escribir "Cantidad de aprobados: ", A
    Escribir "Cantidad de reprobados: ", R
FinAlgoritmo
