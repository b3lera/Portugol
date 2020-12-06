//Tabuada
//Autor: @b3lera

programa
{
	
	funcao inicio()
	{
		inteiro contador,limite,resultado,tabuada, vezes

		contador = 0
		
		
		escreva("Escreva qual tabuada deseja saber? ")
		leia(tabuada)

		escreva("Qual limite? ")
		leia(vezes)
		
		limite =(vezes)
		faca{

			resultado = tabuada * contador
			escreva(tabuada + " X " + contador + " = " + resultado + "\n")
			contador ++
		}enquanto (contador<=limite)
	}
}
