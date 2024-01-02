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
initially make count = 0 

### Step 3:
open the content file using command line arguments.

### Step 4:
by using for loop name the function as "line"

### Step 5:
split the line using .split

### Step 6:
Running the program

## PROGRAM:
```python
'''
Program for getting the word count from the contents of a file using command line arguments
Developed by: N.Neethiventhan
RegisterNumber: 212223100038
'''
import sys
fp=open(sys.argv[1],'r')
count=0
for line in fp:
    words=line.split()
    count+=len(words)
print("Number of words in a file",count)
```

### OUTPUT:
![image](https://github.com/Neethiventhan123/command-line-arguments-to-count-word/assets/148514848/27e12b77-5108-42af-b60c-44a74562c589)




## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
