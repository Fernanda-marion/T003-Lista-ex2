# T003-Lista-Exercicio 2

A)

#include <stdio.h>

    int main () {
        
        float n1,n2,n3,Ordem;
        
        printf("Digite o primeiro numero:");
        scanf("%f",&n1);
        
        printf("Digite o segundo numero:");
        scanf("%f",&n2);
        
        printf("Digite o terceiro numero:");
        scanf("%f",&n3);
        
        Ordem = n3,n2,n1;
        
        printf("Numeros:%f",Ordem); 
    
        
   return 0;
   
    }

B)

#include <stdio.h>

    int main () {
        
        char nome;
        
        printf("Olá eu sou o Nº 1, como é seu nome?\n");
        printf("Escreva seu nome: ");
        scanf("%c",&nome);
        printf("Bem-vindo ao clube: %c",nome);
        
   return 0;
   
    }


C)

#include <stdio.h>
#include <stdlib.h>

    int main () {
        
    
        char nome;
        double idade,d;
        
        printf("Olá, como é seu nome?\n");
        printf("Escreva seu nome: ");
        scanf("%c",&nome);
        
        printf("Qual sua idade?:");
        scanf("%lf",&idade);
        
        d = idade*365;
        printf("Voce possui %d",dias de vida);
        
   return 0;
   
    }
D)

#include <stdio.h>
#include <stdlib.h>

    int main () {
        

        float raio,area;
        
        printf("Informe o raio do circulo: ");
        scanf("%f",&raio);
        
        area= (raio*raio)*3.14;
        
    printf("A area do circulo e:%.1f",area);
        
        
   return 0;
   
    }

E)
#include <stdio.h>
#include <stdlib.h>

    int main () {
        

        float largura,altura,litros,latas;
        
        printf("Informe a largura: ");
        scanf("%f",&largura);
        printf("Informe a altura: ");
        scanf("%f",&altura);
        
        litros= (largura*altura)*0.3;
        
    printf("A quantidade em litros para pintar a parede e: %.1f\n",litros);
    
    latas = (litros)/2;
    
    printf("A porcentagem utilizada de uma lata ou mais foi:%.1f",latas);
        
        
   return 0;
   
    }

F)

#include <stdio.h>
#include <stdlib.h>

    int main () {
        

        float grausc,grausf;
        printf("Informe a temperatura em graus celsius:");
        scanf("%f",&grausc);
        
        grausf=(9*grausc+160)/5;
        printf("Em graus fahrenheit:%.1f",grausf);
        
   return 0;
   
    }

G)

#include <stdio.h>
#include <stdlib.h>

    int main () {

        float pressao,volume,temperatura,massa de ar;
        
        printf("Informe a pressao do pneu:");
        scanf("%f",&pressao);
        printf("Informe a volume do pneu:");
        scanf("%f",&volume);
        printf("Informe a temperatura do pneu:");
        scanf("%f",&temperatura);
        
        massa de ar=pressao*volume=((temperatura+460)*0.37);
        
        printf("A massa de ar do pneu e:%.1f",massa de ar);
        
   return 0;
   
    }





    
