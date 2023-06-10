# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:Create a text1.txt with some content in it

### Step 2: Open the text1.txt file in read mode
 
### Step 3: Create a copy.txt file using write mode

### Step 4: Copy the content of text1.txt file to copy.txt using write function 


## PROGRAM:
''' 
Program for copying the contents from one file to another file

Developed by:S.ANUSHARON

RegisterNumber: 212222240010
'''
with open("text2.txt", 'r')as fp:

    msg1=fp.read()
with open("copytxt",'w')as fp1:

    fp1.write(msg1)

### OUTPUT:

![Screenshot (271)](https://github.com/Anusharonselva/copy-file/assets/119405600/33182cc6-7b2a-4ff0-a63b-626250d68ab9)

![-1](https://github.com/Anusharonselva/copy-file/assets/119405600/58d4db6d-f567-4533-b62d-ee357e5b5d86)

![Screenshot (272)](https://github.com/Anusharonselva/copy-file/assets/119405600/a1f45a0c-26c4-4bc4-89ec-e30dd3d92e62)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
