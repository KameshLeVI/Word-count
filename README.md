# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1 :  
Define the variable to count the number of words in the file and defined with 0.

### Step 2:
  Open the text file using the open keyword.
 
### Step 3:
  Using r command i.e:read mode.

### Step 4: 
 Using for loop to iterate file to split the space in the words.

### Step 5:
 It is splitted and stored in the variable,Use len() function of the splitted word variable

### Step 6:
 End the Program

## PROGRAM:
```
#Developed by = Kamesh D 
#Reference no =22005358 
#To write a program for getting the word count from a file...

num = 0
with open('MyFile.txt','r') as f1:
  for i in f1:
    word =i.split()
    num += len(word)
print("NUMBER OF WORDS =",format(num))

```

### OUTPUT:
![](/1%20w.png)
![](/2w.png)


## RESULT:
Thus the program is written to find the word count from a text.
