#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>


int main(){
    int n;
    scanf("%d",&n);
    if(n==1 || n==2 || n==3){
        printf("O Numero %d e Primo\n",n);
    }else if(n%2!=0 && n%3!=0){
        printf("O Numero %d e Primo\n",n);
    }else {
         printf("O Numero %d Nao e Primo\n",n);
    }

        return 0;
}
