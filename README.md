# py.assignment-reverse

# case 1:

str= input("enter the string: ") 
reversedString=[]
index = len(str) 
while index > 0: 
    reversedString += str[ index - 1 ] 
    index = index - 1 
print(reversedString)

# case 2:

str=input("enter the string: ")
str1=''
for i in str:
    str1=i+str1
print('the output is:',str1)
