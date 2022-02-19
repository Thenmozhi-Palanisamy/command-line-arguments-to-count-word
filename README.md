# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import the sys module

### Step 2: 
pass the file name as the argument after the name of the script open the file as sys.arggv[1]
 
### Step 3: 
read the file using read()method

### Step 4:  
use spilt() method to split the filr content into words

### Step 5: 
use len() method to fi nd the total words

### Step 6: 
run the program to determine the number of words in the file

## PROGRAM:
import sys 
count=0
with open(sys.argv[0],'r') as f:
    for line in f: 
        word = line.split() 
        count += len(word)
print("Word count in File = ",count)

### OUTPUT:
![output](.//co.png)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
