# Caesar-Cipher
Using Functions to Implement a Caesar Cipher

I wrote a program that implements a Caesar cipher, which is a simple method of encryption.

A Caesar cipher takes the letters of a message and shifts each letter along the alphabet by a certain number of places.

In this lab,
We created user-defined functions
Use several functions to implement a Caesar cipher encryption program

Description

This project implements a Caesar cipher, a basic encryption technique that shifts letters in a message by a specified number of positions in the alphabet. 
The program allows users to encrypt and decrypt messages using this simple yet effective method of encryption.

Technologies Used

Python - The programming language used to implement the Caesar cipher.
User defined Functions - The program is structured using multiple functions to enhance modularity and readability

Implementation Details

Functions - The program is organized into several user-defined functions, each responsible for a specific task

encrypt(message, shift) - Takes a plaintext message and a shift value, returning the encrypted message.

decrypt(ciphertext, shift) - Takes an encrypted message and a shift value, returning the original plaintext message.

shift_character(char, shift) - A helper function that shifts a single character by the specified amount, 
handling both uppercase and lowercase letters while preserving non-alphabetic characters.

main() - The main function that drives the program, handling user input and displaying results.

Design Considerations

Modularity - The use of functions promotes code reusability and makes the program easier to maintain and extend

Input Validation - The program includes basic input validation to ensure that the shift value is within a valid range and that the input message is properly formatted

Character Handling - The implementation ensures that non-alphabetic characters remain unchanged during encryption and decryption, preserving the integrity of the original message.

