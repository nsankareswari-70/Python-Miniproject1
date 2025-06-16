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

```
Create a variable called string1 and assign it the string "North Dakota".
string1="North Dakota"

Call .rjust() on string1 with 17 as its argument and print() the result.
print(string1.rjust(17))

Call .ljust() on string1 with the arguments 17 and "*" then print() the result.

print(string1.ljust(17,'*'))

Create a variable called center_plus and assign it the result of .center() being called on the_string with 16 and "+" as arguments.
Use print() to display the string assigned to center_plus.

center_plus = string1.center(16,'+')
print(center_plus)

Call .lstrip() on string1 to remove "North" then print() the result.

s2=string1.lstrip('North')
print(s2)

Call .rstrip() on center_plus with "+" as its argument and print() the result.

s3=center_plus.rstrip('+')
print(s3)

Call .strip() on center_plus with "+" as its argument and print() the result.
s4=center_plus.strip('+')
print(s4)

Call .replace() on string1 and replace "North" with "South".  print() the result.
s5=string1.replace('North','South')
print(s5)

```

```
#output

     North Dakota
North Dakota*****
++North Dakota++
 Dakota
++North Dakota
North Dakota
South Dakota
```
```
# String Reverse
string1=input("Please enter the string: ")
print("The given string is:"+string1)
rev=""

for i in range(len(string1)-1,-1,-1):
  rev=rev+string1[i]
print("The reverse string is :"+rev)
```
```
#output:

Please enter the string: Sankari
The given string is:Sankari
The reverse string is :iraknaS

```
```
# counting words
str1 = "Daisy teaches English."
str2="Subjects – A noun, noun phrase or pronoun that does the action mentioned in the sentence. It mostly occurs at the beginning of the sentence. Predicates – The remaining part of the sentence. It begins with the verb."
str3="Every new sentence should begin with a capital letter."

def wordcount(sen):
  wc=1
  sandl=""
  for i in sen:
    if i.isalnum() or i.isspace() or i=='-' or i=="'":
      sandl=sandl+i
  for j in sandl:
    if j==" ":
      wc=wc+1
  return(wc)


print("Number of words in str1:"+str(wordcount(str1)))
print("Number of words in str2:"+str(wordcount(str2)))
print("Number of words in str3:"+str(wordcount(str3)))
```
```
Number of words in str1:3
Number of words in str2:38
Number of words in str3:9
```
```
# Format() function:
name=input("Please enter your name:")
degree=input("Please enter your major:")
job=input("Please enter your job")
exp=input("Please enter your years of experience")

print(name+" is majored in "+degree+" working as a "+job+" has "+exp+" of experience")
# using Format() function
print("{} is majored in {} working as a {} has {} of experience ".format(name,degree,job,exp))

```
```
name=input("Please enter your name:")
degree=input("Please enter your major:")
job=input("Please enter your job:")
exp=input("Please enter your years of experience:")

print(name+" is majored in "+degree+" working as a "+job+" has "+exp+" of experience")
# using Format() function
print("{} is majored in {} working as a {} has {} of experience ".format(name,degree,job,exp))
```
```
Please enter your name:Sankari
Please enter your major:M.C.A
Please enter your job:Data Analyst
Please enter your years of experience:3
Sankari is majored in M.C.A working as a Data Analyst has 3 of experience
Sankari is majored in M.C.A working as a Data Analyst has 3 of experience 
```

