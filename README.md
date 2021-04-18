# system-of-separation-by-age-and-classification-in-a-soccer-game
Sistema de separação básico em C que separa jogadores por idade e categoria.

#include <stdio.h>
int main ()
{
int idade, nome;
    printf ("Digite seu nome e idade \n");
    scanf("%d%d", &idade, &nome);
    
   nome;
     printf("digite");
   switch(idade)
   {
   case 5 ... 10 :
   printf("Infantil \n");
   break;
   
   case 11 ... 15 :
   printf("Juvenil \n");
   break;
   
   case 16 ... 20 :
   printf("Junior");
   break;
   
   case 21 ... 25 :
   printf("Profissional");
   break;
   
    default :
    printf ("Valor invalido!\n");
  }
   
   return 0;
  }
