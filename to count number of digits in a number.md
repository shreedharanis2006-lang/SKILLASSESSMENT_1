## Write a c program to count the number of digits in a number.
## PROGRAM
~~~
#include <stdio.h>

int main() {
    int num, count = 0;

    printf("Enter a number: ");
    scanf("%d", &num);

    if(num == 0)
        count = 1;

    while(num != 0) {
        num = num / 10;
        count++;
    }

    printf("Number of digits = %d", count);

    return 0;
}
~~~
## OUTPUT
<img width="833" height="190" alt="image" src="https://github.com/user-attachments/assets/26d0320c-b7df-4409-a0ec-bd4d1f693e88" />

## RESULT
The program has been executed successfully.
