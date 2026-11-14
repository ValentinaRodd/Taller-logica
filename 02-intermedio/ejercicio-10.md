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
