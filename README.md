# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
create another text file to copy
### Step 2: 
 now open both file using with open()
### Step 3: 
now read the file and the write on another file using read() and write()
### Step 4:  
now excuete the program
### Step 5: 
now check the another file to see its copied

## PROGRAM:
```
#Python program for copying the contents from one file to another file
#Developed by : Allen Joveth P
#Register Number : 23009582

def copy(fname,newfile):
    with open(fname,'r') as fp:
        with open(newfile,'w') as fp1:
            data1=fp.read()
            fp1.write(data1)
fname=input("Enter an existing file: ")
newfile=input("Enter a name for new file: ")
copy(fname,newfile)
```
### OUTPUT:

![Screenshot 2024-01-03 192447](https://github.com/allenjoveth/copy-file/assets/139422287/6a8eb2f7-8d72-40b9-865a-8dc1ab251c9e)


# Existing file

![Screenshot 2024-01-03 192553](https://github.com/allenjoveth/copy-file/assets/139422287/a7bbfebb-3ef3-4e03-be07-83f9d689832d)

# New file

![Screenshot 2024-01-03 192650](https://github.com/allenjoveth/copy-file/assets/139422287/885cb1e4-3b62-48c8-98a0-c62ab0df1fa2)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
