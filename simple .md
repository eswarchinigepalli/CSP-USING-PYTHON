PROBLEM STATEMENT-1

num=int(input())
sum=0
while num!=0:
  digit=num%10
  sum+=digit
  num//=10
print(sum)
<img width="869" height="160" alt="image" src="https://github.com/user-attachments/assets/6a20454d-6d41-4bca-92c0-7b37d2d377ea" />

PROBLEM STATEMENT-2

list=map(int,input().split(' '))
sum=0
for i in list:
  sum=sum+i
print(sum)
<img width="868" height="160" alt="image" src="https://github.com/user-attachments/assets/e85e3521-d762-42af-8ca7-0839f1fa6a84" />


PROBLEM STATEMENT-3

arr1  = list(map(int,input().split(' ')))
arr2  = list(map(int,input().split(' ')))
def sum_arr(li1,li2):
    li1.extend(li2)
    print(li1) 
c = sum_arr(arr1,arr2)
<img width="864" height="169" alt="image" src="https://github.com/user-attachments/assets/347f99bf-f434-45da-a7e1-d28ba7e1d506" />


PROBLEM STATEMENT-4

n=int(input())
fact=1
for i in range(1,n+1):
  fact=fact*i
print(fact)
<img width="872" height="176" alt="image" src="https://github.com/user-attachments/assets/5d8f312e-d25f-43f9-8166-d63a38e632b7" />


PROBLEM STATEMENT-5

n=int(input())
l=len(str(n))
temp=n
sum=0
while(n>0):
  rem=n%10
  sum=sum+pow(rem,l)
  n//=10
if(temp==sum):
  print("Amstrong")
else:
  print("not a amstrong")
<img width="879" height="186" alt="image" src="https://github.com/user-attachments/assets/c3f5cedf-9781-4127-b48b-6ab2b6ee1251" />

