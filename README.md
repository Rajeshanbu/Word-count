# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
# Step 1:
Open visual studio code or jupyter lab.

# Step 2:
Create file with .py extension.

# Step 3:
Also create .txt file and input sentences.

# Step 4:
Write the code.

# Step 5:
Run the program.

# Step 6:
Print the values and end the program.

# PROGRAM:
```
## PROGRAM TO COUNT THE NUMBER OF WORDS
## DEVELOPED BY : Rajesh A
## REFERENCE NO : 22008551
```
```
num_words=0
with open('a.txt','r') as file1:
    for i in file1:
        word=i.split()
        num_words+=len(word)
print("Number of words= ",num_words)
```
# OUTPUT:
![c2d3beab-26ec-4f6c-9d7d-6bec37a573fe](https://user-images.githubusercontent.com/118924713/214756634-98972e74-5160-46be-be49-aca0612a5521.jpg)


# TEXT FILE
![1767521a-1495-4c40-bfe8-08d4ef920975](https://user-images.githubusercontent.com/118924713/214756613-b869e530-52ae-4fae-9e57-18406f0792df.jpg)


# RESULT:
Thus the program is written to find the word count from a text.
