# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text file in a specific loaction of interest.
### Step 2:
On the same location as the text file, create a python program file.
### Step 3: 
In python Program, import sys and open a text file with argument "sys.argv[1]"
### Step 4: 
using read() and split(), split the lines in the file into a sequence of words
### Step 5:  
using len() count the number of words in the text file
### Step 6: 
In command prompt, initiate python followed by program name and text file name to get the output
## PROGRAM:
```
#python program for getting the word count from the contents of a file using command line arguments.
#Developed by:Bhuvanesh.S.R
#Register number:212223240017
import sys
fp=open(sys.argv[0])
data=fp.read()
words=data.split()
print("no of words",len(words))
```
## OUTPUT:
![5b1](https://github.com/Bhuvanesh-Suresh/command-line-arguments-to-count-word/assets/145742661/cb47f1ff-8b83-4409-94f0-73218f3ada30)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
