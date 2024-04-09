Simple Encryption using 
MIPS assembly language

A company wants to transmit data over the phone, but
they wonder if their phones are being tapped. All data
are passed to them as four-digit integers. Write one
program in the symbolic language of the MIPS32 processor that to
encrypts their data so it can be transferred
with more security.
More specifically, your program should:
1. It reads a four-digit decimal integer given to it by the user.
2. If the integer is not four digits, it prompts the user for a new integer (until given
four-digit decimal integer – see example run below).
3. It "splits" the decimal digits of the integer into temporary registers.
4. Encrypt each decimal digit of the integer as follows: replace the digit with the remainder
of dividing the sum of the digit plus 7 by 10.
5. Exchanges the first encrypted digit with the third and the second with the fourth.
6. It "condenses" the encrypted digits and thus produces the encrypted integer.
7. Finally, it displays the encrypted integer on the screen.
Below is an example of running the program:

Give a 4-digit number: 999
Invalid input, not a 4-digit number

Give a 4-digit number: 0121
Invalid input, not a 4-digit number

Give a 4-digit number: 12140
Invalid input, not a 4-digit number

Give a 4-digit number: 5678
Encrypted number: 4523

