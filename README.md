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






















