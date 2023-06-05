# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 

# Step 1:
Open the first file in read mode

# Step 2:
Open the second file in append mode

# Step 3:
Every word in first file is copied to second file using write()

# Step 4:
close the first file

# Step 5:
close the second file

## PROGRAM:
```
python program for copying the contents from one file to another file.

Developed by:KANCHARLA NARMADHA

RegisterNumber: 212222110016

f1=open("sample1.txt","r")
f2=open("sample2.txt","a")
for line in f1:
    f2.write(line)
f1.close()
f2.close()
```

### OUTPUT:

![YTH OUTPUT 5C](https://github.com/kancharlaNarmadha/copy-file/assets/119559316/6824f166-f7aa-42a8-abaa-fde6104133eb)

![PYTH OUTPUT 5C 2](https://github.com/kancharlaNarmadha/copy-file/assets/119559316/cdd1c289-5a31-4db6-bc74-0965282033ed)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
