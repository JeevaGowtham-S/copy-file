# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1:

First we need to open the required file form which we need to copy the text.

Again using the with keyword to open the empty file.
## Step 2:

Using keyword "with" to open the requied file.
## Step 3:

Again using the with keyword to open the empty file.
## Step 4:

The empty file is open by using 'W' which is used to write only.
## Step 5:

The four function is used to take each line from the main file.
## Step 6:

The four function is used to take each line from the main file.
## PROGRAM:
```
#Developed by: JEEVA GOWTHAM S
#Reference no: 22008760
with open('file.txt','r') as f1:
    with open('file2.txt','a') as f2:
        for line in f1:
            f2.write(line)
 ```
### OUTPUT:
![Screenshot from 2023-01-26 16-45-32](https://user-images.githubusercontent.com/118042624/214824319-4476a378-1a53-4b9e-89f8-242016f1401a.png)

![Screenshot from 2023-01-26 16-54-55](https://user-images.githubusercontent.com/118042624/214824329-291c9708-72c2-4ebd-bc3a-5901c13b2ed6.png)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
