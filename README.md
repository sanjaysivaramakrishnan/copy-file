# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: Create a function for the following operation

### Step 2: prompt the user to enter the two file one is source file another one storage file
 
### Step 3: Inside the function open the source file ann copy the contant in a variable 

### Step 4: Next open the empty file 

### Step 5: then store the contant in the empty file 

### Step 6: finally read the the new file and print that 

## PROGRAM:

# Python program for copying the contants from one to another <br>
# Developed by : Sanjay sivaramakrishnan M<br>
# Reference number : 23013798<br>
def function (file1,file2):   <br>
   with open(file1,'r') as san:<br>
          contant=san.read()<br>
   with open(file2,'a+') as copy:<br>
                 copy.write(contant)<br>
                 copy.seek(0)<br>
                 print(copy.read())<br>
print("Enter a source file you want to copy : ",end='')<br>
x= input()<br>
print("enter a file you to store the data : ",end='')<br>
y=input()<br>
function(x,y)<br>          
### OUTPUT:
![image](https://github.com/sanjaysivaramakrishnan/copy-file/assets/151629616/2bb35d56-a63c-4dbe-9476-8112c2e16ac2)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
