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
