OVERVIEW:
This repository features a Python program that implements the Caesar Cipher algorithm, allowing users to encrypt or decrypt text with a specified shift value.
A Caesar cipher is a simple method of encoding messages. Caesar ciphers use a substitution method where letters in the alphabet are shifted by some fixed number of spaces to yield an encoding alphabet. A Caesar cipher with a shift of 1 would encode an A as a B, an M as an N, and a Z as an A, and so on
FEATURES: 
	Encryption**: Shifts characters in a message forward by a user-defined number of positions in the alphabet.
	Decryption**: Reverses the shift to restore the original message.
	Handles both uppercase and lowercase letters.
	Retains non-alphabetic characters (e.g., spaces, numbers, and punctuation) without alteration.
PREREQUISITES:
	Python 3.7 or higher must be installed on your machine.
 INSTALLATION:
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/caesar-cipher.git
   ```
2. Navigate to the project directory:
   ```bash
   cd caesar-cipher
   ```
USAGE:
1. Run the program:
   ```bash
   python caesar_cipher.py
   ```
2. Follow the prompts:
   - Enter the message you want to encrypt or decrypt.
   - Provide a shift value (integer).
   - Select whether to encrypt or decrypt the message.
EXAMPLE:
	Encryption
```plaintext
Welcome to the Caesar Cipher Program!
Enter your message: Hello, World!
Enter the shift value: 3
Choose an option:
1. Encrypt
2. Decrypt
Enter your choice: 1
Encrypted message: Khoor, Zruog!
```

	Decryption
```plaintext
Welcome to the Caesar Cipher Program!
Enter your message: Khoor, Zruog!
Enter the shift value: 3
Choose an option:
1. Encrypt
2. Decrypt
Enter your choice: 2
Decrypted message: Hello, World!
```
HOW IT WORKS:
The Caesar Cipher is a simple substitution cipher that shifts letters in the text by a fixed number of positions in the alphabet. Key points:

- A positive shift moves letters forward; a negative shift moves them backward.
- The cipher wraps around the alphabet (e.g., shifting `Z` by 1 results in `A`).
- Non-alphabetic characters remain unchanged, preserving formatting.




<!--
**Alakeade/Alakeade** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
