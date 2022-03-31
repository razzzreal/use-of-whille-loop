#include<stdio.h> /*some code execute many times depends on how many times you want to execute*/
void main()
{
    int a=10;
    while(a<20)
    {
        printf("a value is:%d\n",a);
        a++;
    }
}
