# Simple-Ceaser-Encrypt-and-Decrypt
What is a Ceaser Encrytion? Well, it It is a substitution cipher where each character of the original text is shifted a certain number characters in the alphabet.

Problem Statement:
Create and encrypter/decrypter in python based on the ceaser cipher. It is a substitution cipher where each character of the original text is shifted a certain number characters in the alphabet. Write a function that would require 2 arguments – the input text to be encrypted and a key. For eg: Given the input text ‘hello’ and the key 3, the resulting encryted text would be ‘khoor’. Here you can see that every character in the string hello is shifted by 3 characters. ‘h’ has shifted to ‘k’, ‘e’ has shifted to ‘h’ and so on. If a key of 5 were used, the resulting string would be ‘mjqqt’. This function should be capable of ignoring any characters which are not alphabets. The character ‘z’ entered b
y the user for a key of 3 would result in ‘c’.

Usage:<br>
**encrypt(‘hello world!’, 3)**<br>
**‘khoor zruog!’**

Similarly create decrypter which can decode the encryted text when provided the input text and key

Usage:<br>
**decrypt(‘khoor zruog!’, 3)**<br>
**‘hello world!’**

For the sake of simplicity you can assume that input solely consists of lowercase alphabets, spaces and punctuation symbols. Numbers in the input text would also be ignored similar to symbols.
