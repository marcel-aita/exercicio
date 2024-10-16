# Algoritmo: valida senha

variáveis:

senha_correta := "algo01"
senha_digitada
chances := 3

início:

Enquanto chances>0 
	Ler senha_digitada
	Se senha_digitada = senha_correta
		Escrever "Ok"
		Fim do programa
	Senão
		chances = chances - 1


