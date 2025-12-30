# File_Pyramid

**_Goal:_
This project is meant to test my personal coding ability by taking the "coding_qual_input.txt" and using that input to form a pyramid.**

**_The idea for this project was created with Gemini Pro 3:_**

"Prompt: Write a function in Python that reads a text file associated with a specific filename. The file contains a list of numbers and words, organized as one pair per line.
Your task is to decode a hidden message based on the arrangement of these numbers into a "pyramid" structure. The numbers are linked to the words. The pyramid increases in length by 1 for each row:
Row 1: 1 number
Row 2: 2 numbers
Row 3: 3 numbers
...and so on.
The numbers in the file are not in order. You must reorganize them numerically to form the pyramid. The last number in each row corresponds to the word you need to include in the decoded message.
Example: If the sorted numbers are 1, 2, 3, 4, 5, 6:
Row 1: 1 (Keep word associated with 1)
Row 2: 2, 3 (Keep word associated with 3)
Row 3: 4, 5, 6 (Keep word associated with 6)

**The coding_qual_input.txt was given here.**

Requirements:
The function must accept a message_file filename string as an argument.
It must return the decoded string (the words separated by spaces).
Do not use external libraries (like pandas). Use standard Python libraries only."
