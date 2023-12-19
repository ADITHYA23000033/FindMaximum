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
Developed by: ADITHYA V
RegisterNumber: 23000033
'''
def max_marks(marks):
    marks.sort()
    return marks[-1]



```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: ADITHYA V
RegisterNumber: 23000033
'''
def max_marks(marks):
    max(marks)
    return max(marks)



```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: ADITHYA V
RegisterNumber: 23000033
'''
def max_marks(list1):
    highest=list1[0]
    for i in range(1,len(list1)):
        if list1[i]>highest:
            highest=list1[i]
    return highest



```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
## 1. To find the maximum of marks using the list method sort.
![image](https://github.com/ADITHYA23000033/FindMaximum/assets/148514544/1522c192-5e13-4372-9bc3-3e20b0f9eda2)
## 2. To find the maximum marks using the list method max().
![image](https://github.com/ADITHYA23000033/FindMaximum/assets/148514544/0f6ef5c9-5bb2-47d9-9526-40d55282eb7d)
## 3. To find the maximum marks without using builtin functions.
![image](https://github.com/ADITHYA23000033/FindMaximum/assets/148514544/e94131d0-f721-4c93-b66a-3a7b2c08c0e8)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
