# Huffman Coding in C++

This project implements the **Huffman Coding Algorithm** in C++. Huffman Coding is a compression technique used to reduce the size of data without losing any information. This implementation reads input from a text file, builds a Huffman Tree based on character frequencies, encodes the input text, and then decodes it back to the original text.

## Features

- Builds a Huffman Tree from character frequencies.
- Generates Huffman codes for each character.
- Encodes a given input text using the generated Huffman codes.
- Decodes the encoded string using the Huffman Tree.
- Reads input text from a file named `text.txt`.

## File Structure

- `main.cpp`: Contains the full source code implementing Huffman Coding.
- `text.txt`: Input text file (you must create this with your desired text).
- `README.md`: This file.

## How to Use

1. **Create an input file** `text.txt` in the same directory with the text you want to compress.
2. **Compile the program** using a C++ compiler:
   ```bash
   g++ main.cpp -o huffman
   ```
3. **Run the executable**:
   ```bash
   ./huffman
   ```
4. The program will display:
   - Huffman codes for each character.
   - The original string.
   - The encoded binary string.
   - The decoded string (should match the original).

## Example Output

```
Huffman Codes are :

a 0
b 10
c 11

Original string was :
abac

Encoded string is :
0100110

Decoded string is:
abac
```

## Notes

- Ensure the `text.txt` file exists in the same directory as your executable.
- This is a basic implementation and is designed for educational purposes.
