#include <stdio.h>
void main ()
{

int n,m,ch;


printf("Enter first number : ");
scanf ("%d",&n);

printf("Enter second number  : ");
scanf ("%d",&m);

do{
printf ("1.Equality\n");
printf ("2.Less than\n");
printf ("3.Maximum\n");
printf ("4.Exit\n");
printf("Enter your choice\n");
scanf ("%d",&ch);
switch (ch)
{
case 1:
if(n==m)
printf ("%d and %d are equal\n",n,m);
else
printf ("%d and %d are Not equal\n",n,m);
break ;

case 2:
if(n<m)
printf("%d is less than %d \n",n,m);
else
printf("%d is greater than %d\n",n,m);
break;

case 3:
if(n>m)
printf("%d is Maximum\n", n);
else
printf("%d is Maximum\n ", m);
break ;


}

}


while(ch!=4);


}
