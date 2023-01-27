# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

### Step 2: 
 
### Step 3: 

### Step 4:  

### Step 5: 

### Step 6: 

## PROGRAM:
```
Program for getting the word count from the contents of a file using command line arguments.
Developed By: S.IYYANAR
reference number: 22009120
import sys
d={}
f=open(sys.argv[1],"r")
for line in f:
    l=line.split(" ")
    for word in l:
        if word not in d:
            d[word]=1
        else:
            d[word]+=1
print(d)
f.close()
```
### OUTPUT:
![OUTPUT](./command%20line%20argument%20output%201.png)
![OUTPUT](./command%20line%20argument%20output%202.png)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
