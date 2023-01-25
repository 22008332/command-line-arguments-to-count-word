# command-line-arguments-to-count-word

## AIM:

To write a python program for getting the word count from the contents of a file using command line arguments.

## EQUIPEMENT'S REQUIRED: 

PC
Anaconda - Python 3.7

## ALGORITHM: 

### Step 1:
import sys from the package.

### Step 2: 
start the value from 0 to count.
 
### Step 3: 
Use the sys.argvfunction to open the file.

### Step 4: 
Start the loop to count the number of words.

### Step 5: 
Print the required statements.

### Step 6: 
Print the result.

## PROGRAM:
```python
#Developed by:Preethi.A.A
#Reference no:22008332
import sys
count = 0
with open(sys.argv[1],'r') as f:
    for line in f:
        word=line.split()
        count+=len(word)
print("word Count in File =",count)
```

### OUTPUT:
![](command%20line.png)
![](command%20line%201.png)

## RESULT:

Thus the program is written to find the word count from the contents of a file using command line arguments.
