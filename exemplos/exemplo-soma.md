# Algoritmo: Soma n valores

variáveis:
n_valores
valor
total = 0

início:

	Escrever "Quantos valores devo somar?"
	Ler n_valores
	
	Enquanto n_valores>0
		Escrever "Digite um valor"
		Ler valor
		total = total + valor
		n_valores = n_valores - 1
	
	Escrever "A soma é: " + total
