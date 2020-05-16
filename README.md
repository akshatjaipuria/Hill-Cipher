# Hill Cipher 
Hill cipher is a polygraphic substitution cipher based on linear algebra.Each letter is represented by a number modulo 26. Often the simple scheme A = 0, B = 1, …, Z = 25 is used, but this is not an essential feature of the cipher. To encrypt a message, each block of n letters (considered as an n-component vector) is multiplied by an invertible n × n matrix, against modulus 26. To decrypt the message, each block is multiplied by the inverse of the matrix used for encryption.

Refer <a href='https://crypto.interactive-maths.com/hill-cipher.html'>this</a> for detailed working of the algorithm.

## About the project
Problem statement:
```
Using the word "temp" as the key, simulate the secure communication between security troops located away from 
each other, using Hill cipher.
```

The project is a simple implementation of Hill Cipher Algorithm in python.

- hill_cipher_gui.py contains the complete implementation of Hill Cipher wrapped in a Tkinter GUI

- hill_cipher.py contains the actual logic of the Hill Cipher encryption/decryption and can be executed independently.

Team Members: Akshat Jaipuria, Sunchit Lakhanpal, Saurav Banerjee

## Usage
```bash
$ python hill_cipher.py
$ python Hill_Cipher_GUI.py
```

