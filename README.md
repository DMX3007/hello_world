# hello_world
just another repository

#include <stdio.h>
#include <inttypes.h>

int main(int argc, char* argv[])
{
    printf("Please Enter your number:");
    int num;

    scanf("%d",&num);
    int biggerNum = num + 1;
    int lowerNum = num - 1;
    printf("Next number after %d is %d\n",num,biggerNum);
    printf("The previous number of %d is %d",num,lowerNum);
    return 0;
}
