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


#increment
num=1
num=num+1 # or num+=1 
print(num)
num-=1 
print(num)
num*=1
print(num)
num%=1
print(num)
num/=1
print(num)
num//=1
print(num)



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


#flatten
nest=[[1,2],[3,4],[5,6]]
flat=[]
for sub in nest:
    for item in sub:
        flat.append(item)
print(flat)







#list with in a tuple
student=("vijay",[20,45,90],['math','science','english'])
print(student[2])
print(student[1])
print(student[0])
print(student[2][1])


#tuple sample
info=("vijay",33,'engineer')
print(info[0])
print(info[-1])
print(len(info))
print(info*2)
print(info +(3,4))
print(info +('1234',5))


#nested tuple or tuple within tiple
nest=((1,2),(3,4),(5,6))
print(nest[0])
nest=((1,2),('a','b'),(5,6))
print(nest[1])
nest=((1,2),('a',7),(5,6))
print(nest[1][1])


#dictionary operations
person={'name':'aiswarya','age':20,'city':'vijayawada'}
print(person)
print("accessing and modify the the person age:")
person["age"]=21
print(person)
print("adding and deletind")
person["email"]='aiswaryasahani@gmail.com'
print(person)
del person["city"]
print(person)
print("all keys and values:")
print(person.keys())
print(person.values())
print(person.items())
print(person.get("age"))


#nested dictionary
info={"vijay":{"salary":12000,"perks":3000},"marks":{"salary":18000,"perks":5000}}
print(info['marks']['perks'])


#dict with tuple keys
location={(40,7128,-73.070):"new york",(34.0522,-119.234):"mumbai"}
print(location[(40,7128,-73.070)])


info={'name':'india','number':'123'}
v='india'
for key,value in info.items():
    if value==v:
        print(f"key for value '{v}':{key}")

        
#set operations
my_set={1,2,3,4}
print("add and remove values")
my_set.add(7)
print(my_set)
my_set.remove(2)
print(my_set)
my_set.discard(5)
print(my_set)
print("membership check")
print(1 in my_set)
print(10 in my_set)


#operations
print("union")
a={1,2,3}
b={3,4,5}
print(a.union(b))
print("intersection")
print(a.intersection(b))
print("difference")
print(a.difference(b))
print(" symmetricdifference")
print(a.symmetric_difference(b))


a={1,2}
b={1,2,3,4,5}
print(a.issubset(b))
print(b.issubset(a))
print(a<=b)
print(a<b)
print(a>=b)
print(b>a)







#concatination string
s1="india"
s2="won"
result=s1+"  "+s2
print(result)


#search or replace
str="India won the match by 5 wickets"
print(str.find("5"))
print(str.replace("5","9"))
print(str.replace("wickets","runs today"))


#split and join
str="alpha,beta,gamma"
parts=str.split(",")
print(parts)
joined=":".join(parts)
print(joined)
joined=",".join(parts)
print(joined)


#center function
str="india"
print(str.center(20,"*"))


#count
str='he'
text='hellohellhellohellhellohellohell'
print(text.count(str,0,len(text)))


#startwith and endwith .........searching
str1="dog is humans best friends"
str2="the climate is very dangerous"
print(str1.endswith("end",0,len(str1)))
print(str2.startswith("th",0,len(str2)))


#find anothr method
text="how was the meal today?"
print(text.find("meal",0,len(text)))
print(text.rfind("is",0,len(text)))


text="jamesbond007"
print(text.isalpha())
print(text.isalnum())
print(text.isdigit())
print(text.isspace())
print(text.isupper())
print(text.islower())
print(text.istitle())


str="hi"
print(str.ljust(20,"#"))
print(str.ljust(20,"-"))
print(str.ljust(2,"#"))
print(str.ljust(10,"&"))
print(str.ljust(12,"*"))
print(str.rjust(12,"*"))


