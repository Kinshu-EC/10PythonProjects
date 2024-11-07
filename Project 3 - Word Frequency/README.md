Word Frequency Counter
This project reads a text file or allows the user to manually input text and then counts the frequency of each word, displaying the most common words and their counts.

Features
File Reading: The program can read content from a specified text file and analyze its word frequencies.
Manual Input: Alternatively, the user can manually enter text for analysis.
Case-Insensitive: The word count is case-insensitive, meaning "word" and "Word" are treated as the same.
Word Tokenization: Only words (alphanumeric characters) are counted, ignoring punctuation and special characters.

How to Use
Run the Script: Open and execute the script in a Python environment.
Input Options:
Choose whether to input text manually or read from a file.
If you choose the file option, provide the path to the text file you want to analyze.
If you choose the text option, manually enter the text you want to analyze.
Review Word Frequency: The program will display each word's frequency in the text.

Example
Do you want to enter text manually or read from a file? (enter 'text' or 'file'): text
Enter your text: Hello world! This is a test. Hello again, world.

hello: 2
world: 2
this: 1
is: 1
a: 1
test: 1
again: 1

Do you want to enter text manually or read from a file? (enter 'text' or 'file'): file
Enter the path to the text file: /path/to/your/textfile.txt

the: 15
and: 10
to: 8
of: 6

Requirements
Python 3.x
