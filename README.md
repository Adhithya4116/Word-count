# Word-count
## AIM:
To write a python program for getting the word count from a text.

## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7

## ALGORITHM: 
### Step 1:
Create a file and add some content into it.
### Step 2: 
 Open file using with keyword/built-in function in read mode.
### Step 3: 
Use read() to read the contents of the file.
### Step 4:  
Split the lines using split().
### Step 5: 
Iterate the list and increment the count
### Step 6: 
Print the output.

## PROGRAM:
To write a program for getting the word count from a file.
Developed by: adhithya perumal
RegisterNumber: 22008747

def wordcount():
    cnt = 0
    with open("MyFile.txt","r") as fp:
        data = fp.read()
        for line in data.split():
            cnt += 1
    print("The number of words in the given file is:",cnt)
wordcount()

### OUTPUT:
![myfile](https://user-images.githubusercontent.com/118707079/215266389-44ad5a4c-7e6d-42a6-b0a6-ec37c47d03b1.png)


## RESULT:
Thus the program is written to find the word count from a text.
