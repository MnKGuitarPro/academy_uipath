# Exercise 004

## Practical Exercise

### Create a modular stoplight process that:

1. Has an input variable which has a value of either “red”, “green” or “yellow”.
2. Could take the value from the user with a multi choice dialogue (optional).
3. Has a separate logging workflow which writes what color the stoplight is and how long it will stay on in the Output Panel.
4. The default color in the logging workflow arguments should be “red”, to be on the safe side.
5. It will take in two arguments, color and duration.
6. Has a main workflow that will invoke the logging workflow with different arguments depending on the color, as follows: 

* Red - 50 seconds
* Yellow - 10 seconds
* Green - 80 seconds

## Solutions

Here you have two solutions:

1. `exercise004/Main.xaml` and `exercise004/Secondary.xaml` (my solution)
2. `exercise004/official_answer/Stoplights - main.xaml` and `exercise004/official_answer/log information.xaml` (are the official Academy's solutions)