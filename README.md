# A conversion from date to the factorial of the sum of all digits
This program get the user input as a date and  convert it to the sum of all the digits and then output the factorial of the sum

# Tools
Python 3.5

Google colab

# Installation:
Open google colab file in github repo then chose to open it on google colab (click on google colab logo in the midlle of the screen)

# How to use
How to use?

Input: Write any date in the following format dd/mm/yyyy

Then run the code by clicking on running button

Input: 01/01/0011

Output: 24

# Features
Calculate the factorial number
Detect invalid output

# code example

The following code check if there are any error in input format

try:

  valid_date = time.strptime(date, '%d/%m/%Y')
  
except ValueError:

  print('Invalid date!')
  
  