```
l1=[1,2,4,6,8]
print(8 in l1)
print(5 in l1)

a=[1,4.316,True,"Sankari",[50,45,30]]

b=list[a];
print(b)

print('e' in a)

print('a' not in a)

Create a variable and assign it the list [[0, 2], [4, 6], [8, 10], [12, 14]]
list1=[[0,2],[4,6],[8,10],[12,14]]

Access the first list from the list of lists in step 1 by index then print it.
print(list1[0])

Access the 14 from the list in step 1 then print it.
print(list1[3][1])

Create a second variable and assign it the list ["chair", "table", "desk", "lamp", "bed"]
list2=["chair","table","desk","lamp","bed"]

Use a negative integer to access "chair" from the variable in step 4 by index then print it.
print(list2[-5])

Print "Most people own at least 2 chairs." by concatenating the 2 from the list in step 1 and the "chair" from the list in step 4 with "Most people own at least ", a space, and a period.
print("Most people own at least "+str(list1[0][1])+" "+list2[0]+'s')

Create a third variable and assign it the list [0.98, 8.76, 6.54, 4.32]
list3=[0.98,8.76,6.54,4.32]

Print the slice [8.76, 6.54, 4.32] from the variable you created in step 7.
print(list3[1:])

Print the slice [8.76, 6.54] from the variable you created in step 7.
print(list3[1:3])


Print the slice [0.98, 8.76] from the variable you created in step 7.
print(list3[0:2])

```
```
#output:
True
False
list[[1, 4.316, True, 'Sankari', [50, 45, 30]]]
False
True
[0, 2]
14
chair
Most people own at least 2 chairs
[8.76, 6.54, 4.32]
[8.76, 6.54]
[0.98, 8.76]
```
```
# del and list methods
1.Create a variable called arctic_animals and assign it the list ["penguin", "elephant", "polar bear", "walrus", "tiger", "reindeer"]
artic_animals=["penguin","elephant","polar bear","walrus","tiger","reindeer"]

2.Use del to remove "tiger" from the list assigned to arctic_animals.
del artic_animals[4]
print(artic_animals)

3.Use the .remove() method to remove the string "elephant" from the list assigned to arctic_animals.
artic_animals.remove("elephant")
print(artic_animals)

4.Use the .append() method to add the string "arctic fox" to the list arctic_animals.
artic_animals.append("artic fox")
print(artic_animals)

5.Use .insert() to insert the string "snowy owl" between the strings "polar bear" and "walrus" inside of arctic_animals.
artic_animals.insert(2,"snowy owl")
print(artic_animals)

6.Use the .sort() method to rearrange the strings in arctic_animals into alphabetical order.
artic_animals.sort()
print(artic_animals)

7.Use .index() to get the index number of "reindeer" from arctic_animals then print it.
print(artic_animals.index("reindeer"))

8.Use .pop() to get the last item from the list arctic_animals then print it.
print(artic_animals.pop())

```

```
Output:
['penguin', 'elephant', 'polar bear', 'walrus', 'reindeer']
['penguin', 'polar bear', 'walrus', 'reindeer']
['penguin', 'polar bear', 'walrus', 'reindeer', 'artic fox']
['penguin', 'polar bear', 'snowy owl', 'walrus', 'reindeer', 'artic fox']
['artic fox', 'penguin', 'polar bear', 'reindeer', 'snowy owl', 'walrus']
3
walrus
```
```
# Dictionaries

1. create a variable and assign it a dictionary that has 5 key value pairs
a={"fruit1":"apple","fruit2":"orange","fruit3":"Mango","fruit4":"pineapple","fruit5":"grapes"}

2.print and access the value held at the third key in the dictionary
print(a["fruit3"])

3. use the in keyword to check if a key appears in the dictionary and print the result
print("fruit2" in a)

4.use not in to check if a key does not appear in the dictionary and print the result
print("fruit8" not in a)

```
```
# output:
Mango
True
True
```

```
1. create a variable and assign it the following dictionary:

{"Queen": "Bohemian Rhapsody", "Bee Gees": "Stayin' Alive", "U2": "One", "Michael Jackson": "Billie Jean", "The Beatles": "Hey Jude", "Bob Dylan": "Like A Rolling Stone"}
2. Make the dictionary span multiple lines so that the line the dictionary starts on is not too long.

dict1={"Queen": "Bohemian Rhapsody",
       "Bee Gees": "Stayin' Alive",
       "U2": "One",
       "Michael Jackson": "Billie Jean",
       "The Beatles": "Hey Jude",
       "Bob Dylan": "Like A Rolling Stone"}
3. print the length of the dictionary.
print(len(dict1))

4. use the .keys() method and a for loop to get and print all of the keys from the dictionary on separate lines.

for key in dict1.keys():
    print(key)
print("\n")

5.  print all of the values from the dictionary using the .values() method.
for value in dict1.values():
        print(value)
print("\n")

6. use .items() with a for loop to iterate through and print all of the key value pairs from the dictionary.
for i, j in dict1.items():
    print(i, j)

7. use the .get() method to check the dictionary for the key

"Promise of the Real"
and create a message that will print if the key is not found in the dictionary.
print(dict1.get("Promise if the Real","Key not found"))

```



