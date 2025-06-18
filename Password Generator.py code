#UPPANANTHALA GANESH
import random

letters = "abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ"
numbers = "0123456789"
symbols = "!@#$%^&*()"

length_input = input("Enter password length: ")
letters_input = input("Include letters? (y/n): ")
numbers_input = input("Include numbers? (y/n): ")
symbols_input = input("Include symbols? (y/n): ")

if length_input.isdigit():
    length = int(length_input)
    all_chars = ""

    if letters_input == "y":
        all_chars += letters
    if numbers_input == "y":
        all_chars += numbers
    if symbols_input == "y":
        all_chars += symbols

    if all_chars != "":
        password = ""
        for i in range(length):
            password += random.choice(all_chars)
        print("Generated password:", password)
    else:
        print("No characters selected.")
else:
    print("Please enter a number for password length.")
