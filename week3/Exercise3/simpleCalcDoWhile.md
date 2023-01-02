```
Algoritmo simpleCalcDoWhile
	Imprimir "Hello will do some calculations"
	
	Hacer
		Imprimir "Enter a number"
		Leer  n1
		Imprimir "Enter another number"
		Leer n2
		Imprimir "Enter the operator: +, -, *, /"
		Leer option
		
		Segun option
			Caso "+": 
				resultado = n1 + n2
				Imprimir "The result of this operation is: " resultado
			Caso "-": 
				resultado = n1 - n2
				Imprimir "The result of this operation is: " resultado
			Caso "*": 
				resultado = n1 * n2
				Imprimir "The result of this operation is: " resultado
			Caso "/": 
				resultado = n1 / n2
				Imprimir "The result of this operation is: " resultado
		FinSegun
		
		Imprimir "Would you like to continue?"
		Leer continue
	Hasta Que continue == "No" | continue == "no"
	
FinAlgoritmo
```
