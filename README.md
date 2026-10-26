# Lab-Exercise---1---Caesar-Cipher
**Aim:**
To design, implement, and test a Python program that performs data encryption and decryption using the Caesar Cipher substitution technique.


**Procedure**
1. User Selection: Prompt the user to select either Encryption (e) or Decryption (d).
2. Data Gathering: Prompt the user to enter the plaintext/ciphertext message and the numerical shift key value.
3. Key Optimization: Apply a modulo operations (% 26) to the shift value to seamlessly handle keys greater than 26.
4. Direction Handling: If decryption is selected, negate the shift value (shift = -shift) to reverse character mapping.
5. Alphabet Mapping: Iterate through the text, applying the modular formula below to wrap characters within bounds while ignoring non-alphabetic characters:
New Character=(Current Character-Base ASCII+Shift)(mod 26)+Base ASCII
6. Output Generation: Append the modified characters together and print the final string result to the terminal display.

**output**

<img width="532" height="592" alt="image" src="https://github.com/user-attachments/assets/42b41f04-0fb5-4cb7-b07c-b279309f7cae" />

**Result**
The Caesar Cipher script was successfully implemented and verified. 
