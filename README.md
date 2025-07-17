#Tuple swaping
a=1
b=2
a,b=b,a
print(a,b)

#temporarily variable swaping
a=1
b=2
print("a:",a)
print("b:",b)
temp=a
a=b
b=temp
print("a:",a)
print("b:",b)

#swaping using arithmetic operators(addition and subtraction)
a=int(input("enter the value of a:"))
b=int(input("enter the value of b:"))
a=a+b
b=a-b
a=a-b
print("after swaping:")
print("a:",a)
print("b:",b)


#swaping using arithmetic operators(multiplication and division)
a=int(input("enter the value of a:"))
b=int(input("enter the value of b:"))
a=a*b
b=a/b
a=a/b
print("after swaping:")
print("a:",a)
print("b:",b)

#data types list
fruits=["apple","banana","kiwi"]
print(fruits)
print(fruits[2])

#data types list
fruits=["apple","banana","kiwi"]
print(fruits)
print(fruits[-1])

#string method
nums=[0,1,2,3,4,5,9,8,7,6]
print(len(nums))

#not print 0 ,4,5
nums=[0,1,2,3,4,5]
print(nums[1:4])
print(nums[3:6])
print(nums[:3])
print(nums[::2])
print(nums[::-1])
print(nums[:-1])

nums=[0,1,2,3,4,5]
print(6 in nums)
print(3 in nums)

fruits=["apple","mango","cherry"]
fruits.sort()
print(fruits)

fruits=["apple","mango","cherry"]
fruits.reverse()
print(fruits)

#nested list
nestnum=[[1,2],[3,4],[5,6]]
print(nestnum[1])
print(nestnum[2][0])
print(nestnum[1][1])
print(nestnum[2][1])

#reverse the string with respect to their index
#str='india won'   output 'aidni now'
text="india won"
word=text.split()
w1=word[0][::-1]
w2=word[1][::-1]
result=' '.join([w1,w2])
print(result)


print("india".capitalize())
print("india".isascii())
print("6".ljust(10,"$"))
print("6".rjust(10,"$"))
print("india".swapcase())
print("661".zfill(4))
print("india wins".title())
#find
print("one key for a lock".find("for"))
print("one key for a lock".rfind("for"))
#index
print("one key for a lock".index("for"))
print("one key for a lock".rindex("for"))
#count
print("mississippi".count('s'))
#isalnum()
print("JamesBond 007".isalnum())
#isalpha()
print("JamesBond".isalpha())
#isdigit
print("444".isdigit())
#isdecimal
print("444".isdecimal())
#islower
print("hi".islower())
#isupper
print("hi".isupper())
#isspace
print(" ".isspace())

#assign operator
num=100
print(num)
#or print("this is a sample",num)

#increment in operators
num=1
num=num+1 #num+=1
print(num)

#wrong output if we dont give data types
num1=input()
num2=input()
total=num1+num2
print(total)

#with data types
num1=int(input())
num2=int(input())
total=num1+num2
print(total)

#string
str1=input("enter a number")
str2=input("enter a number")
fullname=str1+str2
print(fullname)

num1=input("enter a name")
num2=input("enter a name")
fullname=num1+""+num2
print(fullname)

num1=str(input())
num2=str(input())
fullname=num1+num2
print(fullname)

n1=float(input("enter a float value"))
n2=float(input("enter a float value"))
print("division",n1/n2)

s=str(input("enter a string"))
print(s)
print(len(s))
print(s.upper())
print(s.lower())
print(s[1:3])
print(s[::-1])

#list operators
fruits=["apple","kiwi","orange"]
fruits.append("banana")
fruits.remove("apple")
print(fruits[0])
print(fruits[-3])
print(fruits)

#list with in a list
nest=[[1,2,3,4],[5,6]]
print(nest)
print(nest[0])
print(nest[1][0])
print("modify")
nest[0][1]=99
print(nest)
nest[1]=100
print(nest)
l2=[[1,2],[3,4]]
l2.append([11,22])
print(l2)


























