ASCII value of  character in Python
Here, On this page we will discuss program to find the ASCII value of a character in Python. The machine doesn’t have the capacity to understand languages that humans do, the machine understands binary language and converts everything to binary format.

ASCII value of a character in python

Did you know?
 ASCII stands for American Standard Code for Information Interchange
Which is a binary code used by electronic equipment for electronic communications
A total of 128 characters have been assigned values from 0 – 127
Alphabets (  65 – 90  &  97 – 122  )
Digits (  48 – 57  )
Remaining are Special Character (  !, @, #, $, * …..)
Working
User gives an input
Input is stored in a char type variable say val.
val is converted from char to int .
The ASCII value of Character is Obtained
ASCII value of a character
Python code
Run
# user input
Char = 'z'

# convert Char to Ascii value
Ascii_val = ord(Char)

# print Value
print('The ASCII value of', Char, 'is', Ascii_val)
Output
The ASCII value of z is 122
