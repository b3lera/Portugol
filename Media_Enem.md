//Função do Algoritmo: Calcular a média do Enem 
//Autor: @b3lera

programa
{
	
	funcao inicio()
	{
		real nota1,nota2,nota3,nota4,nota5,media,total
		cadeia candidato
		
		escreva("Digite o nome do Candidato: ")
		leia(candidato)
		escreva("Linguagens, Códigos e suas Tecnologias: ")
		leia(nota1)	
		escreva("Ciências Humanas e suas Tecnologias: ")
		leia(nota2)
		escreva("Ciências da Natureza e suas Tecnologias: ")
		leia(nota3)
		escreva("Matemática e suas Tecnologias: ")
		leia(nota4)
		escreva("Redação: ")
		leia(nota5)
		
		media = (nota1+nota2+nota3+nota4+nota5)/5
	     total = (nota1+nota2+nota3+nota4+nota5)
	     escreva("Total de pontos: " + total)
		
		escreva("\n" + "O Candidato: " + candidato + " obteve a média: " + media)
		
		//verifica se a média é maior ou igual a 500
		se(media>=500) {
			escreva("\n" + "Parabéns!! Você foi Bem!!")
		}
		
		//caso a média seja menor que 500
		senao{ 
			escreva("\n" + "Parabéns pelo seu desempenho.")	
		}

		
	}
	
	  

	
}
