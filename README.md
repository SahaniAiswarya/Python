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




