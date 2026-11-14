Algoritmo Calculadora_basica
	Definir numero1, numero2, resultado Como Real
	Definir operacion Como Caracter
	Escribir "Ingrese el primer numero: "
	Leer numero1
	Escribir "Ingrese el segundo numero: "
	Leer numero2
	Escribir "Ingrese la operacion que desea (+, -, *, /): "
	Leer operacion
	
	Segun operacion Hacer
		"+": 
			resultado <- numero1 + numero2
			Escribir "resultado: ", resultado
		"-": 
			resultado <- numero1 - numero2
			Escribir "resultado: ", resultado
		"*": 
			resultado <- numero1 * numero2
			Escribir "resultado: ", resultado
		"/": 
			si num2 = 0 Entonces
				Escribir "Error: No se puede dividir entre cero"
			SiNo
				resultado <- numero1 / numero2
				Escribir "resultado es: ", resultado
			FinSi
	FinSegun
	
FinAlgoritmo
