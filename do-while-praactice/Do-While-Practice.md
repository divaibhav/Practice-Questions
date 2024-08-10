### Do - While - Practice

1. Write a program to print `Hello World` on console, and ask user,
   `Do you want to continue? Press 1 to continue, Press 0 to exit`. Accept user choice.
    - ```
     Sample:
        Hello World
        Do you want to continue? Press 1 to continue, Press 0 to exit
     input = 1
        Hello World
        Do you want to continue? Press 1 to continue, Press 0 to exit
     input = 0
     
     Explanation:
        Output is printed on screen, not get the user input, based on user input 1, we will continue to print again. When user input is 0, we stops repeating.
     ```
2. Write a program print following menu to user:
    - ```
     Main Menu:
     Press 1 for Addition,
     Press 2 for Subtraction,
     Press 3 for Multiplication,
     Press 4 fot Division,
     Press 0 to exit
     ```
    - Accept user choice and based on choice perform operation by printing operation name and repeat until user enters
      0.
    - ```
     Ouptut
     Main Menu:
     Press 1 for Addition,
     Press 2 for Subtraction,
     Press 3 for Multiplication,
     Press 4 fot Division,
     Press 0 to exit
     
     input : 3
     
     Output
     Multiplication
     Main Menu:
     Press 1 for Addition,
     Press 2 for Subtraction,
     Press 3 for Multiplication,
     Press 4 fot Division,
     Press 0 to exit
     
     input = 1
     
     Output
     Addition
     Main Menu:
     Press 1 for Addition,
     Press 2 for Subtraction,
     Press 3 for Multiplication,
     Press 4 fot Division,
     Press 0 to exit
     
     input = 0;
     
     Explanation
     Frist print the menu and wiat for user choice, Now user entered 3, so print multiplication and again print menu.
     Now user entered 1, then print Addtion and again print menu
     Now user entered 0, exit do while loop
     ```
3. Write a program to accept number from user, until user press 0 to exit. Print the count of all the entered number
   exclude 0.
    - ```Sample
      output : Enter an integer number, Press 0 to exit
      input : 435
      output : Enter an integer number, Press 0 to exit
      input : 896
      output : Enter an integer number, Press 0 to exit
      input : 4
      output : Enter an integer number, Press 0 to exit
      input : 777
      output : Enter an integer number, Press 0 to exit
      input : 789
      output : Enter an integer number, Press 0 to exit
      input : 0

      count = 5

      Explanation:
      Total 5 numbers user entered before 0 to stop, So the count is 5 excluding 0.  
      
      ```
4. Write a program to accept number from user, until user press 0 to exit. Print the average of all the entered number.
    - ```
     Sample
     output : Enter an integer number, Press 0 to exit
     input : 10
     output : Enter an integer number, Press 0 to exit
     input : 20
     output : Enter an integer number, Press 0 to exit
     input : 30
     output : Enter an integer number, Press 0 to exit
     input : 40
     output : Enter an integer number, Press 0 to exit
     input : 50
     output : Enter an integer number, Press 0 to exit
     input : 0
     Average = 30
     Explanation:
     At First iteration user entered 10, so we have to repeat,
     At Second iteration user entered 20, so we have to repeat,
     At Third repeatation user entered 30, so we have to repeat,
     At Fourth repeatation user entered 40, so we have to repeat,
     At Fifth repeatation user entered 50, so we have to repeat,
     At Sixth repeatation user entered 0, so we have to stop and exit the loop.
     So there are total 5 times user values before stop, so average of entered number = 30.
    ```
5. Write a program to accept number from user, until user press 0 to exit. Print the count of all the entered even
   number exclude 0.
    - ```Sample
      output : Enter an integer number, Press 0 to exit
      input : 435
      output : Enter an integer number, Press 0 to exit
      input : 896
      output : Enter an integer number, Press 0 to exit
      input : 4
      output : Enter an integer number, Press 0 to exit
      input : 777
      output : Enter an integer number, Press 0 to exit
      input : 789
      output : Enter an integer number, Press 0 to exit
      input : 0
      count = 2
      Explanation:
      Total 5 numbers user entered before 0 to stop, So the count of even number is 2 excluding 0.
     ```