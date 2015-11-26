#include <stdio.h>
  
int main() {
  
    int senha;
            while(senha != 2002){ // o while e usado para repitir enquanto for diferente de 2002
            scanf("%d",&senha); // le a senha do usuario
                 
                if(senha == 2002){  // se a senha for 2002 = acesso permitido
                            printf("Acesso Permitido\n"); 
            }else
                            printf("Senha Invalida\n");
        }
  
    return 0;
}
