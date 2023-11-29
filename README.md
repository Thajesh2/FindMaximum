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
Program to mark the maximum of marks using the list method sort
Developed by: Thajesh k
RegisterNumber: 23004042

def max_marks(marks):
   marks.sort()
   b=marks[-1]
   return b


```

ii)	# To find the maximum marks using the list method max().
```
Program to find the maximum marks using the list method max().
Developed by:  Thajesh k
RegisterNumber: 23004042

def max_marks(marks):
    a=max(marks)
    return a



```

iii) # To find the maximum marks without using builtin functions.
```

Program to the maximum marks without using builtin functions.
Developed by: Thajesh k
RegisterNumber: 23004042

def max_marks(list1):
   for i in list1:
       if i>94:
           return i

```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:

![image](https://github.com/Thajesh2/FindMaximum/assets/139841959/880fdad5-0e24-4ad2-8ff2-41e68ed13af1)


![image](https://github.com/Thajesh2/FindMaximum/assets/139841959/09203aef-9d4a-4bf0-b502-570e9a559521)


![image](https://github.com/Thajesh2/FindMaximum/assets/139841959/6e2935b6-03c9-49e5-870a-f843019c14dd)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
