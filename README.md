# Huffman Coding

A C++ project for file compression and decompression using the Huffman Coding algorithm. This implementation efficiently compresses files by encoding them based on the frequency of characters.

---

## Features
- **File Compression**: Compress files using the Huffman Coding algorithm to save storage space.
- **File Decompression**: Restore compressed files back to their original form.
- **Efficient Encoding**: Uses character frequency to generate a binary tree and create optimal prefix codes.
- **File Statistics**: Displays the original file size and compressed file size for comparison.

---

## Requirements

### Software
- **C++ Compiler**: Any modern C++ compiler (e.g., GCC, Clang, MSVC).

### Tools
- **Make** (Optional): For automated building of the project.

---

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/huffman-coding.git
   cd huffman-coding
2. Compile the Code: Use the following command to compile:

bash
Copy code
g++ -o huffman huffman.cpp main.cpp
Run the Program:

bash
Copy code
./huffman
Usage
Input File:

Place the file you want to compress in the project directory.
Run Compression:

Execute the program and choose the compression option.
Specify the input file name and the desired output file name for the compressed data.
Run Decompression:

Execute the program and choose the decompression option.
Provide the compressed file name and the desired output file name for the decompressed data.
File Statistics:

After each operation, the program displays file sizes to show compression efficiency.
Project Structure
bash
Copy code
HuffmanCoding/
├── huffman.cpp        # Huffman Coding implementation
├── huffman.hpp        # Header file for Huffman Coding
├── main.cpp           # Entry point of the program
├── sample.txt         # Example input file
└── README.md          # Project documentation
Example
Compression
Input file: sample.txt
Command:

bash
Copy code
./huffman compress sample.txt compressed.huff
Decompression
Compressed file: compressed.huff
Command:

bash
Copy code
./huffman decompress compressed.huff decompressed.txt
Future Enhancements
Add error handling for invalid file inputs.
Support batch compression and decompression.
Implement additional statistical analysis (e.g., compression ratio, time taken).
Contributing
Contributions are welcome! Please fork the repository, create a feature branch, and submit a pull request.
