# Integer-Encryption-Decryption
This project can accept both an integer and integer array to encrypt and decrypt using a certain math equation.

A class named Encrypt accepts any integer, stores the last 4 digits of the integer inside the first half of a private 8 element array, encrypts the 4 digits by taking the remainder of each digit plus 7 divided by 10, swaps the first and third digit, swaps the second and fourth digit, then stores the encrypted integer in the last half of the 8 element array.
The Encrypt class also accepts an integer array of any size, stores the first 4 digits inside the first half of a private 8 element array, encrypts the 4 digits by taking the remainder of each digit plus 7 divided by 10, swaps the first and third digit, swaps the second and fourth digit, then stores the encrypted integer in the last half of the 8 element array.
If the recieved integer has less than 4 digits, zeros are placed in the front of it.
If the recieved integer has a value of less than 1, a default integer value is set.
The Encrypt class also displays both the original integer, and encrypted integer.
The Encrypt class also returns the encrypted integer to a function caller.
The Encrypt class has two constructors to initialize the class with an integer and integer array.

A class named Decrypt accepts any integer, stores the last 4 digits of the integer inside the first half of a private 8 element array, decrypts the integer for it's original value, then stores the decrypted in the last half of the 8 element array.
The Decrypt class also accepts an integer array of any size, stores the first 4 digits inside the first half of a private 8 element array, decrypts the integer for it's original value, then stores the decrypted in the last half of the 8 element array.
If the recieved integer has less than 4 digits, zeros are placed in the front of it.
If the recieved integer has a value of less than 1, a default integer value is set.
The Decrypt class also displays both the original integer, and decrypted integer.
The Decrypt class also returns the decrypted integer to a function caller.
The Decrypt class has two constructors to initialize the class with an integer and integer array.
