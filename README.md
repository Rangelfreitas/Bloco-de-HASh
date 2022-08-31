#include <stdio.h>
#include <cs50.h>


int main (void){

    //variavel tamanho
    int tam;
    do
    {
        //pede tamanho de 1 ao 8
        tam = get_int ("altura do 1 ao 8:");

    }
    while (tam < 1 || tam > 8);


    //variavel espaço
    int esp;


    //quantos # vai sair
    for (int i = 1; i <= tam; i++)
    {

    //blocos em brancos
        esp = tam -i;

    for (int j = 0; j < esp; j++)
    {
        printf (" ");

         }

    for (int j = 0; j < (tam - esp); j++)
{
    printf ("#");

}

printf ("\n");

}

}
