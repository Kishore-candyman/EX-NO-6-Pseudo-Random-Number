# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.

Seed the random number generator using the current time(i.e) rand(time(0));

Get the number of randon number to generate.

Pass the value for number of iterations and print the numbers.

End the program.

# PROGRAM:
```

#include <stdio.h>
#include <stdlib.h>
#include <time.h>


void printRandoms(int min, int max, int count) {
    printf("Random numbers between %d and %d: ", min, max);
  
    for (int i = 0; i < count; i++) {

        int rd_num = rand() % (max - min + 1) + min;

        printf("%d ", rd_num);
    }
}

int main() {
    int min = 3, max = 7, count = 10;
    printRandoms(min, max, count);
    return 0;
}

```
# OUTPUT:
<img width="1704" height="825" alt="image" src="https://github.com/user-attachments/assets/c60f525f-31d6-42d0-8bdc-d5185d14bb8d" />

# RESULT:
Thus, the C program for Pseudo Randon Number generation is executed successfully.
