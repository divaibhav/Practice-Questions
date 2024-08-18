### Practice-Problem-Arithmetic-Input-Output

1. Write a program to display a greeting message `Good Morning, Welcome to Programming` on the console.
2. Write a program to accept `int side` of a Square from user. Calculate `int area` and `int perimeter` of square. Print
   the `area` and `perimeter` on the console.
    ```
        Formula to calculate area of square -> side * side
        Formula to calculate area of square -> 4 * side
    ```
3. Write a program to accept `int length` and `int breadth` of rectangle from user. Calculate `int area` and
   `int perimeter` of rectangle. Print the `area` and `perimeter` on the console.
    ```
        Formula to calculate area of square -> length * breadth
        Formula to calculate area of square -> 2 * (length + breadth)
    ```
4. Write a program that converts inches to centimeters. For example, if the user enters 16.9 for a `length` in inches,
   the output would be 42.926 cm. (One inch equals 2.54 centimeters). Select appropriate datatype to hold `length` in
   inches and `result` in centimeters. Accept `length` from user. And display the output as
   ```16.9 inches = 42.926 centimeters```
    ```
    Sample Run:
    input
    Enter length in inches: 16.9
    output
    16.9 inches = 42.926 centimeters.
    ```
5. Write a program that reads in the radius and length of a cylinder and computes the area and volume using the
   following formulas:
    ```
        area = radius * radius * π
        volume = area * length

        value of π (PI) is  3.14
    ```
    ```
        Sample Run
        INPUT
        Enter the radius of a cylinder: 5.5
        Enter the length of a cylinder: 12
        
        OUTPUT
        The area is 95.0331
        The volume is 1140.4
    ```
6. Write a program that reads a Celsius degree in a double value from the console, then converts it to Fahrenheit and
   displays the result. The formula for the conversion is as follows:
    ```
        fahrenheit = (9 / 5) * celsius + 32
        Hint: In Programming, 9 / 5 is 1, but 9.0 / 5 is 1.8.
    ```
    ```
    Sample Run
    Input
    Enter a degree in Celsius: 43
    Output
    43 Celsius is 109.4 Fahrenheit
    ```
7. Average acceleration is defined as the change of velocity divided by the time taken to make the change, as shown in
   the following formula:
    ```
        a = (v1 - v0) / t
    ```

   Write a program that prompts the user to enter the starting velocity v0 in meters/second, the ending velocity v1 in
   meters/second, and the time span t in seconds, and displays the average acceleration.

    ```
    Sample Run
    Input
    Enter v0 : 5.5
    Enter v1 : 50.9
    Enter t  : 4.5

    Output
    The average acceleration is 10.0889
    ```
8. If you know the balance and the annual percentage interest rate, you can compute the interest on the next monthly
   payment using the following formula:

   > interest = balance x (annualInterestRate/1200)

   Write a program that reads the balance and the annual percentage interest rate and displays the interest for the next
   month.

9. Ravi and Shyam were playing a game. In the first turn of the game, Ravi will give an integer dividend and an integer
   divisor to Shyam. Then Shyam has to tell him the remainder of the division. In the second turn, Shyam will repeat the
   procedure.
   To help them, please write a program that accepts Dividend, and Divisor from the user and print the remainder on the
   console.

   ![hint](./resources/q8.jpg)

10. Write a program that prompts the user to enter the distance to drive, the fuel efficiency of the car in kilometer
    per liter, and the price per liter, and displays the cost of the trip.
    ***Please think of the formula to do calculation.***

    ```
    Sample Run
    Input
        Enter the driving distance: 900.5
        Enter kilometer per liter: 18.5
        Enter price per liter: 106.55
    Output
        The cost of driving is 5186.3932
    ```
