# EX-6 Find the maximum of a list of numbers
# Date:
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
```
i)	 To find the maximum of marks using the list method sort.


def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large



ii)	 To find the maximum marks using the list method max().


def max_marks(marks):
    large = max(marks)
    return large



iii)  To find the maximum marks without using builtin functions.

def max_marks(marks):
    large = max(marks)
    return large



```



## Output:
![Screenshot 2024-10-15 180209](https://github.com/user-attachments/assets/e443f1ca-6d2b-4651-b307-485845b7be7e)

![Screenshot 2024-10-15 180227](https://github.com/user-attachments/assets/2ed839cb-6ff4-4a5b-a756-ac4d0126b768)

![Screenshot 2024-10-15 180242](https://github.com/user-attachments/assets/ed1ebbc7-2c4b-4bcf-87b7-bd1d41d6f7dc)




## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
