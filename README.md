# kclkvl.p
kclkvl calculation in c program 
#include <stdio.h>

int main() {
    float i1, i2, i3, i4, total_in, total_out;

    printf("Enter current I1 entering: ");
    scanf("%f", &i1);

    printf("Enter current I2 entering: ");
    scanf("%f", &i2);

    printf("Enter current I3 leaving: ");
    scanf("%f", &i3);

    total_in = i1 + i2;
    i4 = total_in - i3;

    printf("Current I4 leaving = %.2f A\n", i4);

    total_out = i3 + i4;

    printf("Total entering current = %.2f A\n", total_in);
    printf("Total leaving current = %.2f A\n", total_out);

    return 0;
}#include <stdio.h>

int main() {
    float i1, i2, i3, i4, total_in, total_out;

    printf("Enter current I1 entering: ");
    scanf("%f", &i1);

    printf("Enter current I2 entering: ");
    scanf("%f", &i2);

    printf("Enter current I3 leaving: ");
    scanf("%f", &i3);

    total_in = i1 + i2;
    i4 = total_in - i3;

    printf("Current I4 leaving = %.2f A\n", i4);

    total_out = i3 + i4;

    printf("Total entering current = %.2f A\n", total_in);
    printf("Total leaving current = %.2f A\n", total_out);

    return 0;
}