#zfill
str="1234"
print(str.zfill(4))
print(str.zfill(5))
print(str.zfill(10))
print(str.zfill(3))
print(str.zfill(2))
print(str.zfill(1))


str='6'
print(str.zfill(4))


#enumerate
str="vijay komarapu"
print(list(enumerate(str)))


str="vijay"
print(str.swapcase())
str="sonic the dedgehog"
print(str.capitalize())
print(str.title())


#strip(remove space)
s='   hi aiswarya  '
print(s.strip())
print(s.lstrip())
print(s.rstrip())






#program for basic operations by taking user input of an equation
a=int(input("enter the value of a:"))
b=int(input("enter the value of b:"))
c=int(input("enter the value of c:"))
x=int(input("enter the value of x:"))
result=a*(x**2)+b*x+c
print("the result of the equation",result)


#swaping with temporarily variable [universal swaping]
a=int(input("enter the value of a:"))
b=int(input("enter the value of b:"))
temp=a
a=b
b=temp
print(a,b)


#swaping with temporarily variable [universal swaping]
a=int(input("enter the value of a:"))
b=int(input("enter the value of b:"))
c=a
a=b
b=c
print(a,b)


#swaping numbers (tuple swaping)
a=int(input("enter the value of a:"))
b=int(input("enter the value of b:"))
print("before swaping",a,b)
a,b=b,a
print(a,b)


#swaping using arithmetic operators (+,-)
a=int(input("enter the value of a:"))
b=int(input("enter the value of b:"))
a=a+b
b=a-b
a=a-b
print(a,b)


#swaping using arithmetic operators (*,/)
a=int(input("enter the value of a:"))
b=int(input("enter the value of b:"))
a=a*b
b=a/b
a=a/b
print(a,b)


#swaping using arithmetic operators xor
a=int(input("enter the value of a:"))
b=int(input("enter the value of b:"))
a=a^b
b=a^b
a=a^b
print(round(a),round(b))


#swaping using arithmetic operators xor
a=int(input("enter the value of a:"))
b=int(input("enter the value of b:"))
a=a^b
b=a^b
a=a^b
print(a,b)


#area and circumference of circle
r=float(input("enter radius:"))
pi=3.14159
area=pi*r**2
circumference=2*pi*r
print("area of circle",area)
print("circumference of circle",circumference)


#area and circumference of circle
from math import pi
r=float(input("enter radius:"))
area=pi*r**2
circumference=2*pi*r
print("area of circle",area)
print("area of circumference",circumference)


#square root and power
from math import sqrt,pow
n=int(input("enter the value:"))
print(sqrt(n))
print(pow(2,3))


#trigonometric functions
from math import sin,cos,tan,radians
angle=30
print("sin",sin(radians(angle)))
print("cos",cos(radians(angle)))
print("tan",tan(radians(angle)))


from math import floor,ceil
num=float(input("enter the value:"))
print("floor:",floor(num))
print("ceil:",ceil(num))


from math import log,log10,exp,e
print("natural log:",log(e))
print("log base 10 of 100:",log10(100))
print("e to the power 2:",exp(2))


#date time and calender epoch time
from datetime import datetime
now=datetime.now()
print("current time",now)
print("date:",now.date())
print("time:",now.time())


#calendar
import calendar
print(calendar.month(2004,7))


#calendar with year
import calendar
year=2025
print(calendar.calendar(year))


#calendar leap year
import calendar
leaps=calendar.leapdays(1925,2025)
print(leaps,end='')


#date difference 
from datetime import date
d1=date(2025,5,9)
d2=date(2025,1,1)
diff=d1-d2
print("diffrence in date:",diff.days)


#day abbrevation
from datetime import date
today=date.today()
name=today.strftime("%A")
print("today:",name)


#print first and last date of a month
import calendar
from datetime import date
year=2025
month=5
fday=date(year,month,1)
lday=date(year,month,calendar.monthrange(year,month)[1])
print("firstday",fday.strftime("%A,%Y-%M-%D"))
print("lastday",lday.strftime("%A,%Y-%M-%D"))


