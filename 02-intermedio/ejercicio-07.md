Algoritmo Factorialde_N
	Definir n, i Como Entero
	Definir factorial Como Real
	
	Escribir "Ingrese un numero entero positivo: "
	Leer n 
	factorial <- 1
	Si n < 0 Entonces
		Escribir "Error: El numero debe ser positivo"
	SiNo
		Para i <- 1 Hasta n Hacer
			factorial <- factorial * i
		FinPara
		Escribir "El factorial de ", n, " es: ", factorial
	FinSi
FinAlgoritmo
