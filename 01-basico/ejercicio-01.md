Algoritmo Calculo_promedio
	Definir nota1, nota2, nota3, promedio Como Real
	Definir Pasamosnota_superior3 Como logico
	Escribir "Pasamos con nota superior a 3"
	Escribir "Ingrese la primera nota: "
	Leer nota1
	Escribir "Ingrese la segunda nota: "
	Leer nota2
	Escribir "Ingrese la tercer nota: "
	Leer nota3
	
	promedio <- (nota1 + nota2 + nota3) /3 
	Escribir "El promedio final es: ", promedio 
	Escribir "Pasamos con nota superior a 3 (Verdadero/Falso)"
	Leer Pasamosnota_superior3
	SI Pasamosnota_superior3 Entonces
		
		Escribir "Si paso"
	sino 
		Escribir "No paso"
		
	FinSi
	FinAlgoritmo

Algoritmo Area_Rectangulo
	Definir base, altura, area, perimetro Como Real
	Escribir "Ingrese la base del rectangulo: "
	Leer base
	Escribir "Ingrese la altura del rectangulo: "
	Leer altura
	
	area <- base * altura
	perimetro <- 2 * (base + altura)
	
	Escribir "El area es: ", area
	Escribir "El perimetro es: ", perimetro
		
FinAlgoritmo
Algoritmo Signo_numerico
	Definir Numero_ Como Entero
	Escribir "Ingrese un numero entero: "
	Leer Numero_
	
	SI Numero_ > 0 Entonces
		Escribir "El numero es positivo"
	SiNo
		Escribir "El numero es negativo"
		si Numero_ < 0 Entonces
			Escribir "El numero es negativo"
		SiNo
			Escribir "El numero es cero"
		FinSi
	FinSi
FinAlgoritmo


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
Algoritmo Conversion_temperatura
	Definir celsius, fahrenheit Como Real
	Escribir "Ingrese la temperatura en grados celsius: "
	Leer celsius
	
	fahrenheit <- (celsius * 9 / 5) + 32
	Escribir celsius, "° C equivalen a: ", fahrenheit, "° F"
FinAlgoritmo

