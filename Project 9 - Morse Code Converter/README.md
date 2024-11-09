Morse Code Converter
This project is a command-line tool to convert English text to Morse code and vice versa.

Features
English to Morse Code: Convert regular English text into Morse code.
Morse Code to English: Translate Morse code back into English.

How It Works
Conversion Dictionaries: The program uses two dictionaries:
morse_code_dict maps English characters to Morse code.
morse_to_english_dict maps Morse code back to English characters.

Functions:
convert_to_morse(text): Converts English text to Morse code.
convert_from_morse(morse_code): Converts Morse code back to English.
User Prompt: The main function prompts the user to select a conversion direction and handles the conversion accordingly.

Usage
Running the Script
Run the script in a Python environment:
python morse_code_converter.py

Follow the on-screen prompts to convert text to or from Morse code:
Select Conversion: The script will ask:
Do you want to convert from (1) English to Morse code or (2) Morse code to English? Enter 1 or 2:

Enter 1 for English to Morse code or 2 for Morse code to English.

Input Text or Morse Code:

If you select English to Morse (1), enter the English text to convert.
If you select Morse to English (2), enter Morse code with words separated by "/" and letters by spaces.

Example Input & Output
English to Morse:
Enter text to convert to Morse code: HELLO WORLD
Morse Code: .... . .-.. .-.. --- / .-- --- .-. .-.. -..

Morse to English:
Enter Morse code to convert to English: .... . .-.. .-.. --- / .-- --- .-. .-.. -..
English: HELLO WORLD

Requirements
Python 3.x
