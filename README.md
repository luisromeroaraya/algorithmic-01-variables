# Variables
* Type of challenge: **learning**
* Duration: **30 min**
* Team challenge: **solo**

## Learning objectives
At the end of this challenge you should:
* understand the concept of variables
* be able to declare variables
* be able to assign value to variables

## The mission
This challenge will have you play around with the concept of [variables](https://en.wikipedia.org/wiki/Variable_(computer_science)), complete the exercises down below after you’ve read the explanations.

A variable is like a box holding a value, it can be called upon whenever needed and changed after assignment (except for constant). It also has a type which defines the kinds of data you can store inside.

Types of variables
* [constant](https://en.wikipedia.org/wiki/Constant_(computer_programming)): store a value of any types that cannot change
* [integer](https://en.wikipedia.org/wiki/Integer): store integers
* [float](https://en.wikipedia.org/wiki/Floating-point_arithmetic): store real numbers (ex: 3.14159)
* [character](https://en.wikipedia.org/wiki/Character_(computing)): store one character
* [boolean](https://en.wikipedia.org/wiki/Boolean_data_type): store either true or false
* [string](https://en.wikipedia.org/wiki/String_(computer_science)): store a sequence of character
* [array](https://en.wikipedia.org/wiki/Array_data_type): store an array of values

Programming languages usually have some predefined functions such as output and input allowing the code to print something to the screen or ask for a user input.

Furthermore, you should also research [operators](https://computersciencewiki.org/index.php/Operators) and how to do operation within your code.

Example
```// This algorithm will output "Hi my name is John Doe and I am 42."
constant NAME = "John Doe"
integer age

input("What's your age?",$age)
output("Hi my name is $NAME and I am $age.")

// This algorithm will output "10".
integer nbr = 5
output($nbr * 2)
```

## Exercises

Instructions
* write your algorithm on paper
* detail each and every step
* indicates the types of used variables

*I will be using [Python3](https://repl.it/languages/python3) to write and test the algorithms*

I - calculate
Write an algorithm which calculates:
- [x] the sum of two chosen number
- [x] the division of two chosen number
- [x] the [modulo](https://en.wikipedia.org/wiki/Modulo_operation) of two inputed numbers

```number1=int(input("Enter your first number:"))
number2=int(input("Enter your second number:"))

sum=number1+number2
division=number1/number2
modulo=number1%number2

print(number1,"+",number2,"=",sum)
print(number1,"/",number2,"=",division)
print(number1,"mod",number2,"=",modulo)
```

II - concatenate sentence
- [x] Write an algorithm which [concatenates](https://en.wikipedia.org/wiki/Concatenation) two phrases together.
```phrase1=input("Enter your first phrase:")
phrase2=input("Enter your second number:")

print(phrase1+phrase2)
```
III - VAT
- [x] Write an algorithm which receives a price without VAT and returns the price with VAT with a rate of 21%.
```price=float(input("Enter the price without VAT:"))
vat=price*0.21

print(price+vat)
```

IV - surface of a circle
- [x] Write an algorithm which receives the radius of a circle and calculate its surface.
```import math
radius=float(input("Enter the radius of a circle:"))
surface=math.pi*(radius**2)

print("The surface of your circle is:",surface)
```

V - conversion of time to seconds
- [x] Write an algorithm which receives the time of day in three different numbers, the hour, the minutes and the seconds and returns the number of seconds since midnight.

```hours=int(input("Enter hour:"))
minutes=int(input("Enter minutes:"))
seconds=int(input("Enter seconds:"))

total= (hours*60*60)+(minutes*60)+seconds

print("The number of seconds since midnight:", total, "seconds")
```

## Resources
* [conventions](https://github.com/becodeorg/BXL-Swartz-4-27/blob/master/1.The-Field/7.Algorithmic/conventions.adoc)
* [variables](https://computersciencewiki.org/index.php/Variables)
