```
Algoritmo averageSales
	Imprimir "Hey. How many sales did you do?"
	Leer salesN
	
	Para sale = 1 Hasta salesN Con Paso 1 Hacer
		Imprimir "How much was it?"
		Leer saleAmount
		totalAmount = totalAmount + saleAmount
	FinPara
	
	Imprimir "The sales average is: " totalAmount/salesN
	
	si salesN<5 Entonces
		averageC = totalAmount*.1
	SiNo
		averageC = totalAmount*.15
	FinSi
	
	Imprimir "The comission you will get is: " averageC
FinAlgoritmo
```