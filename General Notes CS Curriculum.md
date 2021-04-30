# PRACTICAL PROGRAMMING
# Chapter 3
PRECONDITIONS = assumptions about your code
for example, would need to enter particular value or works under certain conditions

RETURN NONE = acceptable situation, purpose of returning none is to omit a return value

RECIPES OF A FUNCTION = 
1 - EXAMPLES - Figure out arguements you want to include and what to return
2 - TYPE CONTRACT - the types of information to be handled and types of values, ie. int, float, string
3 - HEADER - a meaningful header can mean its easier to read ie. Def days_difference(day_start, day desired):
4 - DESCRIPTION - use the docstring """ to start and explain the purpose. when using help this will appear in the help call for function
5 - BODY - the actual function details
6 - TEST - use some examples and what the outcome would be, check and revise

Notes about calling functions---
the function definition introduces a new variable that refers to a function object
the parameter is the item int eh parentheses that is being used as input to the function - appears between the function header
the variabels within the function are local variables only used in teh function and not sent out of it, purpose is to calculate intermediate values before return
function calls tell python to execute a function
the function argument is the expression that appears between the parentheses of the function call. upon the function being completed, the return value is assigned to the parameter

# Chapter 4

STRINGS
the empty string is a valid string with no characters

two strings can be added by a "+" which is known as a concatenation

strings can use either single or doubel quotations, but in using a quote within a string, it must be single for the quote and double for the string value
strings of differing types can be added together if they are the same type. they must be converted, ie. string(3) to make "3" which can be added to "3 times" (str(3) + " times")
you can convert a string represented number ('0') into an int or float as it is similar and understood

COMMON FUNCTIONS
len()
repetition of a string with * 
less than or equal to 0 repetitions will give empty string
operations can be done on strings as if they were variables

print ("string") must include the quotes
print with the escape sequence will not print the sequence but rather the result of the tab or new line
print will print out on the screen the values in the quotes and anything between the comma seperations, as long as it is sensible
ie. print("one", 2, 2*5, "one hundred")
one 2 10 one hundred

you can format the print statement with varying parameters
- ending of line
- separators and values

INPUTS
use the function input() to gather keyboard strokes into the program
prompted --- input("what number do you want to enter")

# Chapter 5

CONTROL FLOW = Boolean True/False
