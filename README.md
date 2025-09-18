# Huffman Encoding Project

## Project Description

This project implements **Huffman Coding**, a lossless data compression algorithm, in C++. It allows users to efficiently **compress text files** into a smaller binary format and **decompress them** back to their original form. The project demonstrates the use of **binary trees, priority queues, and file I/O** to encode and decode data while preserving all information. It is designed as a command-line tool for easy compilation and execution, providing a hands-on example of classical compression techniques in computer science.

## Key Features

* **Lossless Compression:** Compresses text files without losing any data.
* **Huffman Encoding & Decoding:** Implements both encoding and decoding processes using Huffman algorithm.
* **Efficient Data Structures:** Uses binary trees and priority queues to optimize compression.
* **Command-Line Interface:** Easy compilation and execution using simple g++ commands.
* **File I/O Support:** Handles reading from input files and writing compressed/decompressed output files.

## Usage Instructions

The repository provides step-by-step instructions for compiling and running the encoding and decoding programs using g++:

### Compile the Encoder

```
g++ huffman.cpp encode.cpp
```

### Run the Encoder

```
./a.out your_sample.txt your_out.huf
```

### Compile the Decoder

```
g++ huffman.cpp decode.cpp
```

### Run the Decoder

```
./a.out your_out.huf new_out.txt
```
