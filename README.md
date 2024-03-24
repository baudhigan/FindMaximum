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
![Python Ex 6(1)](https://github.com/baudhigan/FindMaximum/assets/151921158/77c5ef12-a398-4ed3-a660-f88290d3100f)
![Python Ex 6(2)](https://github.com/baudhigan/FindMaximum/assets/151921158/2a5945c9-67c5-42ff-a72c-c14b476f2b29)
![Python Ex 6(3)](https://github.com/baudhigan/FindMaximum/assets/151921158/1cb4409e-bcb9-431a-a06d-a07d276c941b)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
