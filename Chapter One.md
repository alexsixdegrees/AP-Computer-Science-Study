#Chapter One - Introductory Java#

## Package and Classes ##

Related class are grouped into packages.
Source files - java files comprise of your program

Main method - A java program must have at least one class.

Compiler - convert code into machine-readable form - bytecode

Note:
	All Java methods must be contained in a class, and all program statements must be placed inside a method. 
	The class contains the main method does not contain many additional methods


## Types and Identifiers ##

### Identifiers ###
	- a name for variable, parameter, constant, class…
	- Case-sensitive
	- Be concise and self-documenting

### Built-in type ###
	*Every identifier has a type associated with it
		○ Int: an integer (2,-37)
			§ Integers are bounded, otherwise overflow error
		○ Boolean: just two values, true or false
		○ Double: floating-point number (2.718, 9.1)
	Example Code:
	```java
		○ Int x;
		○ Double y,z
		○ Boolean found;
		○ Int count = 1;     //count initialized to 1
		○ Double p = 2.3, q = 4.1;  
	```
	- One type can be cast to another type
		○ exapmle
			§ int total, n;
			§ Double average;
			§ Average = (double)total/n;   //total cast
		○ Int can automatically casts to a double
	- Round the number
		○ Round a positive number by simply truncating the number 
			§ Double cost = 10.92;
			§ Int numDollars = (int) cost;   // sets numDollars to 11
		○ Round a positive number
			§ Int numDollars = (int) (cost + 0.5)
