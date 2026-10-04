# 5-
C언어 5주차 과제
#include <stdio.h>

int main()
{
    int year, leafyear;
    printf("Input year : ");
    scanf_s("%d", &year);

    if (year % 400 == 0)
    {
        printf("윤년입니다.");
    }
    else
    {
        if (year % 100 == 0)
        {
            printf("평년입니다.");
        }
        else
        {
            if (year % 4 == 0)
            {
                printf("윤년입니다.");
            }
            else
            {
                printf("평년입니다.");
            }
        }
    }

    return 0;
}
