#include <stdlib.h>
#include <stdio.h>
#define LONGEUR 2310



int main()
{
	FILE * fichier;
    fichier = fopen("~/Documents/wordle_KIADY_JEANPAUL/ressources/bdd_wordle.txt", "r"); 
    
    if (fichier!=NULL)
    {
    	printf("succed to open\n");
    	fclose(fichier);
    } 
    
    else
    {
    	printf("Failed to open\n");
    } 
}
    
