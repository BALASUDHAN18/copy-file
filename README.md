# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1:
Create a text1.txt with some content in it

Step 2:
Open the text1.txt file in read mode

Step 3:
Create a copy.txt file using write mode

Step 4:
Copy the content of text1.txt file to copy.txt using write function

## PROGRAM:
```
''' 
Program for copying the contents from one file to another file
Developed by: BALASUDHAN P
RegisterNumber: 212222240017
'''
with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:

![242934589-5bf4d1fe-20b9-4de7-8112-56906bfcd6c9](https://github.com/BALASUDHAN18/copy-file/assets/118807740/845b214a-be54-426b-8d5c-afeba9ab7fb7)

![242934606-04f71081-3a7a-4b9a-8ba8-963bf12e5a41](https://github.com/BALASUDHAN18/copy-file/assets/118807740/9174149c-4bb2-43df-977d-291983cf8a62)

![242934629-7d6c2631-bc40-4a40-9e1d-a27eb01fdeca](https://github.com/BALASUDHAN18/copy-file/assets/118807740/d80e69dd-1938-4883-a51e-9053bdf7bd03)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
