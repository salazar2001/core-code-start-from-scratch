```
Algoritmo greetings
	Imprimir "Hello."
	answer = "Yes"
	Mientras answer == "Yes" | answer == "yes" | answer == "YES" Hacer
		Imprimir "What time is it?"
		Leer hour
		si hour >= 0 & hour<=12
			Imprimir "Good morning, King"
		FinSi
		si hour >= 13 & hour<=18
			Imprimir "Good afternoon, King"
		FinSi
		si hour >= 19 & hour<=23
			Imprimir "Good night, King"
		FinSi
		Imprimir "Want to continue? Yes/No"
		Leer answer
	FinMientras
FinAlgoritmo
```