#include <stdio.h>

int main() {
    int a, b, temp;

    // Input two numbers
    printf("Enter two numbers: ");
    scanf("%d %d", &a, &b);

    // Display numbers before swap
    printf("Before swapping: a = %d, b = %d\n", a, b);

    // Swapping using a temporary variable
    temp = a;
    a = b;
    b = temp;

    // Display numbers after swap
    printf("After swapping: a = %d, b = %d\n", a, b);

    return 0;
}
