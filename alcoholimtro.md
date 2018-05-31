#Alcoholimetro

## Problematica
detectar el color con base a la cantidad de alcohol que tiene el individuo
exiten 4 colores
rojo 5.45 o mas
naranja 3.2 a 5.44
amarrillo 2 a 3.2
verde a 0.1

## Pseudocodigo
    inicio
        leer grado de alcohol
        si (color <= 2)
            imprime verde
        sino si (color => 2 && color <= 3.2>)
            imprime amarillo
        sino si (color => 3.2 && color <= 5.44>)
            imprime naranja
        sino
            imprime rojo