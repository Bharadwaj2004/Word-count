# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Define the variable to count the number of words in the file and defined with 0.
### Step 2: 
Open the text file using the with open keyword.
### Step 3: 
Using r command i.e:read mode.
### Step 4:  
Using for loop iterate the file to split the space in the words.
### Step 5: 
The splited and stored in the variable, use len() function of the splited word variable.
### Step 6: 
End the program.
## PROGRAM:
```python
# Developed By: B.venkata Bhadajwaj 
# Reference number: 22003979
num_words=0
with open('text.txt','r') as f1:         
    for i in f1:
        word=i.split()
        num_words+=len(word)
print("Number of words in a file = {}".format(num_words))
```
### OUTPUT:
![WhatsApp Image 2023-01-26 at 2 54 10 PM](https://user-images.githubusercontent.com/119560345/214804045-4f208b45-bafd-449b-91c4-ec7f59ac6b0f.jpeg)

## RESULT:
Thus the program is written to find the word count from a text.
