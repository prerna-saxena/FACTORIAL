# FACTORIAL
FACTORIAL


include<stdio.h>  
int main()    
{    
int i, fact=1, no;
printf("ENTER A NO\n");
scanf("%d", &no);
for(i=1; i<=no; i++)
{
    fact=fact*i;
}
 printf("FACTORIAL OF A NO IS", no , fact);
return 0;
}
