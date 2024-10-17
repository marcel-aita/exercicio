# Operações repetidas controladas

### Escreva um algorítmo que escreve 10 vezes o seu nome
	variáveis:
		n_vezes = 10
	
	início:
		Enquanto n_vezes > 0
		Escrever "meu nome"
		n_vezes = n_vezes - 1
### Escreva um algorítmo que escreve os números de 1 a 1000
	variáveis: 
		n=0
	
	início
		Enquanto n<=1000
			Escrever n, n=n+1;
				Escrever: "feito" 
### Escreva um algorítmo que escreva a tabuada do 9
	variáveis:
		n=1
	
	início:
		Enquanto n<=10 
			Escreva n +"x9="
			n=n+1 
### Modifique o algorítmo anterior para que ele:
- pergunte a tabuada de qual número deve ser gerada
- escreva a tabuada desse número
	
		variáveis: 
			n=1
			tabuada_do_t=0

		início:
			Escrever "Gerar tabuada de qual número?" 
			Ler T
			Enquanto n<=10
				Escreva n+"x"+t+"=" + (n*t)
				n=n+1
### Escreva um algoritmo que:
- pergunte um número N
- escreva a soma dos número de 0 a N

		variáves:
			//O número digitado
			N
			//acumuladora
			soma
			//contadora
			i=0 

		início:
			Escrever "Digite um número"
			Ler N
			
			Enquanto i<=N
				soma = soma + i
				i = i + i

			Escrever soma	
---