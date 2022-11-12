//# character-check.c//
#include<stdio.h>
int main()
{
    char ch;
    printf("enter any character\n");
    scanf("%c",&ch);
    if(ch>='0'&& ch<=9)
    {
        printf("Entered character is digit.");
    }
    else
    {
        if(ch>='A'&& ch<='Z')
        {
            printf("Entered character is capital letter.");
        }
        else
        {
            if(ch>='a'&&ch<='z')
            {
                printf("Entered character is small letter.");
            }
            else
            {
                printf("Entered character is special character.");
            }
        }
    }
return 0;
}
