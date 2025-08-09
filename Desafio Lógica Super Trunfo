#include <stdio.h>
#include <stdlib.h>

        // Desafio: Super Trunfo De Paises Versão 1.3;
        // Dividir Para Conquistar!

        int main() {

        // Declarando as Variaveis!

          char Estado1[50], Estado2[50];
          char Codigo1[50], Codigo2[50];
          char NomedaCidade1[50], NomedaCidade2[50];

          unsigned int Populacao1, Populacao2;
          float Area1, Area2;
          float PIB1, PIB2;
          unsigned int NumerodePontosTuristicos1, NumerodePontosTuristicos2;

          float DensidadePopulacional1, DensidadePopulacional2;
          float PIBperCapita1, PIBperCapita2;

          float SuperPoder1, SuperPoder2;
          unsigned int Resultado1, Resultado2;
        


  //Calcular a Densidade Populacional e o PIB per Capita: Assim como no nível intermediário, calcule e armazene esses valores.

  // Exibir As Perguntas da Carta 1

    printf("\033[1;34m Desafio Super Trunfo! \033[0m \n ");
      printf("    (Carta 1)\n\n");

    printf("Digite o Estado: ");
    scanf("%s", Estado1);

    printf("Digite o Código: ");
    scanf("%s", Codigo1);
   
    printf("Digite o Nome_Da_Cidade: ");
    scanf("%s", NomedaCidade1);

    printf("Didite a População: ");
    scanf("%d", &Populacao1);

    printf("Digite a Área: ");
    scanf("%f", &Area1);

    printf("Digite o PIB: ");
    scanf("%f", &PIB1);

    printf("Digite o Número de Pontos Turísticos: ");
    scanf("%u", &NumerodePontosTuristicos1);

  // Limpar Informações da Carta 1 da Tela!

    system("clear");

  // Exibir As Perguntas Da Carta 2

    printf("\033[1;31m Desafio Super Trunfo!\033[0m \n ");
      printf("    (Carta 2)\n\n");

    printf("Digite o Estado: ");
    scanf("%s", Estado2);

    printf("Digite o Código: ");
    scanf("%s", Codigo2);

    printf("Digite o Nome_Da_Cidade: ");
    scanf("%s", NomedaCidade2);

    printf("Didite a População: ");
    scanf("%d", &Populacao2);

    printf("Digite a Área: ");
    scanf("%f", &Area2);

    printf("Digite o PIB: ");
    scanf("%f", &PIB2);

    printf("Digite o Número de Pontos Turísticos: ");
    scanf("%u", &NumerodePontosTuristicos2); 

  // Limpar Informações da Carta 2 da Tela!

    system("clear");

  // Conversão dos Resultados Digitados:
  // Calculando a Densidade Populacional e PIBperCapita.

    DensidadePopulacional1 = Populacao1 / Area1;
    DensidadePopulacional2 = Populacao2 / Area2;

    PIBperCapita1 = PIB1 / Populacao1;
    PIBperCapita2 = PIB2 / Populacao2;

  /*Calcular o Super Poder:Para cada carta, calcule o "Super Poder"
  somando todos os atributos numéricos população, área, PIB, 
  número de pontos turísticos, PIB per capita e o inverso da densidade 
  populacional – quanto menor a densidade, maior o poder:*/


    SuperPoder1 = Populacao1 + Area1 + PIB1 + NumerodePontosTuristicos1 + 
    PIBperCapita1 + (DensidadePopulacional1 / 1);
   
    SuperPoder2 = Populacao2 + Area2 + PIB2 + NumerodePontosTuristicos2 + 
    PIBperCapita2 + (DensidadePopulacional2 / 1);


   /** Exibir as Informações da Carta 1 */
  // Exibir os Resultados das Comparações!
  // Adicionei Cor para Diferenciar as Cartas e os Valores!

    
    printf("\n\n \033[1;34m Informações_Da_Carta 1: \033[0m \n\n");

    printf("Estado: \033[1;34m%s\033[0m \n", Estado1);
    printf("Código: \033[1;34m%s\033[0m \n", Codigo1);
    printf("Cidade: \033[1;34m%s\033[0m \n", NomedaCidade1);
    printf("População: \033[1;34m%'.3d Mi\033[0m \n", Populacao1);
    printf("Área: \033[1;34m%'.1fkm²\033[0m \n", Area1);
    printf("PIB: \033[1;34m%'.2f Bi\033[0m \n", PIB1);
    printf("Pontos Turísticos: \033[1;34m%u Lugares\033[0m \n", NumerodePontosTuristicos1);

  // exibir a Densidade Populacional e PIB Capita da Carta 1:

    printf("Densidade Populacional: \033[1;34m%'.2f Hab/km²\033[0m \n", DensidadePopulacional1);
    printf("PIB per Capita: \033[1;34m%'.2f R$\033[0m \n", PIBperCapita1);

  // Exibir o Super_Poder:

    printf("Super Poder: \033[1;34m%'.2fPontos \033[0m \n\n", SuperPoder1);


   /** Exibir as Informações da Carta 2 */
  // Exibir os Resultados das Comparações:

    printf("\n\n \033[1;31m Informações_Da_Carta 2: \033[0m \n\n");

    printf("Estado: \033[1;31m%s\033[0m \n", Estado2);
    printf("Código: \033[1;31m%s\033[0m \n", Codigo2);
    printf("Cidade: \033[1;31m%s\033[0m \n", NomedaCidade2);
    printf("População: \033[1;31m%'.3d Mi\033[0m \n", Populacao2);
    printf("Área: \033[1;31m%'.1fkm²\033[0m \n", Area2);
    printf("PIB: \033[1;31m%'.2f Bi\033[0m \n", PIB2);
    printf("Pontos Turísticos: \033[1;31m%u Lugares\033[0m\n", NumerodePontosTuristicos2);

  // exibir a Densidade Populacional e PIB Capita da Carta 2:

    printf("Densidade Populacional: \033[1;31m%'.2f Hab/\033[0m \n", DensidadePopulacional2);
    printf("PIB per Capita: \033[1;31m%'.2f R$\033[0m \n", PIBperCapita2);

  // Exibir o Super Poder Destacado!

    printf("Super Poder: \033[1;31m%'.2f Pontos\033[0m \n", SuperPoder2);


  // Exibindo as Comparações entre as Cartas!

  // 1.Comparar um atributo escolhido para realizar a comparação entre as duas cartas.

    printf("\n\n\033[1;33m Diferença da população dos Estados entre as Cartas \033[0m\n\n");

    if ( Populacao1 > Populacao2 ) {
    printf("Estado de \033[1;33m%s: %d Mi\033[0m\n", Estado1, Populacao1);
    printf("Estado de \033[1;33m%s: %d Mi\033[0m\n", Estado2, Populacao2);
    printf("Resultado: Carta 1 %s:\033[1;33m('Venceu')\033[0m", Estado1);
    } else { if ( Populacao1 < Populacao2) {
    printf("Estado de \033[1;33m%s: %d Mi\033[0m\n",Estado1, Populacao1);
    printf("Estado de \033[1;33m%s: %d Mi\033[0m\n",Estado2, Populacao2);
    printf("Resultado: Carta 2 %s:\033[1;33m('Venceu')\033[0m", Estado2);  
    } else {
    printf("Estado de \033[1;33m%s: %d Mi\033[0m\n", Estado1, Populacao1);
    printf("Estado de \033[1;33m%s: %d Mi\033[0m\n", Estado2, Populacao2);
    printf("Resultado: \033[1;33m('Empate')\033[0m\n ");

  }
}

  // 2.A carta com o maior valor vence.

    Resultado1 = Populacao1 + Area1 + PIB1 + PIBperCapita1 + NumerodePontosTuristicos1 + SuperPoder1;
    Resultado2 = Populacao2 + Area2 + PIB2 + PIBperCapita2 + NumerodePontosTuristicos2 + SuperPoder2;

    printf("\n\n\033[1;33m Carta Com Maior Atributos (Vence)! \033[0m\n\n ");

      if ( Resultado1 > Resultado2 ) {
    printf("Carta 1:\033[1;33m('Venceu')\033[0m ");
    } else { if ( Resultado1 < Resultado2 ) {
    printf("Carta 2:\033[1;33m('Venceu')\033[0m ");
    } else {
    printf("\033[1;33m('Empate')\033[0m\n ");

  }  
}
  
  // 3.Densidade Populacional, a carta com o menor valor vence.

    printf("\n\n\033[1;33m Menor Densidade Populacional Entre as Cartas (Vence)! \033[0m\n\n ");

    if ( DensidadePopulacional1 < DensidadePopulacional2 ) {
    printf("Carta 1:\033[1;33m('Venceu')\033[0m\n");
    } else {
    printf("Carta 2:\033[1;33m('Venceu')\033[0m\n");

  }


   return 0;

 }
