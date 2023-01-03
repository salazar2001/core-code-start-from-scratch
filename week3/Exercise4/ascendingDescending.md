```
Algoritmo orderNumbers
	Imprimir "Enter a number"
	Leer n1
	Imprimir "please select the following:"
	Imprimir "1. Show ascendent order"
	Imprimir "2. Show descendent order"
	Leer option
	Segun option Hacer
		1:
			Para i <- 0  Hasta n1 Con Paso 1 Hacer
				Imprimir ConvertirATexto(i)
			Fin Para
		2:
			Para i <- n1  Hasta 0 Con Paso -1 Hacer
				Imprimir ConvertirATexto(i)
			Fin Para
		De Otro Modo:
			Imprimir "Incorrect option"
	Fin Segun
FinAlgoritmo
```