#print first and last date of a month
import calendar
from datetime import date
year=2025
month=5
fday=date(year,month,1)
lday=date(year,month,calendar.monthrange(year,month)[1])
print("firstday",fday.strftime("%A,%Y-%M-%D"))
print("lastday",lday.strftime("%A,%y-%m-%d"))






#conditional statements
num=99
if 99<0:
    print("hi student")
print("india")


#if condition
num=99
if num>0:
    print("hi student")
print("india")


#vote for eligible by usinf if condition
person=int(input("enter the age"))
if person>=18:
    print("eligible")


#vote for eligible by usinf if condition
person=int(input("enter the age"))
limit=18
if person>=limit:
    print("eligible")


#print the number is even and skip the condition if not exit
num=int(input("enter the number"))
if num%2==1:
    print("odd",num)
print("after condition exit")


#check if it is character ,digit,space
char=input("press any key:")
if char.isalpha():
    print("the user has entered character")
if char.isdigit():
    print("the user has entered digit")
if char.isspace():
    print("the user has entered space")


#if else condition
person=int(input("enter the age"))
limit=18
if person>=limit:
    print("eligible")
else:
    print("not eligible")


a=int(input("enter the a value:"))
b=int(input("enter the  value:"))
if a<b:
    small=a
else:
    small=b
print("smallest value",small)


a=int(input("enter the a value:"))
b=int(input("enter the  value:"))
if a>b:
    small=a
else:
    small=b
print("smallest value",small)


#if i/p is small then o/p is capital VICE VERSA
ch=input("enter the character")
if ch>='A' and ch<='Z':
    ch=ch.lower()
else:
    ch=ch.upper()
print("converted case of input char:",ch)


#leap year or not
num=int(input("enter number"))
if num%4==0 or num%100==0:
    print("leap year",num)
else:
    print("not leap year",num)
print("leap year",num)


#leap year or not
num=int(input("enter number"))
if num%4==0 or num%100==0:
    print("leap year")
else:
    print("not leap year")


#elif condition or ladder
num=int(input("enter the value:"))
if num==0:
    print("zero")
elif(num>0):
    print("positive")
else:
    print("negative")


#nested if
num=int(input("enter the number"))
if num==1:print("sunday")
elif num==2:print("monday")
elif num==3:print("tuesday")
elif num==4:print("wednesday")
elif num==5:print("thursday")
elif num==6:print("friday")
elif num==7:print("saturday")
else:print("wrong input")


#upper or lower letter is vowel or consonent 
ch=input("enter the character:")
if ch=='a' or ch=='e' or ch=='i' or ch=='o' or ch=='u':
    print("vowels")
elif ch=='A' or ch=='E' or ch=='I' or ch=='O' or ch=='U':
    print("vowel")
else:
    print("consonents")


#capital vowel  or small vowel and capital consonent or small consonent  
ch=input("enter the character")
if ch=='a' or ch=='e' or ch=='i' or ch=='o' or ch=='u':
    print("small vowels")
elif ch=='A' or ch=='E' or ch=='I' or ch=='O' or ch=='U':
    print("capital vowel")
else:
    print("consonents")


a=float(input("enter the number of a:"))
b=float(input("enter the number of b:"))
op=input("enter the operation(+,-,*./):")
if op=='+':
    print(a+b)
elif op=='-':
    print(a-b)
elif op=='*':
    print(a*b)
elif op=='/':
    if b!=0:
        print(a/b)
    else:
        print("invalid input")
else:
    print("invalid operator")





#looping statements
loop=0
while loop<=10:
    print(loop) #print(loop,end=" ")
    loop+=1


loop=0
while loop<=10:
    print("aiswarya",end=' ')
    loop+=1


