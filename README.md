# Python-Miniproject1
1. Round function in Python
```
pasta=16.68
pasta_sauce=6.98
garlic=16.78
italianseasoning=15.26
artisanbaguetts=3
meatballs=4.39
total=pasta+pasta_sauce+garlic+italianseasoning+artisanbaguetts+meatballs
print(total)
print(round(total,2))
```
```
Output:
63.089999999999996
63.09
```
```
word = "abracadabra"

print(word[:3])
print(word[2:5])
print(word[4:])

# string Concatination
word1= "welcome"
word2= " to"
word3= " the"
word4= " Magic"
word5= "World!"

sentence1=word1+word2+word3+word4+word5
print(sentence1)

word6 = "Just do it!"
# To access the "!" from the word6 by index and print it
print(word6[10])

# To print the "do" from word6

print(word6[5:7])

# To get and print the slice "it!" from word6

print(word6[8:11])

# To print the slice "Just" from the word6

print(word6[0:4])

# Get the string slice "do it!" from the word6 and concatenate it with the string "Don't".
print("Don't"+word6[4:])

# type(), str() and escape sequences
a=3.1456

print(type(a))

print(str(a) +" is a float")

print('Hello. I\'m Sankari, it\'s nice to meet you!')
```
```
Output:
abr
rac
cadabra
welcome to the MagicWorld!
!
do
it!
Just
Don't do it!
<class 'float'>
3.1456 is a float
Hello. I'm Sankari, it's nice to meet you!
```

```
# print an asterisk triangle
print("*******\n *****\n  ***\n   *")
OUtput:

*******
 *****
  ***
   *

```
```
# Volume of a cylinder
def vol(pi,r,h):
    v=pi*r**2*h
    return(v)

pie=float(input("Enter the value for Pi:"))
radius=int(input("Enter the value for r:"))
height=int(input("Enter the value for h:"))

print("volume of the cylinder:"+str(round(vol(pie,radius,height),2)))
```
```
output:
Enter the value for Pi:3.14
Enter the value for r:4
Enter the value for h:5
volume of the cylinder:251.2
```
```
# Celsius to Fahrenheit
c=int(input("Please enter an integer value for the Celsius temperature: "))

def fahrenheit(celsius):
   F=round(float(1.8*celsius+32))
   return(F)

fahrenheit(c)
print("The Fahrenheit equivalent of "+ str(c)+ " degrees Celsius is "+ str(fahrenheit(c)))
```
```
# Output:
Please enter an integer value for the Celsius temperature: 40
The Fahrenheit equivalent of 40 degrees Celsius is 104
```
```
# Miles per gallon
import random

gallons = random.randint(10,25)
miles = random.randint(200,400)
print("Number of gallons: ",gallons)
print("Number of miles:",miles)
mpg=miles//gallons

print("Milage the car gives is: ",mpg)
```
```
Output:
Number of gallons:  24
Number of miles: 276
Milage the car gives is:  11
```
```
# Grade determiner
score = int(input("Please enter the score:"))

if score>=90:
    print("The score is :",score)
    print("The Grade is : A")
else:
      if score >=80:
        print("The score is :" ,score)
        print("The Grade is : B")
      else:
          if score >=70:
            print("The score is: ",score)
            print("The Grade is: C")
          else:
                if score >= 60:
                    print("The score is: ",score)
                    print("The Grade is: D")
                else:
                  print("The score is: ",score)
                  print("The Grade is: F")



```
```
# Output:
Please enter the score:65
The score is:  65
The Grade is: D

Please enter the score:100
The score is : 100
The Grade is : A

```
```
Write a program that iterates over the integers 1 through 50 using a loop.

However, for numbers which are multiples of both 3 and 5 print “FizzBuzz” in the output.
For example, 15 is divisible by both 3 and 5, so instead of printing 15, print "FizzBuzz".
For numbers which are multiples of 3 but not 5 (such as 42) print “Fizz” instead of the number.
For the numbers that are multiples of 5 but not 3 (such as 20) print “Buzz” instead of the number.

All of the integers which are not multiples of 3 or 5 should just be printed as themselves.

num=range(1,51,1)
for i in num:
    if i%3==0 and i%5==0:
        print("FizzBuzz")
    else:
        if i%3==0 and i%5!=0:
            print("Fizz")
        else:
            if i%3!=0 and i%5==0:
                print("Buzz")
            else:
                    if i%3!=0 and i%5!=0:
                      print(str(i))

```
```
# Output:
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
16
17
Fizz
19
Buzz
```
```
# Factorial of a number
num=int(input("Enter a integer: "))
init=num
fact=1
while(num!=0):
    fact=fact*num
    num=num-1
print("Factorial of "+str(init)+" is",fact)

```
```
# Output:
Enter a integer: 8
Factorial of 8 is 40320
```

```
# string Functions

string1="sankarinarayanan"
string2="HOW ARE YOU?"
s=string1.upper()
print(s)
t=string2.lower()
print(t)
print(s.isupper())
print(t.isupper())
```

```
Create a variable called mixed_case and assign it the string "A Song of Ice and Fire"
mixed_case="A Song of Ice and Fire"

Use .isupper() to check if mixed_case is a string of all upper case letters.  print() the result.
print(mixed_case.isupper())

Use .islower() to check if mixed_case is a string of all lower case letters.  print() the result.
print(mixed_case.islower())

Change all of the letters in mixed_case to upper case letters using .upper() and print() the result.
print(mixed_case.upper())

Change all of the letters in mixed_case to lower case letters using .lower() and print() the result.
print(mixed_case.lower())

Use the .istitle() method to check if mixed_case is title case and print the result.
print(mixed_case.istitle())

Create a variable called title_case and assign it the result of .title() being called on mixed_case.
title_case=mixed_case.title()
print() title_case
print(title_case)
```


```
Call startswith() on mixed_case with the letter mixed_case starts with as its argument.  print() the result.
print(mixed_case.startswith("A"))

Call endswith() on mixed_case with the letter mixed_case ends with as its argument.  print() the result.
print(mixed_case.endswith("e"))

Create a variable called words and assign it the result of split() being used on mixed_case.
words=mixed_case.split()

print the variable "words"
print(words)

Use the .join() method to join together all of the items in the list assigned to words as a single string.  Use .isalpha() to check if the string is made up entirely of letters.  Finally, use print() to display the result.
c="".join(words)

print(c)

f=c.isalpha()
print(f)
```

```
# ljust(),rjust(),center(),replace()

string1="Hello world"
print(string1.ljust(20,'*'))
print(string1.ljust(25,'*')+" Hello again!!")
print(string1.rjust(25,'*'))
print(string1.center(25,'*'))

print("11111 I had an exciting trip!!!!1111".strip('1'))
print("11111 I had an exciting trip!!!!1111".lstrip('1'))
print("11111 I had an exciting trip!!!!1111".rstrip('1'))

print("Good morning!!".replace('morning','afternoon'))

```
```
# output
Hello world*********
Hello world************** Hello again!!
**************Hello world
*******Hello world*******
 I had an exciting trip!!!!
 I had an exciting trip!!!!1111
11111 I had an exciting trip!!!!
Good afternoon!!

```




