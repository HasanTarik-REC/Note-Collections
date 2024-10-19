### **<br/>What is flag?<br/>Explain signed overflow and unsigned overflow with example.**
A flag is a bit in a register that indicates the status or outcome of different operations. These flags provide information about conditions like arithmetic overflows, zero results, carry operations etc.<br/>
Signed and unsigned overflows are Independent phenomena.<br/>
"Signed overflow" occurs when the result of a calculation on signed number(which can be positive or negative) exceeds the representable range of the data type, causing an incorrect value due to the sign bit being affected.<br/>

"Unsigned overflow" happens when the result of a calculation on unsigned numbers (only positive) exceeds the maximum value that can be stored within the allocated bits, regardless of the sign; essentially, both  situations mean the calculation produced a value too large to fit in the available memory space.<br/>
Example with 8-bit representation:<br/>
Signed Overflow:
	- Consider two positive numbers: +127 and +1.
	- Binary representation of 127 is 01111111.
	- Adding 1 results in 10000000, which is -128(due to two's complement representation).
	- Since adding two positive numbers resulted in a negative value, this is Considered a signed overflow.
Unsigned Overflow:
	- Adding 200 and 100 results in 300 which can't be represented in 8 bits. So an unsigned overflow occurs.
	- However, adding 100 and 50 gives 150, which is within the 8-bit range(0 - 255), so no overflow occurs.
