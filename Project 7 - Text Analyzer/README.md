Text Analyzer
This project provides a script to analyze text files, providing insights into the number of characters, spaces, words, and frequently used words.

Features
Character Count:
Counts total characters, both including and excluding spaces.
Space Count:
Calculates the total number of spaces.
Word Count:
Provides the total number of words.
Top 5 Common Words:
Displays the five most frequently occurring words and their counts.

How It Works
File Reading:
The open_file function reads the contents of a specified text file.
Text Analysis:
The analyze function calculates:
Total characters, with and without spaces.
Total number of spaces.
Total word count.
The top 5 most common words.
Results Display:
The main function outputs the analysis in a clear format.

Usage
Running the Script
Place your text file in the same directory or provide a full path. The file path is specified in the main function:
text = open_file('note.txt')  # Replace 'note.txt' with your file path

Run the script:
python text_analyzer.py

Example Output
Text File Analysis:

The text file contains:
- 245 characters (including spaces).
- 210 characters (excluding spaces).
- 35 spaces.
- 42 words.

Top 5 Most Common Words:
- 'the' appears 5 times.
- 'and' appears 3 times.
- 'is' appears 2 times.
- 'of' appears 2 times.
- 'text' appears 2 times.

Requirements
Python 3.x
