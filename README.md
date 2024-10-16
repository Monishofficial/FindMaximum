## DATE: 
## Ex NO 6: Find the maximum of a list of numbers
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
# DVELOPED BY: MONISH N
# REGISTER NUMBER: 212223240097
def max_marks(marks):
    marks.sort()
    return marks[-1]
```


ii)	# To find the maximum marks using the list method max().
```
# DVELOPED BY: MONISH N
# REGISTER NUMBER: 212223240097
def max_marks(marks):
    return max(marks)
```

iii) # To find the maximum marks without using builtin functions.
```
# DVELOPED BY: MONISH N
# REGISTER NUMBER: 212223240097
def max_marks(marks):
    max_mark = marks[0]
    for mark in marks:
        if mark > max_mark:
            max_mark = mark
    return max_mark
```

## Output:
### i)
![Screenshot 2024-10-16 084216](https://github.com/user-attachments/assets/f97416ec-ca2b-49a4-b727-041e6036f19d)

### ii)
![Screenshot 2024-10-16 084216](https://github.com/user-attachments/assets/082e1c85-e94f-4845-ac14-0e6903dd3458)

### iii)
![Screenshot 2024-10-16 084453](https://github.com/user-attachments/assets/3daeaaec-7082-4eb0-862b-cd9b7bd72783)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
