```
Algoritmo switchCalculator
	Imprimir "*******Calculator*******"
	Imprimir "Enter a number"
	Leer n1
	Imprimir "Enter another number"
	Leer n2
	Imprimir "Select the operation you want to do"
	Imprimir "+ | - | * | / "
	Leer operation
	Segun operation Hacer
		"+":
			result<-n1+n2
			Imprimir "The result is: " ConvertirATexto(result)
		"-":
			result<-n1-n2
			Imprimir "The result is: " ConvertirATexto(result)
		"*":
			result<-n1*n2
			Imprimir "The result is: " ConvertirATexto(result)
		"/":
			result<-n1/n2
			Imprimir "The result is: " ConvertirATexto(result)
		De Otro Modo:
			Imprimir "No es una opcion valida"
	Fin Segun
FinAlgoritmo
```
