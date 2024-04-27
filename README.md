## README ##
## Run-Length Encoding (RLE) Compression and Decompression

#### Description:
This C++ program implements the Run-Length Encoding (RLE) algorithm, a simple form of data compression. It takes input from a text file, performs either encoding or decoding based on user choice, and writes the result to an output file. Run-Length Encoding is a lossless compression technique commonly used in scenarios where consecutive characters are repeated frequently.

#### Featires:
 **Encoding**: Converts input text into its RLE-encoded form.
 **Decoding**: Converts RLE-encoded text back into its original form.
 **Input/Output Files**: Reads input from input.txt and writes output to output.txt.
 **User Interaction**: Provides a user-friendly interface for selecting the encoding or decoding operation.
 **Error Handling**: Handles file I/O errors gracefully, providing informative error messages.


#### Compilation: 
Compile the source code using your C++ compiler. 
#### Run the Program: 
Execute the compiled binary
 

#### Input: 
Write the text you want to encode or the RLE-encoded text you want to decode in **input.txt**. Each line in the file represents a separate input string.
#### Operation Selection: 
When you run the program, you will be prompted to choose between encoding and decoding. Enter 1 for encoding or 2 for decoding.
#### Output: 
The result of the chosen operation will be written to **output.txt**.
#### Example
Suppose **input.txt** contains the following text:
**“hello my name is Kyial”**
#### Encoding: 
If you choose to encode, the resulting **output.txt** will contain:
**“h1e1l2o1 1m1y1 1n1a1m1e1 1i1s1 1K1y1i1a1l1”**
#### Decoding: 
If you choose to decode the above encoded text, the resulting **output.txt** will contain:
**“hello my name is Kyial”**

