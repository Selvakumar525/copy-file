# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the first file in read mode
### Step 2: 
 Open the second file in append mode
### Step 3: 
Every word in first file is copied to second file using write()
### Step 4:  
close the first filepython program for copying the contents from one file to another file.
### Step 5: 
close the second file
```
## PROGRAM:
Developed by: SELVA KUMAR
RegisterNumber: 22009007
f1=open("sample1.txt","r")
f2=open("sample2.txt","a")
for line in f1:
    f2.write(line)
f1.close()
f2.close()
```

### OUTPUT:

![Screenshot_20230127_205139](https://user-images.githubusercontent.com/120643262/215122294-e539c1bb-5a40-4237-b171-8b5a159d6810.png)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
