1.
inicio
    ingresar "puntos x1, y1"
    leer x1, x2
    ingresar "puntos x2, y2"
    leer x2, y2
    Calcular D = sqrt((X2 - X1)^2 + (Y2 - Y1)^2)
    mostrar distancia " la distancia entre los puntos es: ",D
Fin

2.
inicio
    monstrar "Ingrese la cantidad necesara de tela en metros"
    leer metros
    pulgada=(metro/0.0254)
    mostrar " La cantidad de tela en pulgadas es: ", pulgada
fin
[imagenes](/Imagenes/imagen2.jpeg)


3.Inicio
    Mostrar "Ingrese los valores del cateto A"
    Leer A
    Mostrar "Ingrese los valores del cateto B"
    Leer B
    C = sqrt(A^2 + B^2)
    Mostrar "La hipotenusa del triángulo es: ", C
Fin


4. Inicio
    mostrar "Año de nacimiento y año actual"
    ingresar "Año de nacimiento: "
    Leer Año de nacimiento 
    ingrese "Mes de nacimeinto: " 
    leer Mes de nacimiento 
    ingrese "Dia de nacimiento: "
    leer Dia de naciemiento 

    Ingresar "Año actual"
    leer año actual 
    ingresar "Dia actual: "
    leer dia actual 
    ingresar "Mes actual: "
    leer mes actual 

    edad = año_actual - año_nacimiento
        Si (mes_actual < mes_nacimiento) o (mes_actual = mes_nacimiento y dia_actual < dia_nacimiento) Entonces
        edad = edad - 1
        mostrar "Usted no ha cumplido años 
        Si (mes_actual = mes_nacimiento y dia_actual = dia_nacimiento) Entonces
        Escribir "Feliz Cumpleaños"
    Sino
        Escribir "Ya ha celebrado su cumpleaños este año."
        Escribir "La edad actual de la persona es: ", edad
fin

5. Inicio 
    ingrese "Horas trabajadas a la semana: "
    leer horas_trabajadas 
    ingrese "Pago por hora: "
    leer pago_por_hora 
    si horas_trabajadas > 50 
    mostrar "No se permite trabajar más de 50 horas."
    Si horas_trabajadas <= 40 Eentonces
            sueldo = horas_trabajadas * pago_por_hora
    SI horas_trabajadas <= 45 ENTONCES
            sueldo = (40 * pago_por_hora) + ((horas_trabajadas - 40) * (2 * pago_por_hora))

    sino Si horas_trabajadas <= 50 ENTONCES
            sueldo = (40 * pago_por_hora) + (5 * (2 * pago_por_hora)) + ((horas_trabajadas - 45) * (3 * pago_por_hora))
        FIN Si
        escribir "El sueldo semanal es: ", sueldo
    fin 

6. Inicio
    Describir N, cantidad, ceros, menores, mayores
    ceros = 0
    menores = 0
    mayores = 0
 
    ingrese "Ingrese la cantidad de números a evaluar (N): "
    leer N
 
    para x desde 1 hasta N hacer
        ESCRIBIR "Ingrese el número ", x, ": "
        leer cantidad
 
        Si cantidad = 0 ENTONCES
            ceros = ceros + 1
        SI cantidad < 0 ENTONCES
            menores = menores + 1
        SINO
            mayores = mayores + 1
        Fin Si
    fin para 
 
    escribir "Cantidad de ceros: ", ceros
    escribir "Cantidad de números menores a cero: ", menores
    escribir "Cantidad de números mayores a cero: ", mayores
fin