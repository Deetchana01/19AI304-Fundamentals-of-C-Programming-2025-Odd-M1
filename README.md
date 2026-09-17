# 19AI304-Fundamentals-of-C-Programming-2025-Odd-M1
# IAPR-1- Module 1 - FoC
## 1. Implementation of basic C programs using Literals,Consonants, Variables, Data types.
## 2. Implementation of different categories of operators.
# Ex.No:1
  Build a C program to demonstrate the usage of different types of literals: integer, float, character, and string.   
# Aim:
To build a C program that prints integer, float,character, and string literals on the console using the printf() function.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Inside the main() function, use printf() to display each literal along with its size in bytes using sizeof() :
  
   3.1 Integer literal (e.g., 10) using `%d`
   
   3.2 Float literal (e.g., 3.14) using `%f`
   
   3.3 Character literal (e.g., 'A') using `%c`
   
   3.4 String literal (e.g., "Hello C") using `%s`
   
### Step 4: 
   Stop
# Program:
~~~
#include <stdio.h>

int main()
{
    printf("Integer literal: %d\n", 10);
    printf("Float literal: %f\n", 3.14);
    printf("Character literal: %c\n", 'A');
    printf("String literal: %s\n", "Hello C");

    return 0;
}
~~~
# Output:
<img width="1446" height="432" alt="image" src="https://github.com/user-attachments/assets/9d56ac5d-be3c-4141-8af0-d72fa098f5c4" />

# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:2
  Build a C program to display the value of a macro constant and a constant variable.
# Aim:
  To build a C program that demonstrates the use of macro constants and constant variables.
# Algorithm:
### Step 1:
  Start  
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Define a macro constant `PI` with value `3.14159` using `#define`.
### Step 4: 
   Inside `main()`:
   
   4.1 Declare a constant integer variable `DAYS`
   
   4.2 Initialize it with the value `7`
   
### Step 5:  
  Use `printf()` to display the values of `PI` and `DAYS`.     
### Step 6:  
  Stop
# Program:
~~~
#include <stdio.h>

#define PI 3.14159

int main()
{
    const int DAYS = 7;

    printf("Value of PI = %f\n", PI);
    printf("Value of DAYS = %d\n", DAYS);

    return 0;
}
~~~
# Output:
<img width="1456" height="497" alt="image" src="https://github.com/user-attachments/assets/c3d033ff-1322-4fcb-ac9f-820cace14a15" />

# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:3
  Build a C program to demonstrate the use of different data types such as int, float, double, and char, and display their values using printf().
# Aim:
  To build a C program that declares variables of various data types—integer, float, double, and character—initializes them, and prints their values on the screen.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Inside main(), declare and initialize variables of types int, float, double, and char.
### Step 4: 
   Display their values using printf().
### Step 5:    
   Stop
# Program:
~~~
#include <stdio.h>

int main()
{
    int a = 10;
    float b = 3.14;
    double c = 25.6789;
    char d = 'A';

    printf("Integer value = %d\n", a);
    printf("Float value = %f\n", b);
    printf("Double value = %lf\n", c);
    printf("Character value = %c\n", d);

    return 0;
}
~~~
# Output:
<img width="1453" height="516" alt="image" src="https://github.com/user-attachments/assets/ce1b9546-39db-4d3a-b0e9-645b85bd093e" />

# Result: 

# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:4
  Build a C program to perform arithmetic and bitwise operations on two integers entered by the user. The program should display: Arithmetic operations: addition, subtraction, multiplication, division, and remainder. Bitwise operations: AND, OR, XOR, left shift, right shift, and NOT.
# Aim:
  To build a C program that takes two integers as input and demonstrates the arithmetic and bitwise operations, displaying the results of each operation.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Declare two integer variables a and b.
### Step 4: 
   Prompt the user to enter two integers and read the input using scanf().
### Step 5:    
   Perform arithmetic operations on a and b:
   #### Sum (a + b)
   #### Difference (a - b)
   #### Product (a * b)
   #### Quotient (a / b)
   #### Remainder (a % b)
### Step 6: 
  Perform bitwise operations on a and b:
  #### AND (a &amp; b)
  #### OR (a | b)
  #### XOR (a ^ b)
  #### Left shift (a << b)
  #### Right shift (a >> b)
  #### Bitwise NOT of a (~a) and b (~b)
### Step 7:   
  Display the results of all operations using printf().
### Step 8:   
  Stop
# Program:
~~~
#include <stdio.h>

int main()
{
    int a, b;

    scanf("%d %d", &a, &b);

    printf("Addition = %d\n", a + b);
    printf("Subtraction = %d\n", a - b);
    printf("Multiplication = %d\n", a * b);
    printf("Division = %d\n", a / b);
    printf("Remainder = %d\n", a % b);

    printf("Bitwise AND = %d\n", a & b);
    printf("Bitwise OR = %d\n", a | b);
    printf("Bitwise XOR = %d\n", a ^ b);
    printf("Left Shift = %d\n", a << b);
    printf("Right Shift = %d\n", a >> b);
    printf("NOT of a = %d\n", ~a);
    printf("NOT of b = %d\n", ~b);

    return 0;
}
~~~
# Output:
<img width="1447" height="727" alt="image" src="https://github.com/user-attachments/assets/192ef2a2-7d2d-4db3-a702-5f8b86156bb9" />

# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.


# 19AI304-Fundamentals-of-C-Programming-2025-Odd
# IAPR-1- Module 1 - FoC
# Ex.No:5
  Develop a C program to check whether a given character is a vowel, consonant, digit, or special symbol using the ternary operator.
# Aim:
  To develop and implement a C program that classifies a character as a vowel, consonant, digit, or special symbol using the ternary operator.
# Algorithm:
### Step 1:
  Start
### Step 2: 
  Include the standard input-output library: #include<stdio.h>.
### Step 3: 
  Input a character ch from the user.
### Step 4: 
   Check if ch is a digit ('0' to '9').
   
   If true → Print "Digit" → Go to Step 8.
   
   If false → Go to Step 5.
   
### Step 5:    
   Check if ch is an alphabet letter ('A' - 'Z' or 'a' – 'z').
   
   If true → Go to Step 6.
   
   If false → Go to Step 7.
   
### Step 6: 
   Check if ch is a vowel (a, e, i, o, u or A, E, I, O, U).
   
   If true → Print "Vowel" → Go to Step 8.
   
   If false → Print "Consonant" → Go to Step 8.
   
### Step 7:   
   Print "Special Symbol".
### Step 8:   
  Stop
# Program:
~~~
#include <stdio.h>

int main()
{
    char ch;

    scanf("%c", &ch);

    (ch >= '0' && ch <= '9') ? printf("Digit") :
    ((ch >= 'A' && ch <= 'Z') || (ch >= 'a' && ch <= 'z')) ?
    (((ch == 'A') || (ch == 'E') || (ch == 'I') || (ch == 'O') || (ch == 'U') ||
      (ch == 'a') || (ch == 'e') || (ch == 'i') || (ch == 'o') || (ch == 'u')) ?
      printf("Vowel") : printf("Consonant"))
    : printf("Special Symbol");

    return 0;
}
~~~
# Output:
<img width="1455" height="625" alt="image" src="https://github.com/user-attachments/assets/13e6f57b-c5e8-4094-9410-017a4f30c052" />

# Result: 
Thus, the program was implemented and executed successfully, and the required output was obtained.
