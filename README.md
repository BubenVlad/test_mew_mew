'''
a=int (input("Введіть число"))
while ( a!=0):
    a=int (input("Введіть число"))
print ( "The End")
'''

'''
import random
a=random.randint(1,6)
while ( a!=1):
    print (a)
    a=random.randint(1,6)
print ( "The End")
'''

'''
*
import random
a=random.randint(1,11)
while ( a!=11):
    print (a)
    a=random.randint(1,11)
print ( "The End")
'''

'''
import random
a=random.randint(1,100)
k=0
while ( a!=100):
    print (a, end= ' ')
    a=random.randint(1,100)
    k=k+1
print ("K=", k)
'''

'''
import random
a=random.randint(1,100)
k=0
n=0
while ( a!=100):
    print (a, end= ' ')
    if(a%2==0):
        k=k+1
    else:
        n=n+1
    a=random.randint(1,100)
print ("Парних=",k)
print ("Непарних=",n)
'''

'''
import random
a=random.randint(1,100)
k=0
n=0
s=0
while ( a!=100):
    s=s+a
    print (a,end=' ')
    if(a%2==0):
        k=k+1
    else:
        n=n+1
    a=random.randint(1,100)
s=s/(k+n)

print ("Парних=",k)
print ("Непарних=",n)
print ("Середнє=",s)
'''

import random
print("Я загадую число від 1 до 10")
a=random.randint(1,10)
print("Ваша версія=", end=' ')
b=int (input())
while (a!=b):
    if(a>b):
        print("Мало")
    else:
        print("Багато")
    print("Ваша версія=",end=' ')
    b=int(input())
print ("Вгадано!")



    
