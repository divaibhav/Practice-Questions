### While Loop Practice

1. Write a program to print all the digits of a given number.
    ```
   Sample 
   input - 1234
   output - 
   4
   3 
   2
   1
   Explanation
    - get remainder of input to get last digit - input % 10 will give 4 as remainder
    - now last was extracted, discard the last digit from the input - input = input / 10 will dicard the last digit 4
    - repeat the process till input become zero.
   
   digit = input % 10;
   input = input / 10;
   print the digit
   
   ```
2. Write a program to print sum of all the digits of the given number. Accept number as input from user.
   ```
   Sample run
   input - 12345;
   output - 15
   
   Explanation
      - get digits from number one by one - digit = input % 10;
      - add digit to sum one by one - sum = sum + digit;
      - now discard the last digit - input = input / 10;
      - repeat the process till input become zero  
   sum = 0;
   iteration 1
   input = 12345;
   digit = input % 10; // 12345 % 10 -> 5 
   sum = sum + digit; // 0 + 5 -> 5
   input = input / 10; // 12345 / 10 -> 1234 
   
   iteration 2
   input = 1234; // now the input become, 1234, due to first iteration
   digit = input % 10; // 1234 % 10 -> 4 
   sum = sum + digit; // 5 + 4 -> 9
   input = input / 10; // 1234 / 10 -> 123 
   
   iteration 3
   input = 123; // now the input become, 123, due to last iteration
   digit = input % 10; // 123 % 10 -> 3 
   sum = sum + digit; // 9 + 3 -> 12
   input = input / 10; // 123 / 10 -> 12
   
   iteration 4
   input = 12; // now the input become, 12, due to last iteration
   digit = input % 10; // 12 % 10 -> 2 
   sum = sum + digit; // 12 + 2 -> 14
   input = input / 10; // 12 / 10 -> 1
   
   iteration 5
   input = 1; // now the input become, 1, due to last iteration
   digit = input % 10; // 1 % 10 -> 1 
   sum = sum + digit; // 14 + 1 -> 15
   input = input / 10; // 1 / 10 -> 0
   
    
   ```
3. Write a program that calculates the sum of all even numbers from 1 to a given number N and print the sum. Accept the
   number N from user.

4. Implement a program that computes the factorial of a given number N using a loop and print the factorial. Accept the
   number N from user.
   ```
      Sample
      N = 5
      output = 120
      Explaination
      5 factorial => 5 * 4 * 3 * 2 * 1 => 120
   ```

5. Write a program that checks if a given integer inputNumber is prime number, if yes print inputNumber is prime number
   otherwise print inputNumber is not a prime number. Accept the inputNumber from user.

6. Write a program to print the first N numbers in the Fibonacci sequence. Accept the number N from user.
   Constrain N >= 0 and N <= 20. (keep value of N small. )
   ```
   Sample 
   N = 10
   output = 0, 1, 1, 2, 3, 5, 8, 13, 21,34
   Explanation
   first trem is 0 (known)
   second trem is 1 (known)
   third term = 0 + 1 = 1
   fourth term = 1 + 1 = 2
   so on.... next term is sum of last two terms
   
   
   What is Fibonacci Series?
   
   The Fibonacci series is the sequence of numbers (also called Fibonacci numbers),
   where every number is the sum of the preceding two numbers, such that the first two terms are '0' and '1'.
   In some older versions of the series, the term '0' might be omitted. 
   
   A Fibonacci series can thus be given as, 0, 1, 1, 2, 3, 5, 8, 13, 21, 34, . . . 
   It can thus be observed that every term can be calculated by adding the two terms before it.

   Given the first term, F0 and second term, F1 as '0' and '1' respectively,
   the third term here can be given as, 
   F0 = 0, F1 = 1,
   F2 = F0 + F1
   F2 = 0 + 1 = 1

   Similarly,

   F3 = 1 + 1 = 2
   F4 = 2 + 1 = 3
   F5 = 2 + 3 = 5
   F6 = 3 + 5 = 8
   F7 = 5 + 8 = 13
   and so on
   
   ```
   [Reference - cuemath.com](https://www.cuemath.com/numbers/fibonacci-series/)
7. Write a program to print the sum of first N numbers in the Fibonacci sequence. Accept the number N from user.
   Constrain N >= 0 and N <= 20. (keep value of N small. )
   ```
   N = 8
   output = 33
   Explaination 
    0, 1, 1, 2, 3, 5, 8, 13 fibbonacci series for N = 8
   
   sum = 0 + 1 + 1 + 2 + 3 + 5 + 8 + 13 = 33 
   ```

8. Write a program to check if a given three-digit number N is an Armstrong number if yes, print Armstrong number
   otherwise
   print Not an Armstrong number. Accept the three-digit number N from user.
   ```
   Sample 
   Input N = 371
   output = Armstrong number
   ```
   Explanation :

   An Armstrong number of three digits is an integer such that the sum of the cubes of its digits is equal to the number
   itself.

   3<sup>3</sup> + 7<sup>3</sup> + 1<sup>3</sup>

   27 + 343 + 1 => 371
9. Generate the multiplication table for a given number N up to 10. Accept the number N from user.
10. Write a program to calculate number<sup>power</sup> (number raised to the power) using a loop. Accept the number and
    power from user.

    Sample

    number = 2, power = 5

    output = 32

    Explanation

    2<sup>5</sup> = 32
   
