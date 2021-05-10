# Assignment-6-Inf-Theory

Input: a sequence of binary digits from Part 2. 

Goal: Encode the binary sequence after Part2 (Shannon-Fano or Huffman code) with Hamming  code. 

Final output: a sequence of binary digits ready for error correction. 

Output:  

1. Read the file with the sequence of bits from assignment 3.

2. For teams of 2: one member builds (15, 11) Extended Hamming code as described  in Lecture 4 (it uses 11 data bits), another member builds (7, 4) Hamming code using one of the  approaches from Lecture 5 (it uses 4 data bits). For approach 1 (7, 4) Hamming code from Lecture  5 use the extended version where you will add a parity bit in the 0th position to check the parity  of all 7 bits. 

3. Write a function HammingEncode(bitstring) that takes a sequence of 11 bits and  returns the 16-bit codeword for (15, 11) Extended Hamming to be sent over the channel, and a  function HammingEncode2(bitstring) that takes a sequence of 4 bits and returns the 8-bit  codeword for (7, 4) Extended Hamming to be sent over the channel (or the 7-bit codeword for  (7, 4) Hamming approach 2 with matrices). Include all intermediate steps. 

4. Run functions HammingEncode and HammingEncode2 on all data blocks. Please  include all intermediate steps. The output should be the same as in the previous output (3), but  on all data blocks.

5. Combine all of the encoded bitstrings into one sequence. Print it and save it in a txt  file. 
