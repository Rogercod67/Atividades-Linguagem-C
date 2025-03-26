#include <stdio.h>
#include <stdlib.h>

int dia, mes, ano;
int main(){
  printf("Adicione sua data de nascimento: \n");
  scanf("%d %d %d\n", &dia, &mes, &ano);
  printf("%d/%d/%d\n", dia, mes, ano);
  system("pause");
  return 0;
}
