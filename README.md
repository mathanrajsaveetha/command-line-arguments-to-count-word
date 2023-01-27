# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import sys
### Step 2: 
 open file using open().
### Step 3: 
Use for loop.
### Step 4:  
Use len to count number of words
### Step 5: 
give print


## PROGRAM:
```
##Developed by : MATHAN RAJ E
##Register number :22008971

import sys

with open(sys.argv[1],'r') as f:
    num_words =0
    for i in f:
        word =i.split()
        num_words += len(word)
print("Number of words={}".format(num_words))
```
### OUTPUT:
![image](https://user-images.githubusercontent.com/119560501/214978727-598f51fa-4cbf-46c5-af7e-1d45e35251b3.png)
![image](https://user-images.githubusercontent.com/119560501/214978497-69e25e0d-6a5d-4e9c-a528-adb31dd7e4b0.png)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
