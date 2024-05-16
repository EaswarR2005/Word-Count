# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Declare number of words is 0.
### Step 2: 
open it with file1.txt file.

### Step 3: 
Give range for i.

### Step 4:  
Then next split the words.

### Step 5: 
count the number of words.

### Step 6: 
Giving print statement for getting output.

## PROGRAM:
```
NAME: EASWAR R
REGISTER NUMBER: 212223230053

num=0
with open("C:/Users/BSS/Documents/words.txt","r") as f1:
   for i in f1:
     word=i.split()
     num += len(word)
print("The number of words are in the file is ",num)
```

### words.txt:
![Screenshot 2024-05-16 200337](https://github.com/EaswarR2005/Word-Count/assets/146931525/622b0123-2b22-4ab9-b0b5-3fec7988f32c)


### OUTPUT:
![image](https://github.com/EaswarR2005/Word-Count/assets/146931525/12064061-f0cd-4662-bcd8-5c3806494bfd)


## RESULT:
Thus the program is written to find the word count from a text.
