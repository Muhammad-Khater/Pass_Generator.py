🔐 Password Generator (Python)

This Python script generates a strong, randomized password based on a user-defined length. It ensures a secure mix of lowercase letters, uppercase letters, digits, and punctuation symbols.

✨ Features

Prompts the user for the desired password length

Validates that the input is a number and at least 8 characters

Uses Python's built-in string and random modules

Creates a password with:

60% letters (mixed upper & lower case)

40% digits & punctuation

Shuffles characters to enhance randomness

Outputs a strong, ready-to-use password

🛠 How It Works

Loads character sets:

string.ascii_lowercase

string.ascii_uppercase

string.digits

string.punctuation

Asks the user for the password length and validates the input.

Splits the password into proportions:

30% lowercase

30% uppercase

20% digits

20% punctuation

Randomly samples characters based on the proportions.

Shuffles all selected characters and joins them into the final password.

▶️ Usage

Run the script:

python password_generator.py


Enter the desired password length when prompted.
The script will display a secure, randomized password such as:

Strong Password:  A3#ngP9@bK...

📌 Requirements

Python 3.x

No external libraries needed
