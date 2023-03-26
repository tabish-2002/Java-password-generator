# Java-Password-Generator
Password Generator

This program generates a random password based on user input, with customizable options for password length and character types to include. It also provides the option to copy the generated password to the clipboard.
Usage

To use the program, run the PasswordGenerator class in your Java IDE or from the command line. The program will prompt you for the following input:

    Password length: Enter a number between 8 and 256 to specify the length of the generated password.
    Include uppercase letters?: Enter "y" to include uppercase letters in the generated password, or "n" to exclude them.
    Include lowercase letters?: Enter "y" to include lowercase letters in the generated password, or "n" to exclude them.
    Include numbers?: Enter "y" to include numbers in the generated password, or "n" to exclude them.
    Include symbols?: Enter "y" to include symbols in the generated password, or "n" to exclude them.

After you provide this input, the program will generate a password based on your specifications and display it in the console. You will then be prompted to copy the password to the clipboard by entering "y" or "n".
Dependencies

This program uses the java.util.Scanner and java.util.Random classes for input and random number generation, respectively. It also uses the java.awt.Toolkit and java.awt.datatransfer.StringSelection classes to copy the generated password to the clipboard.
