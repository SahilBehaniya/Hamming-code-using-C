# Hamming-code-using-C
Hamming Code Implementation in C This repository contains a complete implementation of Hamming Code in the C programming language. Hamming Code is a widely used error-detection and error-correction code that can detect up to two-bit errors and correct one-bit errors.
Features
Encoding: Generates Hamming Code for a given input data.
Decoding: Detects and corrects single-bit errors in the received data.
Error Detection: Identifies the position of erroneous bits in the received data.
Comprehensive Documentation: Detailed comments and documentation for each function.
Sample Test Cases: Example input and output files for quick testing.
Getting Started
Prerequisites
To compile and run this code, you need:

A C compiler (e.g., GCC)
Installation
Clone the repository:
sh
Copy code
git clone https://github.com/yourusername/hamming-code-c.git
Navigate to the repository directory:
sh
Copy code
cd hamming-code-c
Usage
Compile the source code:
sh
Copy code
gcc hamming_code.c -o hamming_code
Run the executable:
sh
Copy code
./hamming_code
Example
c
Copy code
// Example input data
char data[] = "1011";

// Encode the data
char* encoded_data = encode(data);
printf("Encoded Data: %s\n", encoded_data);

// Introduce an error (for testing)
encoded_data[2] = '0';

// Decode the data
char* decoded_data = decode(encoded_data);
printf("Decoded Data: %s\n", decoded_data);
Contributing
Contributions are welcome! Please fork this repository and submit pull requests for any features or bug fixes.
