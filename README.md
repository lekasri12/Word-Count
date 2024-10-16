# DATE
# EX-09 Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a new text file
### Step 2:
Add some sentence to the file
### Step 3:
Now in the main.py file using split function,split the words in the .txtfile
### Step 4:
Count the splitted Words
### Step 5:
Add the counted number in the variable
### Step 6:
Run the program and display the results


## PROGRAM:
```
#Program to find the number of words in a text file
#Developed by : G LEKASRI
#Register number : 212223100025
count=0
with open("story.txt","r") as f1:
    for i in f1:
        word=i.split()
        count += len(word)
print("The number of words are in the file is ",count)
```
### OUTPUT:

![Screenshot 2024-10-16 081507](https://github.com/user-attachments/assets/7c8dfcb4-647f-4a7d-a641-52112a08a35c)
![Screenshot 2024-10-16 081527](https://github.com/user-attachments/assets/9b6eb650-6d92-4b5d-bca4-5faff5f966f8)


## RESULT:
Thus the program is written to find the word count from a text.
