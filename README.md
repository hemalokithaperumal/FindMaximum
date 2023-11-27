# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```Python
''' 
Program to mark the maximum of marks using the list method sort
Developed by: HEMA LOKITHA P
RegisterNumber: 23007550
'''
def max_marks(marks):
   marks.sort()
   max=marks[-1]
   return max 
max_marks([88,67,96,45,63])



```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: HEMA LOKITHA P
RegisterNumber: 23007550
'''
def max_marks(list):
    max = list[0]
    for i in list:
        if i>max:
            max = i
    return max
max_marks([88, 67, 77, 93, 95, 11, 67, 89, 56, 89])
    


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: HEMA LOKITHA P
RegisterNumber: 23007550
'''
def max_marks(list1):
    max1=list1[0]
    for i in list1:
        if i>max1:
            max1=i
    return max1
max_marks([88, 67, 77, 93, 95, 11, 67, 89, 56, 89])


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![OUTPUT I](<Screenshot 2023-11-27 175252.png>)
![OUTPUT II](<Screenshot 2023-11-27 175350.png>)
![OUTPUT III](<Screenshot 2023-11-27 175419.png>)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.