loop=0
while loop<=10:
    print("aiswarya",end=' ')
    print("sahani",end='  - ')
    loop+=1


loop=0
while loop<=10:
    print("vijay",end=' ')
    print("cricket",end='  - ')
    loop+=1
print("looping over as condition fails")


#print sum of first natural number
sum=0
i=1
n=int(input("enter the value of n:"))
while i<=n:
    sum+=i
    i+=1
print("total",sum)


#reverse of natural number
n=int(input("enter he number"))
i=n
while i>=1:
    print(i,end=' ')
    i=i-1

    
#reverse a 4 digit number
n=int(input("enter the number"))
rev=0
print(n)
while n>0:
    d=n%10
    rev=rev*10+d
    n//=10
print(rev)


#another method of reverse a 4 digit number
n=int(input("enter the number"))
while n!=0:
    t=n%10
    print(t,end='')
    n//=10


#for var the range(start,stop)
n=int(input("enter the number:"))
for i in range(1,n+1,3):
    print(i,end=" ")


#for loop using string
name="mississippi"
for char in name:
    print(char,end=" ")


#lists in for loop
items=["maggie","5-star","borbon","lays"]
for sale in items:
    print(sale)


#reverse n numbers using for loop
n=int(input("enter the number"))
for i in range(n,0,-1):
    print(i,end=" ")
    
#another for reverse n number usimg for loop
for i in range(10,0,-1):
    print(i,end=" ")


#all squares uptp 10 using for loop
for i in range(1,11):
    print(i**2,end=" ")

#another all squares upto given n using for loop
n=int(input("enter the number"))
for i in range(1,11):
    print(i**2,end=" ")


#lists in for loop
items=["maggie","5-star","borbon","lays"]
for sale in items:
    print(sale)


#factorial using for loop
n=int(input("enter the number:"))
if n==0:
    f=1
f=1
for i in range(1,n+1):
    f=f*i
    print("factorial of",n,"is",f)


#reverse of string using for loop
s="mississippi"
rev=" "
for c in s:
    rev=c+rev
print(rev)





#user define function
def hi():
    print("hello students")
hi()


#user define function with parameter
def summate(a,b):
    print("sum of two numbers:",a+b)
a=int(input("enter the value of a"))
b=int(input("enter the value of b"))
summate(a,b)


def summate(x,y):
    print("sum of two numbers:",x+y)
a=int(input("enter the value of a"))
b=int(input("enter the value of b"))
summate(a,b)


#user define function with arguments and return value
def summate(x,y):
    return x+y
a=int(input("enter the value of a"))
b=int(input("enter the value of b"))
result=summate(a,b)
print(result)


def summate(x,y):
    print("sum of two numbers:",x+y)
c=int(input("enter the value of c"))
d=int(input("enter the value of d"))
summate(c,d)


#default argument
def power(base,expo=2):
    return base**expo
num=int(input("enter number"))
print(power(num))


#another method default argument
def power(base,expo=2):# or exp=3
    return base**expo
num=int(input("enter number"))
print(power(num,3))


#multiple return values from a single function
def operate(a,b):
    return a+b,a-b,a*b
a=int(input("enter a value:"))
b=int(input("enter b value:"))
sum,diff,prod=operate(a,b)
print("sum",sum)
print("sub",diff)
print("mul",prod)


#anonumous function lambda
#lambda var operation
num=int(input("enter the number"))
square=lambda num:num*num
print(square(num))


#another method lambda var operation
a=int(input("enter the a number"))
b=int(input("enter the b number"))
square=lambda a,b:a*b
print(square(a,b))


#nested function
def hi():
    def hello():
        print("inner function")
    print("outer function")
    hello()
hi()


#nested function
def operation(a,b):
    def add():
        return a+b
    def sub():
        return a-b
    print("addition",add())
    print("subtraction",sub())
a=int(input("enter a value"))
b=int(input("enter b value"))
operation(a,b)


