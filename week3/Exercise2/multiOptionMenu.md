```

Algoritmo multiOptionMenu
	Imprimir 'Available Options'
	Imprimir '1. Sum 2 numbers'
	Imprimir '2. Print DOW'
	Imprimir '3. Lenght of word'
	Imprimir 'Enter the option:'
	Leer option
	Segun option Hacer
		1:
			Imprimir 'Option 1. Sum 2 numbers'
			Imprimir 'Enter the first number'
			Leer n1
			Imprimir 'Enter the second number'
			Leer n2
			Imprimir 'Result: ' + ConvertirATexto(n1 + n2)
		2:
			Imprimir 'Option 2.  Print DOW'
			Imprimir 'Enter the DOW in numbers (1-7)'
			Leer day
			Segun day Hacer
				1:
					Imprimir 'Monday'
				2:
					Imprimir 'Tuesday'
				3:
					Imprimir 'Wednesday'
				4:
					Imprimir 'Thursday'
				5:
					Imprimir 'Friday'
				6:
					Imprimir 'Saturday'
				7:
					Imprimir 'Sunday'
				De Otro Modo:
					Imprimir 'That's not a day'
			Fin Segun
		3:
			Imprimir 'Option 3. Lenght of word'
			Imprimir 'Enter the text'
			Leer string
			Imprimir 'Result: ' + ConvertirATexto(Longitud(string))
		De Otro Modo:
			Imprimir 'Incorrect option'
	Fin Segun
FinAlgoritmo

```