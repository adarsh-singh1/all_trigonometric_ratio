#include <stdio.h>
#include <math.h>
int main()
{
    float angle,radian;
    printf("enter the value of angle");
    scanf("%f", &angle);
    radian=angle*(3.14159/180);
    printf("sin %0.1f = %f\n", angle, sin(radian));
    printf("cos %0.1f = %f\n", angle, cos(radian));
    printf("tan %0.1f = %f\n", angle, tan(radian));
    printf("cosec %0.1f = %f\n", angle, 1/sin(radian));
    printf("sec %0.1f = %f\n", angle, 1/cos(radian));
    printf("cot %0.1f = %f\n", angle, 1/tan(radian));

    return 0;
}
