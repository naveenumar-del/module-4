File Handling in Python: Count Lines Not Starting with 'T'

🎯 Aim

To write a Python program that counts the number of lines in a text file story.txt that do not start with the alphabet 'T'.


🧠 Algorithm

Open the file story.txt in read mode.

Initialize a counter count to zero.

Iterate through each line of the file:

Check if the first character of the line is not 'T'.

If the line does not start with 'T', increment the count by 1.

After processing all lines, print the count value, which represents the number of lines that do not start with 'T'.

🧾 Program

Add code here

f = open("story.txt", "r")

count = 0

for line in f:

    if not line.startswith('T'):
    
        count += 1

f.close()

print(count)

Output

<img width="1024" height="256" alt="image" src="https://github.com/user-attachments/assets/143d831e-1bd9-4194-817c-1710fdd837fb" />


Result

Thus,the program has been executed successfully.
