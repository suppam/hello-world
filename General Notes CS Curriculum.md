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
