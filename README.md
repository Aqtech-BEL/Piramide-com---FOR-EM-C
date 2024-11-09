Piramide com * - FOR EM C


    int main(){
      
      int num, i = 1, j = 1;
      
      
      printf("Digite o tamanho da piramide: ");
      scanf("%d", &num);
      
      for(i = 1; i <= num; i++){
         for(j = 1; j <= i; j++){
             printf("*");
         } 
         printf("\n");
      }
      
  
      return 0;
    }
