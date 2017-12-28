# Chapter Two - Classes and Objects

## Objects

Object is a thing that is being created or manipulated by the program.

Object is characterized by state and behaviour.

In Java, a variable that represents an object is called an object reference.

## Classes

Class is a software blueprint for implementing objects of a given type.

## Public, Private, and Static

* public: the class is usable by all client programs
* private: private methods and variables can be accessed only by methods of that class
* static: memory allocation happens once.

## Methods

### Headers

| public | void | withdraw | \(string password, double amount\) |
| --- | --- | --- | --- |
| access specifier | return type | method name | parameter list |

### Instance Methods

Instance methods, constructors, accessors, and mutators, all operate on individual objects of a class.

#### Constructors

1. Default constructor
   1. has no return value and only initializing class objects.
   2. example:
      \`\`\`java
      /\*\* Default constructors.
   3. Constructs an initial value for the hero. \*/
      public NewHero\(\)
      {
        attack = 50.0;
        hp = 100.0;
      }
      \`\`\`
   4. Declaration:
      ```java
      NewHero a = new NewHero();
      ```
2. Constructor with parameters
   1. entering values in the parameters would sets the value for the objects.
   2. exapmle:
      ```java
      /** Constructor. Constrcts a hero with 
      *specified attack and hp. */
      public NewHero1(nattack,nhp)
      {
       attack = nattack;
       hp = nhp;
      }
      ```
   3. Declaration:
      ```java
      NewHero b = new NewHero(33,500);
      ```
3. note that b and c are only addresses for the objects, rather than storing objects themselves.

#### Accessors

An accessor returns some information about the object.

```java
/** @return the balance of this account */
public double getData()
{ return balance; }
```

#### Mutators

A mutator changes the state of an object by modifying at least one of its variables.

```java
/** @ alter one of the instance variables.*/
public void ()
{ return balance; }
```

### Static Methods

static methods can use a static variable in its code rather than a private instance variable.

```java
public static double getInterestRate()
{
    System.out.println("Enter interest rate for bank account /n Enter in decimal form.")
    intRate = IO.readDouble()
    return intRate
}
```

### Method Overloading

Using two or more methods in the same class that have the same name but different parameter lists.

```java
public class DoOperations
{
    public int product (int n) {return n * n};
    public double product (double x) {return x * x}
}
```

## Scope ##



