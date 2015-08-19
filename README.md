# practica1
primer ejercicio triangulos
#include<stdio.h>
int a,b,c;
main()
{
	printf("programa para saber que triangulo es  \n");
	printf("Dame el primer lado del triangulo : ");
	scanf("%d",&a);
	printf("Dame el segundo lado del triangulo : ");
	scanf("%d",&b);
	printf("Dame el tercer lado del triangulo : ");
	scanf("%d",&c);
	
	if((a==b)&&(b==c))
	{
		printf("Es un triangulo equilatero");
	}
	else
	{
	
		if((a==b)||(a==c)||(c==b))
			printf("Es un triangulo isoceles");
		else
			printf("Es un triangulo escaleno");
	}
	printf("\n");
	system("pause");
	return 0;
}
