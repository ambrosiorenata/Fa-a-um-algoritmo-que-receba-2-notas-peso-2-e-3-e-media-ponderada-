# Fa-a-um-algoritmo-que-receba-2-notas-peso-2-e-3-e-media-ponderada-
#include <stdio.h>


   int main()
{
    // declara as variáveis 
	float n1, n2; 
	printf("\nRecebe duas notas, calcula e mostra a média ponderada dessas notas. ");
    printf("\nConsiderando peso 2 para a primeira nota e peso 3 para a segunda nota.\n");
    
    // Solicitando dados do usuarios Notas
    printf("\nDigite a primeira nota: ");
	scanf("%f", &n1); // guarda o valor em n1
		
	printf("Digite a segunda nota: ");
	scanf("%f", &n2); // guarda o valor em n2
	
	//Verificação condicional 
	printf("\nA primeira nota tem peso igual a 2");
	printf("\nA segunda nota tem peso igual a 3");
	
	// Calcula e exibe o resultado
	printf("\n\nA média ponderada de %.2f + %.2f = %.2f \n\n", n1, n2, (((n1*2) + (n2*3)) /5));

	return 0;
}

