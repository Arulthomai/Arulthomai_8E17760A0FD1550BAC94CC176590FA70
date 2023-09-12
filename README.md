
#include <stdio.h>
 
unsigned long factorial(int n)
{
    
    if (n < 1) {
        return 1;
    }
    return n * factorial(n - 1);
}
 
int main()
{
    int n = 5;
    printf("The Factorial of %d is %lu", n, factorial(n));
 
    return 0;
}

