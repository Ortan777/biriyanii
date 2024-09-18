# biriyanii
#include <stdio.h>

int main() {
    // Declare variables to store the two numbers and their sum
    int num1, num2, sum;

    // Prompt the user for input
    printf("Enter first number: ");
    scanf("%d", &num1);
    
    printf("Enter second number: ");
    scanf("%d", &num2);

    // Calculate the sum
    sum = num1 + num2;

    // Display the result
    printf("The sum of %d and %d is %d\n", num1, num2, sum);

    return 0;
}
