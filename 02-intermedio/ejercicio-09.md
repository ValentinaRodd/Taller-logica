Algoritmo Seriede_Fibonacci
	Definir n, i Como Entero
	Definir a, b, siguiente Como Real
	Escribir  "Ingrese la cantidad de terminos de fibonacci a generar: " 
	Leer n
	a <- 0
	b <- 1
	
	Escribir "Serie de fibonacci: "
	si n >= 2 Entonces
		Escribir Sin Saltar a, " "
	FinSi
	si n >= 2 Entonces
		Escribir Sin Saltar b, " "
	FinSi
	para i <- 3 Hasta n Hacer
		siguiente <- a + b
		Escribir Sin Saltar siguiente, " "
		a <- b
		b <- siguiente
	FinPara
	Escribir " " salto de linea final

FinAlgoritmo

