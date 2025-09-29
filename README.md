# learning_python_1_datastructures
print("I am using escape sequences\nThis is a new line")
print("to seperate", 6, 7, sep="_", end="lol")
print("anything")
#use hashstag to comment-These are my python notes
#'control+ forward slash(/)' to comment out multiple lines and 'ctrl+\' for uncommenting. Same with ''' ''' or """ """ for multiple lines
a=10
a1=8.2
b="lafoot"
c=True
d=complex(8,2)
print(a+a1)
print("the type of a,b,c, & d are", type(a),",", type(b),",", type(c),",",type(d))
#list is a data structure that allows multiple values and different data types. mutable can change. immutable cannot change
#tuple is immutable. tuple is faster than list.
#dictionary is an unordered collection of data containing key-value pairs. It is generally used when we have a huge amount of data. Dictionaries are optimized for retrieving data. We must know the key to retrieve the value.
print(13//5) #floor division
print(13%5) #modulus
print(2**3) #exponent
print(2**3/2*3/3+6-4) #BODMAS
print("10+8.2=", a+a1)
print("10-8.2=", a-a1)
print("10*8.2=", a*a1)
print("10/8.2=", a/a1)
# pa2=input("enter your name:") #input function
# print("my name is", pa2) # input datatype is string
#st= """"I can write anything in this string and it will be printed as it is. Multiple lines and paragraphs""".
print(b[0])
print(b[1])
print(b[2])
print(b[3])#string indexing
print(b[0:3]) #string slicing
for character in b:
    print(character) #string iteration
print(len(b))
#print(b[:-2]) #string slicing
b1 = "lAfOot, !!!"
print(b1.upper())#string functions
print(b1.lower())
print(b1.rstrip("!"))#removes trailing characters
print(b1.replace("lAfOot", "lafoot"))
print(b1.split(" "))#splits the string at the mentioned variable and returns a list
print(b1.capitalize())#capitalizes the first letter
print(b1.center(50))#prints the string in the center of 50 characters
print(len(b1))
print(b1.count("O"))#counts the number of times the mentioned variable appears in the string
print(b1.find("f"))#returns the index of the first occurrence of the mentioned variable
print(b1.index("f"))#returns the index of the first occurrence of the mentioned variable
print(b1.isalnum()) #returns true if all characters in the string are alphanumeric
print(b1.isalpha())#returns true if all characters in the string are alphabets
print(b1.islower())#returns true if all characters in the string are lower case
print(b1.isprintable())#returns true if all characters in the string are printable
print(b1.isspace())#returns true if all characters in the string are whitespaces
print(b1.istitle())#returns true if the string follows the rules of a title
print(b1.swapcase())#swaps cases of all characters in the string
