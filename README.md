# Tarefa GitHub

## Introdução a engenharia de software
	
#include <stdio.h>
	
	int main()
	{
		float nota;
		printf("Qual a minha nota?\n");
		scanf("%d", &nota);
		if(nota<=5)
		{
			printf("Tenho que melhorar.");
		}
		if(nota>5&&nota<=7)
		{
			printf("Nota regular.");
		}
		if(nota>7)
		{
			printf("Nota boa.");
		}
		return 0;
	}
		
	
	
