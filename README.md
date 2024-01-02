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
Developed by: RAJKUMAR G
RegisterNumber: 23003498
'''
def max_marks(marks):
    #Write your code here
    marks.sort()
    large=marks[-1]
    return large


```

ii)	# To find the maximum marks using the list method max().
```Python

''' 
Program to find the maximum marks using the list method max().
Developed by: RAJKUMAR G
RegisterNumber: 23003498
'''
def max_marks(marks):
    # write your code here
    large = max(marks)
    return large

```

iii) # To find the maximum marks without using builtin functions.
```Python

''' 
Program to the maximum marks without using builtin functions.
Developed by: RAJKUMAR G
RegisterNumber:23003498 
'''
def max_marks(list1):
    # write your code here
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max

```

## Output:
![Screenshot 2024-01-02 125921](https://github.com/Rajkumar28072005/FindMaximum/assets/144980101/5c741157-c373-4a6b-b657-ebee0f05df25)
![Screenshot 2024-01-02 125952](https://github.com/Rajkumar28072005/FindMaximum/assets/144980101/f82d0ba7-bee7-44f5-8cf4-970af4e49660)
![Screenshot 2024-01-02 130008](https://github.com/Rajkumar28072005/FindMaximum/assets/144980101/2fd189d3-3257-4e26-86b5-6e9a15cbf171)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
