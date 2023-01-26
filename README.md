# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Use open function to open the file in which we want to copy from and access it in read mode.

### Step 2: 
Read the file and store in a variable.


 
### Step 3: 
Now create a new file in which we want to paste the content using write access mode

### Step 4: 
Use write function to copy the read file that has been stored in the variable.

### Step 5:
The content in the original file will be copied in the new file.

### Step 6: 
End the program.

## PROGRAM:
```python
# Developed By: Gumma Dileep Kumar
# Reference number: 22007129
with open("copy.txt", "r") as firstfile:
    with open("text.txt", "a") as secondfile:
        for line in firstfile:
            secondfile.write(line)
```            

### OUTPUT
![count3 1_output](https://user-images.githubusercontent.com/118707761/214807030-9e78f0b1-eaa0-4945-a154-11f684e01f1c.png)
![count3 2_output](https://user-images.githubusercontent.com/118707761/214807095-effdf993-a214-459d-9467-8bcff5bcebcc.png)

:





## RESULT:
Thus the program is written to copy the contents from one file to another file.
