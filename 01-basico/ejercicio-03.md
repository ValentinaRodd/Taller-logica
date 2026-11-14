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
