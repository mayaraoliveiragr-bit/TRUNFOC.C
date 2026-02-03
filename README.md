#include <stdio.h>
#include <string.h>

int main() {
//colets de dados
 char estado; // Uma letra de 'A' a 'H' (representando um dos oito estados). Tipo: char
 char codigo [20]; //A letra do estado seguida de um número de 01 a 04 
 char cidade [20]; //O nome da cidade.
 int populacao; //O número de habitantes da cidade
 float area;//A área da cidade em quilômetros quadrados.
 float pib;//O Produto Interno Bruto da cidade.
 int turistico; //A quantidade de pontos turísticos na cidade.
 int contador [20] = {0};// Um contador para cada Estado


 printf("CARTA 1:\n");

 printf("Estado: ");
 scanf(" %c", &estado);
 getchar();

 printf("Código:" );
 scanf(" %s", codigo);

 printf("Nome da Cidade: ");
 scanf(" %s", cidade);

 printf("População: ");
 scanf(" %d", &populacao);

 printf("Área: ");
 scanf(" %f", &area);

 printf("PIB: ");
 scanf(" %f", &pib);

 printf("Número de Pontos Turísticos: ");
 scanf(" %d", &turistico);

 printf("CARTA 1\n");
 printf("ESTADO: %c\n", estado); 
 printf("CÓDIGO: %s\n", codigo);
 printf("NOME DA CIDADE: %s\n", cidade);
 printf("População: %d\n", populacao);
 printf("ÁREA: %.3f KM²\n", area);
 printf("PIB: %.2f\n", pib);
 printf("NÚMERO DE PONTOS TURÍSTICOS: %d \n",turistico);

 printf("CARTA 2:\n");

 printf("Estado: ");
 scanf(" %c", &estado);
 getchar();

 printf("Código:" );
 scanf(" %s", codigo);

 printf("Nome da Cidade: ");
 scanf(" %s", cidade);
 
 printf("População: ");
 scanf(" %d", &populacao);

 printf("Área: ");
 scanf(" %f", &area);

 printf("PIB: ");
 scanf(" %f", &pib);

 printf("Número de Pontos Turísticos: ");
 scanf(" %d", &turistico);


// RESUMO DAS INFORMAÇÕES
 printf("CARTA 2\n");
 printf("ESTADO: %c\n", estado); 
 printf("CÓDIGO: %s\n", codigo);
 printf("NOME DA CIDADE: %s\n", cidade);
 printf("População: %d\n", populacao);
 printf("ÁREA: %.3f KM²\n", area);
 printf("PIB: %.2f\n", pib);
 printf("NÚMERO DE PONTOS TURÍSTICOS: %d\n", turistico);

 return 0;

}
