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

