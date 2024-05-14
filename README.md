# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1:
Create a text file with some content in it.

## Step 2:
Open the created text file.

### Step 3:
Create another empty text file.

## Step 4:
Copy the content of text file to empty file using write function.

## PROGRAM:
```
Developed by: T. Gayathri
Reg No: 212223100007

with open("write.txt",'r') as file1:
    msg=file1.read()
with open("copy.txt",'w') as file2:
    file2.write(msg)
```

### OUTPUT:
![Screenshot 2024-05-14 180624](https://github.com/gayumee/Copy-File/assets/149037327/52f8cb56-6007-4587-87de-f04d59cd0b5a)

![Screenshot 2024-05-14 180635](https://github.com/gayumee/Copy-File/assets/149037327/aa7a1627-0502-48d7-9f88-d87c85da18b2)

![Screenshot 2024-05-14 180642](https://github.com/gayumee/Copy-File/assets/149037327/cab89bd5-eb57-4d4a-80c8-0226d440afe1)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
