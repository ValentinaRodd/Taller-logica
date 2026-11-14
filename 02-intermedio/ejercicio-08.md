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

