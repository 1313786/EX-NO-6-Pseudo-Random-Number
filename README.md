# EX-NO-6-Pseudo-Random-Number
## NAME: IRFAN KHAN.N
## REG NO: 212224230097

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
int main()
{ int n;
printf("Enter how many random numbers to generate: ");
scanf("%d", Cn);
srand(time(0)); // Seed the random number generator
printf("Generated Random Numbers:\n");
for (int i = 0; i < n; i++) {
printf("%d ", rand());
}
printf("\n");
return 0;
}
```
# OUTPUT:
<img width="707" height="293" alt="image" src="https://github.com/user-attachments/assets/f134707a-b1b7-4eab-b70d-1a9ae990fdbb" />


# RESULT:

The program executed successfully.
