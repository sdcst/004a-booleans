## SDSS Computing Studies Python Assignment
### Assignment #004a Introduction to Boolean Variables (Total Marks 10)

Objectives:
* Differentiate boolean variables from int, float and str
* Identify Uses for Boolean type Variables
* Evaluate Boolean Expressions

Imagine you open up your phone settings.  There are a lot of different buttons or "toggles" that 
you might be see.  For example:
![toggle image](https://cdn.dribbble.com/users/6179/screenshots/726313/toggle-switches.jpg)

This is a great example of a Boolean variable.  A boolean stores only 2 possible values, unlike
a str, float or int that can store almost an infinite number of different possible values. There
are many different ways to think of these 2 states:

on or off \
yes or no \
1 or 0 \
Enabled or Disabled \
True or False \

Python uses the values **True** or **False** as the values that a boolean can store
```
#Example
hasKey = True
doorLocked = False
```
Note the absence of quotation marks around the values being stored into the variables
*hasKey* and *doorLocked*.  Also, the capitalization is important - the first character
must be upper case.

There are many different ways that you might see a Boolean used or how you might use them:
* To see if a setting has been enabled or disabled. This is sometimes called a toggle or flag
* To answer a simple Yes/No question and decide what to do next.  Many of you included something like this in your Peanut Butter Sandwich assignment.  If you have 2 pieces of bread, you can proceed with making the sandwich. If no, then you need to consider acquiring some bread
* To keep track of a single state that could be either a Yes or No
* To check a *conditional statement*

### Conditional Statements ###
A conditional statement is one that is evaluated as True or False. You can kind of think of it as a question.
There are several different conditional operators

Consider 2 variables or values: \
a == b    Checks to see if the 2 values are equal
a > b     Checks to see if a is greater than b
a < b     Checks to see if a is less than b
a >= b    Checks to see if a is greater than or equal to b
a <= b    Checks to see if a is less than or equal to b
a != b    Checks to see if a and b are not equal
These all work for both numerical values (int and float) as well as for strings

"in" is a special conditional operator that compares 2 strings.  It can be used to see if one string
can be found somewhere in the other string. These 2 strings are sometimes referred to as the
"needle" and the "haystack" \
"example: \
*needle* in *haystack*
"i" in "team" is evaluated as False
"fun" in "funeral" is evaluated as True




### XX Tasks

##### Task 1
(x points) 

