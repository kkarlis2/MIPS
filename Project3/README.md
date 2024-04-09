MIPS Subprograms


Write the following program in the symbolic language of the MIPS32 processor. You are using
appropriate comments to document your program. You implement the program and the
its subroutines exactly as described below, making proper use of registers
and processor memory. Use indirect addressing via
base register (base register) where references are made to the memory, to the elements of the table.
Program Principle
# Enter data from the user:
Read and store 5 integers (array A)
Read an integer (b1)
Read an integer (b2)
if (b1>=1 && b1<=5 && b2>=1 && b2<=5 && b1<=b2){
k = max (A, b1, b2)
print
# The max subroutine returns the maximum value that
# is from position b1 to position b2 of array A.
# For example if A = (10, 2, 3, 4, -5)
# then for b1=1 and b2=3 the maximum value is 10.
}
else
print ("Index out of range")
End of Program
Page 2 of 3
Start_Subroutine max (Array A, Integer K, Integer P)
int maxA= A[K];
for (int i= K+1; i <= P; i++)
  maxA = greater(maxA, A[i]);
return maxA;
End_Subroutine?
Subroutine_Start greater (Integer x, Integer y)
if (x < y)
return y
else
  return x
End of Subprogram?
