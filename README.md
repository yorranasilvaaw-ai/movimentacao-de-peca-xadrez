#include <stdio.h>

int main(){
    printf("----movimentacao de xadrez----\n\n");
    printf("Movimento da Torre(5 casas para a direita):\n");
    int casastorre= 5;
    for (int i=1;i<=casastorre;i++){printf("Direita\n");
    }
    printf("\n");

    printf("Movimento do bispo(5 casas na diagonal superior direita):\n");
    int casasbispo = 5;
    int contadorbispo = 1;
    while (contadorbispo<=casasbispo){
        printf("Cima,direita\n");
        contadorbispo++;
    }
    printf("\n");
      
    printf("Movimento da Rainha(8 casas para a esquerda):\n");
    int casasrainha = 8; 
    int contadorrainha =1;
    do {
        printf("Esquerda\n");
        contadorrainha++;
    }while (contadorrainha <= casasrainha);

   return 0;

}


