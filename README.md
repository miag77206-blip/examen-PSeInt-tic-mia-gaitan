# examen-PSeInt-tic-mia-gaitan
Algoritmo Ejercicio_01
		Definir N, i, sumaPares, sumaImpares Como Entero
		sumaPares <- 0
		sumaImpares <- 0
		Escribir "Ingrese un número entero positivo N:"
		Leer N
		Para i <- 1 Hasta N Con Paso 1 Hacer
			Si i MOD 2 = 0 Entonces
				sumaPares <- sumaPares + i
			SiNo
				sumaImpares <- sumaImpares + i
			FinSi
		FinPara
		Escribir "La suma de los números pares es;" sumaPares
		Escribir "La suma de los números impares es;" sumaImpares
		