#calculate the factorial and power
def operation(a,b):
    def fact(a):
        op=1
        for i in range(1,a+1):
            op*=i
        return op
    def power(a,b):
        return a**b
    print("factorial",fact(a))
    print("power",power(a,b))
a=int(input("enter a value"))
b=int(input("enter b value"))
operation(a,b)


#super factorial
def fact(n):
    if n==0 or n==1:
        return 1
    return n*fact(n-1)
def sfact(n):
    if n==1:
        return 1
    return fact(n)*sfact(n-1)
num=int(input("enter the number:"))
print("factorial",sfact(num))





#scope and lifetime of arguments in a function
num=int(input("enter the number:"))
print(num)
def modify():
    global num
    num=100
modify()
print(num)


#tuggle state function
#tuggling a global flag
is_active=False
def toggle_state():
    global is_active
    is_active=not is_active
    return is_active
print(f"initial state:{is_active}")
toggle_state()
print(f"state after 1st toggle:{is_active}")
toggle_state()
print(f"state after 2nd toggle:{is_active}")
toggle_state()


#annutations
def add(a:int,b:int): #->int
    return a+b
a=int(input("enter the a value:"))
b=int(input("enter the b value:"))
print(add(a,b))


#area of rectangle with single annutation
def area(l:int,b:int)->int:
    return l*b
x=int(input("enter the x value:"))
y=int(input("enter the y value:"))
print(area(x,y))
l=int(input("enter the l value:"))
b=int(input("enter the b value:"))
print(area(l,b))


from typing import List,Optional
def names(n:List[str],separator:Optional[str]=" ")->str:
    return separator.join(n)
print(names(["vijay","mark","steve"]))
print(names(["CSE","ECE"],separator="-"))


#tuple arg keyboard function
#sun of n user i/p values by tuple arg
def sumnum(*args):
    return sum(args)
nums=input("enter the number separated by space:")
numbers=[float(x) for x in nums.split()]
result=sumnum(*numbers)
print(f"sum:{result}")


def sortnum(*args):
    return sorted(args)
nums=input("enter the number separated by space:")
numbers=[int(x) for x in nums.split()]
result=sortnum(*numbers)
print(f"sorted:{result}")
x=result[::-1]
print("descending:",x)


#keyword argument
def info(**kwargs):
    for key,value in kwargs.items():
        print(f"{key}:{value}")
info(name="vijay",age=32)


def info(hi,**kwargs):
    print(hi)
    for key,value in kwargs.items():
        print(f"{key}=>{value}")
info("Hello!",name="vijay",age=32,city="vijayawada")





#Recursion
#linear / head
def hrec(n):
    if n==0:
        return
    print(n)
    return hrec(n-1)
num=int(input("enter the value"))
hrec(num)


#tail
def hrec(n):    
       if n==0:
           return
       hrec(n-1)  
       print(n)
num=int(input("enter the value"))
hrec(num)


#linear recursion factorial
def fact(n):
    if n==1:
        return 1
    return n*fact(n-1)
num=int(input("enter the number"))
print("factorial",fact(num))


def sumD(n):
    if n==0:
        return 0
    return (n%10)+sumD(n//10)
num=int(input("enter the number"))
print(sumD(num))


#indirect recursion
def one(n):
    if n>0:
        print("one",n)
        two(n-1)
def two(n):
    if n>0:
        print("two",n)
        one(n//2)
num=int(input("enter the number"))
one(num)


#indirect even or odd
def is_even(n):
    if n==0:
        return True
    return is_odd(n-1)
def is_odd(n):
    if n==0:
        return False
    return is_even(n-1)
num=int(input("enter the number"))
print(num,"is even",is_even(num))


#tree
def tree(n):
    if n<0:
        return
    print(n)
    tree(n-1)
    tree(n-2)
tree(3)


def nest(n):
    if n>=10:
        return n-1
    return nest(nest(n+2))
print(nest(5))






























