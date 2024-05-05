# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Define a function which will count the word in the given file.
### Step 2: 
Create a file pointer and open the file.
### Step 3: 
Initialize word count as zero.
### Step 4:  
For each line in file, split it into words and find number of the words in every line.
### Step 5: 
Sum the number of words in each line.
### Step 6: 
Display the total words in the file.
### Step 7:
Close the file pointer and end the program.
## PROGRAM:
```
Developed by: KAMALESHWAR KV
Register no: 212223240063
```
```py
def wordcount(filename):
    fp=open(filename)
    wordcount=0
    for i in fp:
        words=i.split()
        wordcount+=len(words)
    print("Total no of words in file is",wordcount)
    fp.close()
wordcount(input("Enter a filename in current directory or specify it with full path:"))
```
### OUTPUT:
![image](https://github.com/Kamaleshwa/Word-Count/assets/144980199/fe09e834-0511-4e3e-b808-2688b4fb3742)


## RESULT:
Thus the program is written to find the word count from a text.
