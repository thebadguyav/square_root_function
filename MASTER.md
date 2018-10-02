#include<stdio.h>
#include<math.h> //header file for 'sqrt()' function
int main()
{
    int a; //variable whose square root is to be calculated
    float ans=0; //variable for storing the answer value
    printf("Enter the number whose square root is to be calculated:");
    scanf("%d",&a);
    ans=sqrt(a);
    printf("Square root of the entered number is: %f",ans);
return 0;
}
