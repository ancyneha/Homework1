1. Print out your favorite color and write comment about what you are doing above the code.


```python
# printing my favorite color

fav_color = 'pink'
print(fav_color)
```

    pink
    

2. Print the sumation of numbers 1 to 10


```python
# addin g the numbers from 1 to 10
x = 1, 2, 3, 4, 5, 6, 7, 8, 9, 10
sum = 1+2+3+4+5+6+7+8+9+10
print(sum)

```

    55
    

3. Print what 2 to the 8th power is.


```python
x = 2**8
print(x)
```

    256
    

4. Print the remainder of 100 divided by 11. 


```python
100%11
```




    1



5. What is the result of adding strings: 20, 8, 77?


```python
x = '20' + '8' + '77'
print(x)
```

    20877
    

6. Print out 100 divided by 5


```python
x = 100/5
print(x)
```

    20.0
    

7. What is the different between 10/4 and 10//4?  Print out the result


```python
#module operation gives you the result without remainder
x = 10/4
y = 10//4
print(x)
print(y)
```

    2.5
    2
    

8. Create a variable called height and store your height value there.
Print a sentence describing your height and use the variable in the sentence as well.


```python
print("What is your height?", end="  ") # add an extra blank space after the question

height = input()

print("My  height is " + height + ' ')
```

    What is your height?  164
    My  height is 164 
    

9. Print the same information as exercise 8 using a formatted string. 


```python
height = 164

# return the value of the variable in a specific format

print(f"My height is {height}")
```

    My height is 164
    

10. Use two different (single and double) quotes in a string to print out a sentence


```python
print("My 'favorite' animal is dog")
```

    My 'favorite' animal is dog
    

11. Print out Hello World! 7 times each on a new line using only one line of code.


```python
# print Hello World! 7 times
print("Hello World!\n Hello Wolrd!\n Hellow World!\n Hello World!\n Hello World!\n Hello World!\n Hellow World!")

```

    Hello World!
     Hello Wolrd!
     Hellow World!
     Hello World!
     Hello World!
     Hello World!
     Hellow World!
    

12. Write a code to get two integers from a user. Then print out their summation, subtraction, multiplication, and division.


```python
prompt = f"Enter an intiger:"

x = input("Enter an intiger")
y = input("Enter an intiger")


print(x+y)
print(x-y)
print(x*y)
print(x/y)
```

    Enter an intiger23
    Enter an intiger45
    2345
    


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    <ipython-input-41-c5b79741abf8> in <module>
          6 
          7 print(x+y)
    ----> 8 print(x-y)
          9 print(x*y)
         10 print(x/y)
    

    TypeError: unsupported operand type(s) for -: 'str' and 'str'



```python
# a prompt can be added to provide the user with more direction or a stylistic choice 

prompt = ">"

print("Enter a number:")

numb1 = input(prompt) # include the prompt in the paraenthses of the input function 

print("Enter next number:")

numb2 = input(prompt)

total = numb1 * numb2

print(f"{numb1} * {numb2} = {total}")

## remember, by default input() returns a string value
```


```python
 
```

13. You and your collegue have been tasked to write a code to get 5 numbers from a user and then print out their summation and average in a formatted string.  Your partner wrote codes below.  Now it is up to you to fix any errors.


```python
prompt = ">"

print("Enter a number:")
numb1 = int(input(prompt)) # use the int() function to convert input from string to integer

print("Enter next number:")
numb2 = int(input(prompt))

total = numb1 * numb2

print(f"{numb1} * {numb2} = {total}")
```

    Enter a number:
    >24
    Enter next number:
    >43
    24 * 43 = 1032
    


```python
print(f"{numb1} + {numb2} = {numb1 + numb2}")
print(f"{numb1} - {numb2} = {numb1 - numb2}")
print(f"{numb1} * {numb2} = {numb1 * numb2}")
print(f"{numb1} / {numb2} = {numb1 / numb2}")
```

    24 + 43 = 67
    24 - 43 = -19
    24 * 43 = 1032
    24 / 43 = 0.5581395348837209
    

14. You and your partner have been assigned to a project to write a program to calculate the amount of runoff rain on a roof from any given rainfall.  

You and your partner have figured out that to calculate the runoff from any given rainfall, you need to take the dimensions of the footprint of the roof and convert them to inches. (So, a 50' x 20' roof is 600" x 240"). Then, multiply the roof dimensions by the number of inches of rainfall. As an example, 600" x 240" x 1" = 144,000 cubic inches of water for an inch of rainfall. Finally, divide that result by 231 to get the number of gallons (because 1 gallon = 231 cubic inches). (144,000/231 = 623.38).

Your partner started coding before getting sick and it is up to you to finish the program.


```python
print("\nRainfall Calculation ***\n")

width = int("What's roof's width in foot? ")
length = int("What's roof's length in foot? ")
rain = int("How much did it rain? ")


area = width * length * rain

```


```python
print("\nRainfall Calculation ***\n")

width = int("240 ")
length = int("600 ")
rain = int("1 ")


area = (width * length * rain)
print(area)
gallon = area/231
print(gallon)
print(f"Gallon:\t\t{gallon:.2f}")
```

    
    Rainfall Calculation ***
    
    144000
    623.3766233766233
    Gallon:		623.38
    


```python

```

15. A program is required to get a customer’s name, a purchase amount and a discount rate (in %). The program must compute the discount amount, sales tax (6%) and the total amount due. Using one print statement, print the customer’s name, purchase amount, discount amount, sales tax and total amount due in friendly format.


```python
print("What is your name?", end="  ")
name = input()

print("what is the purchase amount:")
purchase_amount = input()

print("what is the discount rate:")
discount_rate = input()

 
sales_tax = 0.060
total_amount = (purchase_amount + str(sales_tax))



```

    What is your name?  Ancy
    what is the purchase amount:
    600
    what is the discount rate:
    25%
    


```python

```


```python

```
