# VIGENERE-CIPHER
## EX. NO: 4
 

## IMPLEMETATION OF VIGENERE CIPHER
 

## AIM:

To implement the Vigenere Cipher substitution technique using C program.

## DESCRIPTION:

To encrypt, a table of alphabets can be used, termed a tabula recta, Vigenère square,or Vigenère table. It consists of the alphabet written out 26 times in differnt rows, each
 
alphabet shifted cyclically to the left compared to the previous alphabet, corresponding to the 26 possible Caesar ciphers. At different points in the encryption process, the cipher uses adifferent alphabet from one of the rows. The alphabet used at each point repeating keyword.depends on a Each row starts with a key letter. The remainder of the row holds the letters A to Z. Although there are 26 key rows shown, you will only use as many keys as there are unique letters in the key string, here just 5 keys, {L, E, M, O, N}. For successive letters of the message, we are going to take successive letters of the key string, and encipher each message letter using its corresponding key row. Choose the next letter of the key, go along that row to find the column heading that	atches the message character; the letter at the intersection of
[key-row, msg-col] is the enciphered letter.


## ALGORITHM:

Step 1 : 

Design of Vigenere Cipher algorithnm 

Step 2 : 

Implementation using C code 

Step 3 : 

1. The Vigenère cipher uses a series of Caesar ciphers based on letters from a repeating 
keyword to encrypt text. 
2. A Vigenère square or table is created with 26 rows of the alphabet, each shifted one 
position left, representing different Caesar cipher shifts. 
3. To encrypt, each letter of the plaintext is matched with a corresponding letter in the 
keyword, repeated to match the message length. 
4. The letter in the Vigenère table is selected by intersecting the row starting with the 
keyword letter and the column with the plaintext letter. 
5. The resulting encrypted text is a combination of letters taken from various 
rows of the Vigenère square, based on the keyword. 
6. Decryption reverses this process by identifying the original plaintext letter from 
the appropriate row based on the keyword letter.

## PROGRAM

## OUTPUT

## RESULT
