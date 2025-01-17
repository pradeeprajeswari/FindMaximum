# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## STEP1:
Get the list of marks as input

## STEP2:
Use the sort() function or max() function or use the for loop to find the maximum mark.

## STEP3:
Return the maximum value.

## Program:

i)	# To find the maximum of marks using the list method sort.
```
Program to mark the maximum of marks using the list method sort
Developed by: pradeep.E
RegisterNumber: 23013416

def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```
Program to find the maximum marks using the list method max().
Developed by: pradeep.E
RegisterNumber:23013416 

def max_marks(marks):
    large=max(marks)
    return large

```

iii) # To find the maximum marks without using builtin functions.
```
Program to the maximum marks without using builtin functions.
Developed by: pradeep.E
RegisterNumber: 23013416

def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max
    
```
## Sample Input and Output
![output](./img/max_mar

## Output:
![list method sort](https://github.com/pradeeprajeswari/FindMaximum/assets/145743112/69fa75de-593b-4c78-be10-dfc2d345dc2b)

![listmethodmax](https://github.com/pradeeprajeswari/FindMaximum/assets/145743112/548e7f50-15bd-4c9f-a5e0-805bf161b28d)

![buildinfunction](https://github.com/pradeeprajeswari/FindMaximum/assets/145743112/eb5ed9d3-3d9c-43a0-b6e2-b8c4d04a904a)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
