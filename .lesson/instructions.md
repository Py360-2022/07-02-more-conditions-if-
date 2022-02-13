# Instructions  

  ** exercises using if  **

_ Note because the results are random Before you test your functions, choose 1 test case, calculate the expected results and put your test cases & results in comments (before the functions).  _ 

  ## Problem 1 `magic_8_ball`
  1. Write a function `magic_8_ball` that takes no parameters. It will generate a random number between 1 and 8, and then returns a different string for each one (e.g., if the random number is 1, the function returns 'today is your lucky day')
   Choose 8  from here https://en.wikipedia.org/wiki/Magic_8-ball#Possible_answers 

  2. Now write the rest of the program that will:

    1. Ask for the user’s name.
    2. Call `magic_8_ball`
    3. Display a personalised message that includes the user’s name and the magic-8-ball message

## Problem 2 `can_drive`
  1. Write a function `can_drive` the function should take one parameter, age.  Think about how you would structure the below logic, draw a flowchart, it's easier (do it without using a logical `and` or `or`)
      ```
    If the age is under 16, it should return:
      “You’re too young to drive!”
    If the age is between 16 and 21 it should return:
      “You’re old enough to drive, but not old enough to rent a car”
    If the age is over 21 it should return:
      “You’re old enough to both drive and rent a car!”
      ```
  
  2. Now write the rest of the program that will:

    1. Ask the user for their age
    2. call the function
    3. Displlay the results of the function call