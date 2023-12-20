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
```
''' 
Program to mark the maximum of marks using the list method sort
Developed by: OVIYA P
RegisterNumber: 23013207
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: OVIYA P
RegisterNumber: 23013207
'''
def max_marks(marks):
    large=max(marks)
    return large

```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: 
RegisterNumber: 
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large

```
## Output:
#output for find the maximum of numbers using list method sort.

![image](https://github.com/Oviya24032K6/FindMaximum/assets/147139999/7fb80847-405a-4478-a9dd-e0810a506bed)


#output for find the maximum of numbers using list method max().

![image](https://github.com/Oviya24032K6/FindMaximum/assets/147139999/70179370-bcd9-42b6-9719-71429e8bdc9a)

#output for find the maximum of numbers using buitin function.

![image](https://github.com/Oviya24032K6/FindMaximum/assets/147139999/87a31e38-b1ba-4203-8659-9616a5a33221)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
