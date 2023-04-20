# ativiidade
primeira atividade 

#include <stdio.h>
#include <string.h>
int main()
{
	int idade,ano;
	float altura;
	char nome [30];
	/* entrada de dados*/
	/* mensagem ao usuario*/
	printf ("digite seu nome");
	scanf ("%s", nome);
	printf(" digite a idade");
	scanf ("%d", &idade);
	printf("informe a altura");
	scanf ("%f", &altura);
	/* processamento*/
	ano= 2022 - idade;
	/* saida de dados   */
	printf(" \n O nome e: %s", nome);
	printf(" \n A idade é: %d", idade);
	printf(" \n A altura é: %.2f", altura);
	printf("\n O ano de nascimento é: %d", ano );
	 return (0);
	
}
