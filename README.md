# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys package


### Step 2: 
 Create an empty dictionary
### Step 3: 
Open the text file in read mode
### Step 4:  
Split words in each line and store in list
### Step 5: 
count the number of occurence of each word in the list
### Step 6: 
Store the count of each word in dictionary
### step 7:
print the dictionary close the file
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
