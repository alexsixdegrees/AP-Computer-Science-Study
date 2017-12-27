# Chapter One - Introductory Java

## Package and Classes

Related class are grouped into packages.  
Source files - java files comprise of your program

Main method - A java program must have at least one class.

Compiler - convert code into machine-readable form - bytecode

Note:  
    All Java methods must be contained in a class, and all program statements must be placed inside a method.   
    The class contains the main method does not contain many additional methods

## Types and Identifiers

### Identifiers

* a name for variable, parameter, constant, class…
  Case-sensitive
* Be concise and self-documenting

### Built-in type

* Every identifier has a type associated with it
  * Int: an integer \(2,-37\)
    * Integers are bounded, otherwise overflow error
  * Boolean: just two values, true or false
  * Double: floating-point number \(2.718, 9.1\)
  * Example Code:
    ```java
    Int x;
    Double y,z
    Boolean found;
    Int count = 1;     //count initialized to 1
    Double p = 2.3, q = 4.1;
    ```

### Casting

* example
  ```java
  int total, n;
  Double average;
  Average = (double)total/n;   //total cast
  ```
* Int can automatically cast to a double
* Round the number
  * Round a positive number by simply truncating the number 
    ```java
    Double cost = 10.92;
    Int numDollars = (int) cost;   // sets numDollars to 11
    Int numDollars = (int) (cost + 0.5)   // Round a positive number
    ```

## Operators

### Arithmetic Operators

| operator | meaning |
| --- | --- |
| + | addition |
| - | substraction |
| \* | mutli |
| / | division |
| % | mod |

### Relational operators

| operator | meaning |
| --- | --- |
| == | equal to |
| != | not equal |
| &gt; | greater than |
| &lt; | smaller than |
| &gt;= | greater or equal |
| &lt;= | less or equal |

### logical operators

|  |  | operator | meaning |
| :--- | :--- | :--- | :--- |
|  |  | ! | not |
|  |  | && | and |
|  |  |  | or |

### assignment operators

| operator | meaning |
| --- | --- |
| += | x = x + 4 |
| \*= | x = 4x |
| ... | ... |

### increment and decrement operators

| operator | meaning |
| --- | --- |
| ++ | x is incremented by one |
| -- | x is dncremented by one |
| ... | ... |

## Input Output

int x = 23;  
system.out.println\("Hot"\);  
system.out.println\(x\);

### Escape Sequence

| operator | meaning |
| --- | --- |
| \n | newline |
| \" | double quote |
| \\ | backslash |

## Control Structure

### if statement

if \(boolean expression\)  
{  
    statements  
}  
else  
{  
    statements  
}

### extended if statement

if \(\)  
    statement;  
else if \(\)  
    statement;  
else if \(\)  
    statement;  
else \(\)  
    statement;

### iteration

for \(initialization; termination condition; update statement\)  
{  
    statements;   //body of loop  
}

```java
//output 1,2,3,4
for (i = 1; i < 5, i ++)
    System.out.println(i);
```

### for each loop

for \(some type of collection of elements\)  
{  
    statements  
}

### While Loop

while \(Boolean test\)  
{  
    statements    //loop body  
}

## Errors and exceptions

Different types of exceptions:

| exceptions | meaning |
| --- | --- |
| arithmeticException | divide an integer by zero |
| arrayindexoutofbonds | a negative array index |



