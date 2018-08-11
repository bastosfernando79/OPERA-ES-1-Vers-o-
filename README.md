//Diretivas
#include <stdio.h>

//Função main
int main() {
  //Declaração de variáveis
  float a, b;

  //Recebimento das variáveis
  printf("Digite a: ");
  scanf("%f", &a);

  printf("Digite b: ");
  scanf("%f", &b);

  //Divulgação dos resultados
  printf("\n--RESULTADOS--");
  printf("\nSoma: %.2f", a+b);
  printf("\nMultiplicação: %.2f", a*b);
  printf("\nDivisão: %.2f", a/b);
  return 0;
}
