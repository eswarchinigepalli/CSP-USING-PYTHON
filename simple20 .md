PROBLEM STATEMENT-1
"""def sum_num(num):
    sum_n =0
    while(num!=0):
        rem = num%10
        sum_n = rem +sum_n
        num = num//10

    return sum_n
    
n = int(input())
c=   sum_num(n)   
print(c)
"""

PROBLEM STATEMENT-2
"""arr1  = list(map(int,input("Enter your elements").split(' ')))
def arr_sum(li):
    sum=0
    for i in range(0,len(li)):
        sum = sum + li[i]
    return sum
c= arr_sum(arr1)
print(c)"""

PROBLEM STATEMENT-3
"""arr1  = list(map(int,input("Enter your elements : ").split(' ')))
# print(arr1)
arr2  = list(map(int,input("Enter your elements : ").split(' ')))
# print(arr2)"""
"""def sum_arr(li1,li2):
    li1.extend(li2)
    print(li1) 
c = sum_arr(arr1,arr2)"""
"""def sum_arr(li1,li2):
    for i in range(0,len(li2)):
        li1.append(li2[i])
    print(li1)
c = sum_arr(arr1,arr2)"""

PROBLEM STATEMENT-4

"""num =int(input("Enter your number to get factorial "))
def facto(n):
    fact =1
    if n<0:
        return "factorial is not possible "
    elif n==0 or n==1:
        return fact
    else:
        fact = n* facto(n-1)
    return fact
c = facto(num)
print(c)"""

PROBLEM STATEMENT-5
"""num = int(input("Enter your number : "))
def arm_str(n):
    o_n = n
    c= len(str(n))

    sum_arm = 0

    while(n>0):
        
        rem = n%10
        sum_arm = sum_arm + rem ** c
        n=n//10
    return sum_arm == o_n
if arm_str(num):
    print("armstrong")
else:
    print("not a arm strong ")"""

PROBLEM STATEMENT-6
"""num = int(input("Enter your number :"))
def cou_dig(n):
    count =0
    while(n>0):
        rem = n%10
        count+=1
        n=n//10
    return count
print(cou_dig(num))"""

PROBLEM STATEMENT-7
"""init_arr = list(map(int,input("Enter your elements :").split(' ')))
def app_ele(li1):
    app_arr = list(map(int,input("Enter your append elements ").split(' ')))
    for i in range(0,len(app_arr)):
        li1.append(app_arr[i])
    return li1
c = app_ele(init_arr)
print(c)"""

PROBLEM STATEMENT-8
"""arr1  = list(map(int,input("Enter your  1st array elements : ").split(' ')))
print(arr1)
arr2  = list(map(int,input("Enter your 2  array elements : ").split(' ')))
print(arr2)
def sort_arr(li1,li2):
    arr3 =li1[:]
    arr3.extend(li2)
    
    print(arr3)
    n = len(arr3)
    for i in range(n):
        for j in range(n-i-1):
            if arr3[j] > arr3[j+1]:
                arr3[j],arr3[j+1] = arr3[j+1],arr3[j]
    return arr3

c = sort_arr(arr1,arr2)
print(c)"""

PROBLEM STATEMENT-9
"""arr1  = list(map(int,input("Enter your  1st array elements : ").split(' ')))
arr2  = list(map(int,input("Enter your  1st array elements : ").split(' ')))
arr3  = list(map(int,input("Enter your  1st array elements : ").split(' ')))
def com_ele(li1,li2,li3):
    com_ele_arr=[]
    for i in li1:
        if i in li1 and i in li2 and i in li3  :
            com_ele_arr.append(i)
    return com_ele_arr

c =com_ele(arr1,arr2,arr3)
print(c)"""


PROBLEM STATEMENT-10
"""for i in range(1,100):
    if i%2 ==0:
        print(i)"""

"""def even_gen(l_l,u_l):
    for i in range(l_l,u_l):
        if i%2==0:
            print(i) 
l_lim = int(input("Enter your lower limit"))
u_lim = int(input("Enter your upper limit"))
c= even_gen(l_lim,u_lim)
print(c)"""


PROBLEM STATEMENT-11
"""num = int(input("Enter no of terms "))
def fibo(n):
    if n==1:
        return 0
    elif n==2:
        return 1
    else:
        return fibo(n-1) + fibo(n-2)
c = fibo(num)
print(c)"""

PROBLEM STATEMENT-12
# num1 = int(input("Enter your number one "))
# num2 = int(input("Enter your number two "))
"""def hcf(n1,n2):
    if n2==0:
        return n1
    if n1==0:
        return n2
    if n1 == n2:
        return n1
    if n1>n2:
        return hcf(n1-n2,n2)
    else:
        return hcf(n1,n2-n1)
    
c =hcf(num1,num2)
print(c)"""

PROBLEM STATEMENT-13
"""def hcf(n1,n2):
    if n2==0:
        return n1
    else:
        return hcf(n2,n1%n2)
def lcm(n1,n2):
    return (n1*n2)//hcf(n1,n2)
c = hcf(num1,num2)
print(c)
c1 = lcm(num1,num2)
print(c1)"""

PROBLEM STATEMENT-14
"""str1 = input("Enter yourr string ")
if str1[::] == str1[::-1]:
    print("Armstrong ")
else:
    print("Not a arm strong")"""

PROBLEM STATEMENT-15
"""str1 = list(input("Enter your string "))
set_1 = set()
for i in str1:
    set_1.add(i)
new_str = list(set_1)
new_str = ''.join(new_str)
print(new_str)"""

PROBLEM STATEMENT-16
"""num = int(input("Enter your number "))
def sum_dig(n):
    sum1=0
    while n!=0:
        rem = n % 10
        sum1 = sum1 + rem
        n = n//10
    return sum1
c =sum_dig(num) 
print(c)"""

PROBLEM STATEMENT-17
"""list_1 = list(map(int,input("Enter n elements of ").split(' ')))
def sort_l(li1):
    n=len(li1)
    for i in range(n):
        for j in range(n-i-1):
            if li1[j] > li1[j+1]:
                li1[j],li1[j+1] = li1[j+1] , li1[j]
    return li1
print(sort_l(list_1))"""

PROBLEM STATEMENT-18
"""list_1 = list(map(int,input("Enter n elements of ").split(' ')))
def sum_l(li):
    sum =0
    for i in range(len(list_1)):
        sum = sum+list_1[i]
    return sum
print(sum_l(list_1))"""

PROBLEM STATEMENT-19
"""name = input("Enter your name ")
def greet(name):
    return f"hello, happy birthday to you my dear {name} "
print(greet("varunmannam"))"""
    
PROBLEM STATEMENT-20
"""for i in range(10):
    print(i)"""
PROBLEM STATEMENT-21
"""def div_3(l_l,u_l):
    li =[]
    for i in range(l_l,u_l):
        if i%3 ==0:
            li.append(i)
    return li
print(div_3(10,200))"""
