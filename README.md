# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Start the program

### Step 2: 
Create a file story.txt in anacoda navigator
 
### Step 3: 
Write a program to count

### Step 4:  
Run the program

### Step 5: 
Print the output

### Step 6: 
End the program

## PROGRAM:
```
program to find the number of words in a text file
Developed by : SANDHIYA R
Register number : 212223240146

num=0
with open("story.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words are in the file is ",num)
```
### OUTPUT:

![image](https://github.com/SandhiyaRajagopal/Word-Count/assets/144870852/891fe6cc-50ae-4031-a467-2dcd4cfbe4c9)


## RESULT:
Thus the program is written to find the word count from a text.
