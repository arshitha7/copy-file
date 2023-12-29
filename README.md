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
Read the file and store in a variable
### Step 3: 
Now create a new file in which we want to paste the content using access mode.
### Step 4:  
Use write function to copy the read file that has been stored in the variable.
### Step 5: 
The content in the original file will be copied in the newfile
### Step 6: 
End the program
## PROGRAM:
```
#program to copy the content of one file to the other
#developed by:Arshitha MS
#register number: 212223241005
with open('pythonfile.txt') as f:
    with open("text1.txt",'w') as f1:
        for line in f:
            f1.write(line)
```
### OUTPUT:

![output](image-1.png)

![output1](image-2.png)

## RESULT:
Thus the program is written to copy the contents from one file to another file.