#include <stdio.h>

#include <stdlib.h>


int main()



{



   int first_num;
   
   int sec_num ;
   
   char  oprator;


   printf("please enter your first number\n ");

   scanf("%d",&first_num);
    printf("please enter your oprator\n ");

   scanf("%s",&oprator);
   printf("please enter your sec number \n ");
   scanf("%d",&sec_num);

   if (oprator == '+'){

    printf("your result is %d",first_num+sec_num);

   }
   else if (oprator == '-'){


 printf("your result is %d",first_num-sec_num);


   }
   else if (oprator == '*'){


 printf("your result is %d",first_num*sec_num);


   }
    else if (oprator == '/'){


 printf("your result is %d",first_num/sec_num);


   }
   else if (oprator == '%'){


 printf("your result is %d",first_num%sec_num);


   }


   else {

    printf(" wrong oprator");



   }

















    return 0;
}
