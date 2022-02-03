# simple_calculator
Simple calculator useing else-if ladder in C

#include <stdio.h>

int main() {
    int n1,n2;
    char op;
    printf ("Enter the first number \n");
    scanf ("%d",&n1);
    printf ("Enter the second number\n");
    scanf ("%d",&n2);
    printf ("select your operation (+,-,*,/)\n");
    scanf (" %c",&op);
    if (op =='+')
    {
        printf ("%d + %d = %d",n1,n2,n1+n2);
    }
    else if (op == '-')
   {
       printf ("%d - %d = %d",n1,n2,n1-n2);
   }
   else if (op == '*')
   {
     printf ("%d * %d = %d",n1,n2,n1*n2);
   }
   else if (op == '/')
   {
    printf ("%d / %d = %d",n1,n2,n1/n2);
   }
   else 
   {
       printf ("Invalid input");
   }
    
    return 0;
}
