# Code for Encryption & Decryption

Description:

The next Python script implements the Caesar Cipher, an encryption technique for secure communication. It takes a text string and shift value as input and provides the encrypted or decrypted text as output.

How it works:

Input text: The user is prompted to input a string of text they want to encrypt or decrypt.

Shift value: The user is prompted to enter a shift value. The number of positions for each letter in the text will be moved.

Direction: The user is prompted to enter the direction of the shift - "encrypt" or "decrypt." If "encrypt" is chosen, the shift will be to the right (forward in the alphabet). If "decrypt" is chosen, the shift will be to the left (backward in the alphabet).

Processing: The script processes all characters of the input text. The shift value shifts a letter in the specified direction. Non-alphabetic characters remain unchanged.

Output: The script outputs the resulting string after all characters have been processed.

Code Structure:

This script can be divided into two main functions:

caesar_cipher(text, shift, direction): This function performs the real Caesar Cipher operation. It takes an input text, shift value, and direction as parameters. It returns the resulting string after performing the shift operation.

main(): This function is used for user input and output. It prompts the user for the input text, shift value, and direction. It then calls the caesar_cipher function with these values and prints the result.

The script runs from the if __name__ == "__main__": line. This line ensures that the main() function is called when the script is run directly.

Usage:

To use this script, just put the script in a Python environment. You will get a prompt to enter your text, shift value, and direction. The output will be printed to the console.

Please note that this script only shifts letters. Non-letter characters remain unchanged. Shift operations are case-sensitive; uppercase and lowercase letters are shifted differently.

Example

Text: hello
Shift value: 3
Direction: "encrypt" or "decrypt": encrypt

Output: khoor

In this scenario, every letter is shifted 3 places toward the right within the phrase 'hello.'
