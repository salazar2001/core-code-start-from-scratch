```
Algoritmo simpleCalculator
	Imprimir "Calculator"
	Imprimir "Enter a number"
	Leer n1
	Imprimir "Enter another number"
	Leer n2
	Imprimir "Select the operation you want to do"
	Imprimir "+ | - | * | / "
	Leer operation
	
	si (operation == "+") Entonces
		result<-n1+n2
		Imprimir "The result is: " ConvertirATexto(result)
	FinSi
	
	si(operation == "-") Entonces
			result<-n1-n2
			Imprimir "The result is: " ConvertirATexto(result)
	FinSi
	
	si (operation == "*") Entonces
		result<-n1*n2
		Imprimir "The result is: " ConvertirATexto(result)
	FinSi
	
	si (operation == "/") Entonces
		result<-n1/n2
		Imprimir "The result is: " ConvertirATexto(result)
	FinSi
FinAlgoritmo
```
