# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file using notepad extension (.txt)

### Step 2: 
 Open the file in read mode. 

### Step 3: 
Read the file and split it. Store the data in any variable. Words in the file will be stored as a list.

### Step 4:  
Print the variable to display contents of the file. 

### Step 5: 
Initialise variable count to 0. Run a for loop to count the number of elements in the list. 

### Step 6: 
End program.

## PROGRAM:
```
#Program to count number of words in a list.
#Developed by: Cynthia Mehul J
#RegisterNumber: 23009725

with open("MyFile.txt","r") as f:
    count=0
    s=f.read().split()
    print(s)
    for word in s:
        count+=1
    print("Number of words: ",count)
```

### OUTPUT:
![label](/Notepad%20count.jpg)

![label](/Program%20count.jpg)

![label](/Output%20count.jpg)

## RESULT:
Thus the program is written to find the word count from a text.
