# immc
Imc 
#include<stdio.h>
float imc[5],alt,peso;
int i;

int main(){
	 for(i=0;i<5;i++){
    	printf("digite sua altura: ");
    	scanf("%d",&alt);
    	printf("digite seu peso: ");
        scanf("%d",&peso);
    imc[i]=peso/(alt*alt);
	}

printf("\nimc da pessoa 1 e: %d",1,imc[0]);
printf("\nimc da pessoa 3 e: %d",3,imc[2]);
printf("\nimc da pessoa 5 e: %d",5,imc[4]);


	
	
	
	return 0;
}
