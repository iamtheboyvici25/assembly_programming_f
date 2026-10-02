#sub1 
on line mov al, [num] the interrupt flag was set because the program had started
 on line sub al, [num2]  , the flags CF , PF , SF are set 
 CF: this is set to indicate that a borrow has occurred .
 PF: the result produced has been converted to two's complement due to al using it so the result flag is set to 1 due to even numbers of 1
 SF: The result is neagtive so the MSB is 1 , so flag is set
 on line : xor ebx, ebx: the flags PF and ZF were set;
PF: The result is zero and the number of 1s is 0 and since 0 is considered an even number , the flag is set
ZF: The result of the operation is 0 

sub 2

 on line sub ax, [num2]  , the flags CF , PF , SF are set 
 CF: this is set to indicate that a borrow has occurred .
 PF: the result produced has been converted to two's complement due to al using it so the result flag is set to 1 due to even numbers of 1
 SF: The result is neagtive so the MSB is 1 , so flag is set
 on line : xor ebx, ebx: the flags PF and ZF were set;
PF: The result is zero and the number of 1s is 0 and since 0 is considered an even number , the flag is set
ZF: The result of the operation is 0 




