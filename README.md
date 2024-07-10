# icreate-nitialize-and-access-pointer
#include<stdio.h>
#include<conio.h>
void main()
{

    int num1,num2,*ptr;
    printf("\n ENTER ANY NUMBER-");
    scanf("%d",&num1);
    ptr=&num1;
    printf("\n VALUE IN ADDRESS %u is %d",ptr,*ptr);

    printf("\n ENTER ANY NUMBER-");
    scanf("%d",&num2);
    ptr=&num2;
    printf("\n VALUE IN ADDRESS %u is %d",ptr,*ptr);
    getch();

}
