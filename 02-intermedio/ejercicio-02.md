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
Algoritmo Contadorde_vocales
	Definir texto_ Como Caracter
	Definir i, contador Como Entero
	Definir letra Como Caracter
	Escribir "Ingrese una cadena de texto: "
	Leer texto_
	contador <- 0
	para i <- 1 Hasta Longitud(texto_) Hacer
		letra <- Minusculas(Subcadena(texto_, i, i))
		
		si letra = "a" O letra = "e" O letra = "i" O letra = "o" O letra = "u" Entonces
			contador <- contador + 1
		FinSi
	FinPara
	Escribir "El numero total de vocales en la frase es: " contador  
FinAlgoritmo


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






Algoritmo Sistema_login
	Definir claveCorrecta, claveingresada Como Caracter
	Definir intentos Como Entero
	Definir acceso como logico
	
	claveCorrecta <- "Valentina26."
	intentos <- 3
	acceso <- Falso
	Mientras intentos > 0 y no acceso Hacer
	Escribir "Ingresa tu contraseña (te quedan ", intentos, " intentos): "
		Leer claveingresada
		Si claveingresada   claveCorrecta Entonces
			acceso <- Verdadero
			Escribir "Acceso concedido"
		SiNo
			intentos <- intentos -1
			Escribir "Contraseña incorrecta"
		FinSi
	FinMientras
	si no acceso Entonces
		Escribir "Acceso bloqueado. Intentalo de nuevo mas tarde"
	FinSi
FinAlgoritmo







