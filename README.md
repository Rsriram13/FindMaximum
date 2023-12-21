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
Developed by: sriram R 
RegisterNumber:23004952 
'''
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large
    #Write your code here


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: sriram R
RegisterNumber: 23004952
'''
def max_marks(marks):
     large = max(marks)
     return large
     
    # write your code here


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: sriram R
RegisterNumber: 23004952
'''
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i>max:
            max =i
    return max
    # write your code here


```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
# To find the maximum of marks using the list method sort
![output](https://github.com/Rsriram13/FindMaximum/assets/145742823/45d7cbf5-5242-4414-ac34-e96fd4760bc1)


# To find the maximum marks using the list method max()
![output](https://github.com/Rsriram13/FindMaximum/assets/145742823/6b36e038-b04e-4957-83b8-a60a588ca6e7)


# To find the maximum marks without using builtin functions
![output](https://github.com/Rsriram13/FindMaximum/assets/145742823/a49481c2-0af2-457e-82b5-4578f1f394b0)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
