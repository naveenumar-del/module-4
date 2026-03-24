Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:

Alphabetically by keys

Alphabetically by values

🎯 Aim

To write a Python program that sorts a dictionary's:


Keys in alphabetical order

Values in alphabetical order

🧠 Algorithm

Start the program.

Define a dictionary with key-value pairs.

Sort by Keys:

Use sorted(dictionary.items())

Convert the result to a dictionary using dict()

Sort by Values:

Use sorted(dictionary.items(), key=lambda item: item[1])

Convert the result to a dictionary using dict()

Display the original and sorted dictionaries.

End the program.

🧪Program

Add Code here


a={2:56,1:2,5:12,4:24,6:18,3:323}

b=sorted(a.items(),key=lambda x:x[1])

print(f"Keys and Values sorted in alphabetical order by the value\n{b}")

Sample Output

<img width="1456" height="207" alt="image" src="https://github.com/user-attachments/assets/9d2d3f6c-0a43-43fb-865d-057bd6c19bfe" />


Result

Thus,the program has been executed successfully.
