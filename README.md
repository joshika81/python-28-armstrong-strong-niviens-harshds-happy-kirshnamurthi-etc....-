n=153
t=n
s=0
c=len(str(n))
while n>0:
  d=n%10
  e=d**c
  s+=e
  n=n//10
if t==s:
  print(f"{t}  number is armstrong number")
else :
  print(f"{t} number is not armstrong number")
'''''''''output''''''''''''''''''
  153  number is armstrong number


  n=200
t=n
s=0
c=len(str(n))
while n>0:
  d=n%10
  e=d**c
  s+=e
  n=n//10
if t==s:
  print(f"{t}  number is armstrong number")
else :
  print(f"{t} number is not armstrong number")
  '''''output'''''''''''''
  200 number is not armstrong number



  # niven's/harshad
n=int(input("enter a number"))
temp=n
sum=0
while n>0:
    d=n%10
    sum+=d
    n=n//10
if temp%sum==0:
    print("given number is harshad")
else:
    print("given number is not harshad")
''''''''''output'''''''''''
enter a number 346
given number is not harshad

enter a number 156
given number is harshad

#for loop
for i in  range (1,21):
    print(i)
'''''''''''output''''''''''''''
1
2
3
4
5
6
7
8
9
10
11
12
13
14
15
16
17
18
19
20


for i in  range (1,21):
    print(i,end='')
''''''output''''''''''
1234567891011121314151617181920



for i in  range (1,21):
    print(i,end=' ')
''''''output''''''''''
    1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18 19 20 


j=['joshika','sravya','jyotjika']
for i in j:
    print(j)
''''''output''''''''''
'joshika', 'sravya', 'jyotjika']
['joshika', 'sravya', 'jyotjika']
['joshika', 'sravya', 'jyotjika']


j=['joshika','sravya','jyotjika']
for i in j:
    print(i)
 ''''''output''''''''''
 joshika
sravya
jyotjika


for i in range(10,0,-1):
    print(i)
''''''output''''''''''
10
9
8
7
6
5
4
3
2
1

for i in range(10,-1,-1):
    print(i,end=' ')
 ''''''output''''''''''
 10 9 8 7 6 5 4 3 2 1 0


 '''write a program to print sum of all the squares of numbers
square of 1 is 1
square of 2 is 4
square of 3 is 9
.
.
.
square of 10 is 100'''
for i in range(1,11):
    s=i*i
    print(f"square of {i} is {s}")




'''write a program to print sum of all the squares of numbers
square of 1 is 1
square of 2 is 4
square of 3 is 9
.
.
.
square of 10 is 100'''
for i in range(1,11):
    s=i*i
    print(f"square of {i} is {s}")
''''''output''''''''''       
square of 1 is 1
square of 2 is 4
square of 3 is 9
square of 4 is 16
square of 5 is 25
square of 6 is 36
square of 7 is 49
square of 8 is 64
square of 9 is 81
square of 10 is 100    
    



n=20
for i in range(1,11):
    print(f"{n}*{i}={n*i}")
''''''output''''''''''

20*1=20
20*2=40
20*3=60
20*4=80
20*5=100
20*6=120
20*7=140
20*8=160
20*9=180
20*10=200

word='sravya'
for i in word:
    print(word[2])
''''''output''''''''''  
a
a
a
a
a
a  
