### Conditional Statement

1. Write a program that accept an integer form user and print positive, if the integer is positive.
2. Write a program that accept two numbers from the user and print equals if the numbers are equal.
3. Write a program to accept three numbers from user and print equals if the numbers are equal.
4. Write a program to accept three numbers from user and print all are divisible by 9, if all three numbers are divisible by 9.
5. Write a program to accept an integer from user and print positive, if the number is positive. Otherwise, print negative. Considering number can never be equal to zero.
6. Write a program to accept an integer from user and print even if the number is even, Otherwise print odd.
7. Write a program to accept an integer from user. If the number is even make it odd and print. If the number is odd make it even and print.
8. Write a program to accept two numbers from user, if the both the numbers are positive, get the remainder of the division by 5 for both the numbers.
   If remainder of both the division are equal print numbers are equal, otherwise number are not equal. If one or both the numbers are negative, print calculation not possible.
9. Write a program that print the current balance of the account, ask the user to enter the withdrawal amount.
    - if withdrawal amount is less than current balance,
      - deduct the withdrawal amount form the current balance, if current balance after deduction is less than 500 INR, deduct penalty of 50 INR and print current balance and penalty.
      - otherwise, print the current balance.
    - If withdrawal amount is greater than current balance, print insufficient funds.
    ```
   Sample run 1
   Current balance = 5000
   Enter withdrawal amount - 4600
   Current balance = 350
   Penalty = 50
   
   Sample run 2
   Current balance = 5000
   Enter withdrawal amount - 4500
   Current balance = 500
   
   Current balance = 5000
   Enter withdrawal amount - 5600
   insufficient funds
   ```
10. **Pick the odd one out** - Write a program to accept four numbers from user and print the odd one among them.
    - Number can be odd among others in following scenario:
      - if three numbers are equal, then the different one is odd one among them.
      - if three number are even, then the different one is odd one among them.
      - if three number are odd, then the different one is odd one among them.
    - if all are different, even or odd, then print no number is odd one among them.
11. Write a program to accept the annual income from the user and calculate tax based of the below conditions:
    - In each case provide standard deduction of 50,000 INR, calculate taxable income by subtracting 50,000 form annual income.
      - if the taxable income is:
          - less than equal to 3,00,000 INR tax rate will be 0%.
          - greater than 3,00,000 INR and less than or equal to 5,00,000 INR tax rate will be 5%.
          - greater than 5,00,000 INR and less than or equal to 10,00,000 INR tax rate will be 15%.
          - greater than 10,00,000 INR and less than or equal to 15,00,000 INR tax rate will be 20%.
          - greater than 15,00,000 INR and less than or equal to 25,00,000 INR tax rate will be 25%.
          - greater than 25,00,000 INR tax rate will be 30%.
    - On the basis of the condition calculate tax amount and print.

12. Write a program to accept birth year of user in YYYY format (like 1983) and print the chinese zodiac of the user.
    - Chinese zodiac is represented by an animal sign as follows:
      - 0: monkey
      - 1: rooster
      - 2: dog
      - 3: pig
      - 4: rat
      - 5: ox
      - 6: tiger
      - 7: rabbit
      - 8: dragon
      - 9: snake
      - 10: horse
      - 11: sheep
    - To get the corresponding value modulo-division year by 12