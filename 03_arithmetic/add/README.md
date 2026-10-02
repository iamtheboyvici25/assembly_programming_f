#add1
On the line : mov al, [num] -> the interrupt flag was set because the program had started
on the line : add al, [num2] -> PF , AF , SF and OF were set 
PF: The result of the operation was 10000010 which has an even number of 1s hence the flag was set.
AF: During the operation a carry occured between the 3rd and 4th bit.
SF: This is set due to the MSB of the result being 1
OF: This is set due to an overflow  because the result of the operation did not fit in the 8-bit register.
on line : xor ebx, ebx: the flags PF and ZF were set;
PF: The result is zero and the number of 1s is 0 and since 0 is considered an even number , the flag is set
ZF: The result of the operation is 0 , so the flag is set.

add2 
on line ax, [num] -> tthe interrupt flag was set because the program had started
on line : xor ebx, ebx: the flags PF and ZF were set;
PF: The result is zero and the number of 1s is 0 and since 0 is considered an even number , the flag is set
ZF: The result of the operation is 0 , so the flag is set.







#