Error Detection with 
Hamming Code using 
MIPS assembly language

Write a program in its symbolic language
MIPS32 processor, which will read 12 digits (0 or
1) and checks if these digits correspond to one
correct codeword with even parity, based on
Hamming algorithm.
Auxiliary elements
The Hamming algorithm can be used to control and correct errors during
transfer-transmission of data (words) of any size m.
Suppose that the transmission concerns a word of length one byte, i.e. m=8. For example:
1 1 1 1 0 0 0 0
If during the transfer the 2nd digit (less significant digit) is altered the receiver will receive the word as
following:
1 1 1 1 0 0 1 0
How could this error be detected?

Requirements:
Write a program in the symbolic language of the MIPS32 processor that:
• Reads a 12-digit codeword, as 12 characters '0' or '1'.
• Checks the codeword so that even parity results for all parity digits.
• Displays the result of the check, i.e. 'No error in Codeword' if the codeword
is-transmitted correctly or 'Error in Codeword' if wrong.
