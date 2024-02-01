Il Derevigenere
A revised version or the veritable Vigenere Cipher devised originally by the visionary Giovan Battista Bellaso in the 16th century, surviving almost four centuries of certain uncrackabile security.

Learn more about vigenere ciphers here:
https://en.wikipedia.org/wiki/Vigen%C3%A8re_cipher

# A Python Vigenere Cipher

Welcome to the `il-derevigenere` repository! This Python script implements a Vigenere cipher, a classic encryption method that adds complexity to the traditional Caesar cipher. This cipher is a polyalphabetic substitution, meaning that it uses multiple substitution alphabets.

## Vigenere Cipher Overview

The Vigenere cipher operates by using a keyword to shift each letter in the plaintext by a corresponding amount, taken from a given keyword known only to the cipher's intended users. It was a more secure encryption than a simple Caesar cipher. Unlike the Caesar cipher, which has a single shift, the Vigenere cipher keyword defines a unique shift for each letter.

## Functionality Overview

The provided Python script replicates the Vigenere cipher, offering both `devigenere` encryption (locking) and  `revigenere` decryption (unlocking) functionalities. It takes `message` and `key` as inputs and provides an encrypted message as output. 

### Features

While staying true to the Vigenere cipher concept, this implementation introduces several enhancements:

User-Friendly Interface: The script provides a seamless user experience, allowing users to easily input messages and keywords without getting into the specifics of encryption or decryption operations.

Special Character Handling: In contrast to the original cipher, which required users to manually remove and reinsert special characters before and after encryption, this script automates the process. Special characters are seamlessly incorporated into the encrypted message without any user intervention.

Keystone Markers: The script employs [>.<] markers to represent unknown characters in the message, ensuring transparency during the encryption process. These markers simplify the identification of characters that may be altered during encryption, enhancing overall clarity.

## Getting Started

Clone the repository. Run the script. Follow the prompts.

```bash
python vigenere_cipher.py
```

## Author

Mike Delmar | 2024 [>.<]

Feel free to explore, use, and modify the code to suit your needs. Any comments or suggestions, I welcome your feedback.
