# Classical Ciphers Collection

This repository contains Python implementations of various classical ciphers. These ciphers are part of cryptography history and include both **substitution** and **transposition** ciphers. The goal of this project is to provide code for educational purposes.
A python notebook is uploaded that contains all the codes

---

## Ciphers Implemented

1. **Caesar Cipher**  
   A substitution cipher that shifts the letters of the plaintext by a fixed number of positions.

2. **Atbash Cipher**  
   A simple substitution cipher where each letter of the alphabet is mapped to its reverse counterpart.

3. **August Cipher**  
   A cipher that is similar to the Caesar cipher, but with a shifting pattern dependent on the month's number.

4. **Affine Cipher**  
   A substitution cipher where each letter in an alphabet is mapped to its numeric equivalent, then encrypted using an affine function.

5. **Vigenère Cipher**  
   A more complex substitution cipher that uses a keyword to shift letters based on the key's characters.

6. **Gronsfeld Cipher**  
   A variant of the Vigenère cipher, but with numeric keys (0-9), instead of letters.

7. **Beaufort Cipher**  
   A polyalphabetic substitution cipher that is similar to the Vigenère cipher but with a different encryption/decryption formula.

8. **Autoclave (Running Key) Cipher**  
   A polyalphabetic cipher where the key is extended using the plaintext itself.

9. **N-gram Operations**  
   A collection of functions for generating and analyzing n-grams (both character and word-based) from a given text.

10. **Hill Cipher**  
    A cipher that uses linear algebra to encrypt text in blocks by multiplying plaintext with a matrix (mod 26).

11. **Rail Fence Cipher**  
    A transposition cipher that arranges the text in a zigzag pattern and then reads it off row by row.

12. **Route Cipher**  
    A transposition cipher where the message is written into a matrix and then read in a specific route (e.g., spiral).

13. **Myszkowski Cipher**  
    A transposition cipher that uses a keyword to rearrange columns of the text, allowing for encryption and decryption with the keyword.

---

## How to Run

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/yourrepository.git
   cd your_repository
