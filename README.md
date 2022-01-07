# BigIntegerLibraryInCpp
## Problem Statement: Create a big integer library, similar to the one available in Java. The library should provide functionalities to store arbitrarily large integers and perform basic math operations.
## Operations:
### 1. Addition, subtraction, multiplication.
### Eg Input: `99893271223 * 9203232392 + 32789123 - 4874223 = 919340989462382970316`
#### Negative numbers won’t be present in the intermediate or final output (Eg: No need to consider cases like 2-3 )
### 2. Exponentiation.
#### Base will be a bigint and exponent will be < 2^63
### 3. GCD of two numbers.
### 4. Factorial.
### Note: For all the operations, input will be such that the number of digits in output won’t exceed 3000 digits.
### Evaluation parameters: Accuracy of operations and performance
### First line will contain the type of operation:
### 1 for exponentiation
### 2 for GCD
### 3 for factorial
### 4 for calculator

### The following line will contain one string in case of calculator and factorial, and two space separated strings in case of GCD and exponentiation.
### Eg:
### input 1:
### 1
### 2 34
### input 2:
### 2 
### 9 15
### input 3:
### 3
### 24
### input 4:
### 4
### 1+2+3*5-2
