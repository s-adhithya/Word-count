# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
Step 1: Open the file in read mode and handle it in text mode.
    

 Step 2: Read the text using read() function.
 
Step 3: Split the text using space separator. We assume that words in a sentence are separated by a space character.

 Step 4:  The length of the split list should equal the number of words in the text file.

 Step 5: You can refine the count by cleaning the string prior to splitting or validating the words after splitting.


 Step 6: Finally,print the number of words and display the output.

## PROGRAM:
## To write a program for getting the word count from a text.
## Developed by:Adhithya.S
## Registration number:22005823


```python
num_words=0
with open('testpro.txt','r') as file1:
    for i in file1:
        word=i.split()
        num_words +=len(word)
print("Number of words={}".format(num_words))

```

### OUTPUT:
![output](/OUTPUT.png)
![output](/OUTPUT2.png)




## RESULT:
Thus the program is written to find the word count from a text.
