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

Developed by: BAUDHIGAN D
RegisterNumber: 212223230028

i)	# To find the maximum of marks using the list method sort.
```Python
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    large = max(marks)
    return large

```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max

```



## Output:
![image](https://github.com/baudhigan/FindMaximum/assets/151921158/931c639c-37d1-4bb8-8803-fdff127cd44c)
![image](https://github.com/baudhigan/FindMaximum/assets/151921158/27d6ca6e-7663-46c4-9992-8e8d52be9866)
![image](https://github.com/baudhigan/FindMaximum/assets/151921158/41568f2f-0397-4df8-85aa-508ad8d4bba9)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
