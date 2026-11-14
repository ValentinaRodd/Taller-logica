Algoritmo Sumanumeros_pares
	Definir n, i, suma Como Entero
	Escribir "Ingrese el valor limite n: "
	Leer n
	
	suma <- 0
	Para i <- 2 Hasta n Con Paso 2 Hacer
			suma <- suma + i
	FinPara
	
	Escribir "La suma de los numeros pares entre 1 y ", "es: ", suma
FinAlgoritmo
