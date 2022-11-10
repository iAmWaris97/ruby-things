// Tutorial //
# Understanding Data Types in Ruby

> When you write programs, you use data types to classify data. Data types tell the computer how to handle the data in your program. They also determine what you can do with the data, including which operations you can perform.

> The followings are the data types in Ruby

### Integers

- You can print out an integer like this:

```
print -25
```

```
Output
-25
```

- You can also store the integer in a variable and then print the value out by referencing the variable:

```
my_int = -25
print my_int
```

```
Output
-25
```

- You can do math with integers, too. For example, you can calculate the sum of two numbers and print out the result:

```
sum = 116 - 68
print sum
```

```
Output
48
```

### Floating-Point Numbers

- You can print out floats in Ruby just like you print out integers:

```
print 17.3
```

```
Output
17.3
```

- You can also declare a variable and assign a float:

```
my_float = 17.3
print my_float
```
```
Output
17.3
```

- And, just like with integers, you can do math with floats in Ruby, too:

```
sum = 564.0 + 365.24
print sum
```
```
Output
929.24
```

- If you add a float to an integer in Ruby, you’ll get a float:

```
sum = 564 + 365.24
print sum
```
```
Output
929.24
```

### Boolean Data Types

- Many operations in math give us answers that evaluate to either true or false:

  - greater than
    - 500 > 100 true
    - 1 > 5 false
  - less than
    - 200 < 400 true
    - 4 < 2 false
  - equal
    - 5 = 5 true
    - 500 = 400 false


- Like with numbers, you can store a true or false value in a variable:

```
result = 5 > 8
```

- You can then print the Boolean value with a call to the print() function:

```
print result
```

- Since 5 is not greater than 8 you’ll see the following result:

```
Output
false
```

### Strings

> In Ruby, so to create a string, enclose a sequence of characters in quotes, like this:

```
"This is a string in double quotes."
```

- ex:

```
print "Hello, World!"
```

```
output = "Hello, World!"
```

### Arrays

> Arrays are defined by specifing values between square brackets [ ], separated by commas.

> An array of integers looks like this:

```
[-3, -2, -1, 0, 1, 2, 3]
```

  > Here’s a list of strings:
```
['shark', 'cuttlefish', 'squid', 'mantis shrimp']
```

  > Like other data types, you can assign an array to a variable:
```
sea_creatures = ['shark', 'cuttlefish', 'squid', 'mantis shrimp']
```

