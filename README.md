# 19CS301Module8
EXPTNO.8a Program to find Find the simple interest

### Aim: 
To Write a Python Program to find Find the simple interest by getting the principal, rate and time value from the user

### Algorithm:

STEP 1: Start.

STEP 2: Define a function.

STEP 3: Create variable 'p','r','t' for principal,rate of interest and time. STEP 4: Get the input of p,r and t from user.

STEP 5 : Using the formula (p*r*t)/100 calculate the result. STEP 6: Print the result.

STEP 7: Stop.

### Program:
```
Reg no-212223070007
Name-Gopinath G

def simpleInterest(p,t,r):
      si = p*t*r/100
       return si
p = eval(input())
r = eval(input())
t = eval(input())
```
### Output:
![image](https://github.com/user-attachments/assets/0cc71222-9697-4545-a937-b330407cbc02)

### Result: 
Thus the Python Program to find Find the simple interest by getting the principal, rate and time value from the user
was executed successfully .



EXPTNo.8b program to display elements from a list, present at odd index positions

### Aim: 
To Write a python program to display elements from a list, present at odd index positions

### Algorithm:

STEP 1: Start.

STEP 2: Define a function.

STEP 3: Create a list and a variable a.

STEP 4: Get the input of a from user.

STEP 5 : Using loop get the inputs and append in list.

STEP 6: Using another loop print the elements in the odd index position of the list. 

STEP 7: Stop.

### Program:
```
Reg no-212223070007
Name-Gopinath G 


def odd(a):
         l=[]
          for i in range(a):
x = int(input())
l.append(x)
for i in range(a):
           if i%2!=0:
                print(l[i], end=" ")
 a = int(input())
odd(a)

```
### Output:
![image](https://github.com/user-attachments/assets/a13fba7c-36b5-4227-98c1-82ab22a7804a)

### Result: 
Thus the python program to display elements from a list, present at odd index positions was executed successfully .
 

EXPT NO>8C 
### Aim: 
To Write a python program to Given the participants' score sheet for your University Sports Day, you are required to find the runner-up score. You are given scores. Store them 

### Algorithm:
STEP 1: Start.

STEP 2: Create a variable n.

STEP 3: Get the value of n from user.

STEP 4: Get the number of inputs from user and split the input and append in a list. STEP 5: Using set function remove duplicates from the list.

STEP 6: Using sort function reorder the list in ascending order. STEP 7: Print the result.

STEP 8: Stop.


### Program:
```
Reg no-212223070007
Name-Gopinath G

if  name	== '   main    ':
          n = int(input())
          arr = map(int, input().split())
          arr2 = list(set(arr))
          arr2.sort()
print(arr2[-2])
```
### Output:
 
![image](https://github.com/user-attachments/assets/032939c0-f500-4bbb-9b19-87b3c54d8454)

 

### Result: 
Thus the python program to Given the participants' score sheet for your University Sports Day, you are required to find the runner-up score. You are given scores. Store them was executed successfully .
 


EX: 8.d program to square all the even numbers and cube all odd numbers from a list of integers
### Aim: 
To Develop a python program to square all the even numbers and cube all odd numbers from a list of integers. Get the starting and ending range to create a list.


### Algorithm:

STEP 1: Start.

STEP 2: Create a variable f and l for upper and lower limit of list. STEP 3: Get the value of f and l from user.

STEP 4: Create a list.

STEP 5 : Get the input from user and append in the list. STEP 6: Create a lambda function to calculate the result. STEP 7: Print the result.

STEP 8 : Stop.

### Program:
```
Reg no-212223070007
Name-Gopinath G

cube = lambda x: x**2 if x%2==0 else x**3
def fun(f,l):
     l1=[]
     for i in range(f,l+1):
           l1.append(i)
      return l1
f,l = int(input()),int(input())

```
### Output:
![image](https://github.com/user-attachments/assets/4a9076d8-a2cf-44e1-b7d1-e638b7edf12f)


### Result: 
Thus the python program to square all the even numbers and cube all odd numbers from a list of integers. Get the starting and ending range to create a list.
was executed successfully .


 EX: 8.e print the sentence by reversing
 
### Aim:
The included code stub will read a sentence, , from STDIN.

Ti[ry to print the sentence by reversing each word in sentence

### Algorithm:

1. **Read a sentence** from the user.
2. **Split** the sentence into words.
3. **For each word** in the list:

   * Reverse the word.
   * Print the reversed word with a space.


### Program:
```
Reg no-212223070007
Name-Gopinath G

n=input().split()
for i in n:
    print(i[::-1],end=" ")


```
### Output:
![image](https://github.com/user-attachments/assets/e8d90635-aa1f-4824-8b5a-ba2f7a2506dd)


### Result
Thus thw included code stub will read a sentence, , from STDIN was executed successfully



