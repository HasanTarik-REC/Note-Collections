### **<br/>What is flag?<br/>Explain signed overflow and unsigned overflow with example.**
A flag is a bit in a register that indicates the status or outcome of different operations. These flags provide information about conditions like arithmetic overflows, zero results, carry operations, etc.<br/>
Signed and unsigned overflows are Independent phenomena.<br/>
"Signed overflow" occurs when the result of a calculation on a signed number(which can be positive or negative) exceeds the representable range of the data type, causing an incorrect value due to the sign bit being affected.<br/>

"Unsigned overflow" happens when the result of a calculation on unsigned numbers (only positive) exceeds the maximum value that can be stored within the allocated bits, regardless of the sign; essentially, both  situations mean the calculation produced a value too large to fit in the available memory space.<br/><br/>
Example with 8-bit representation:<br/><br/>
`Signed Overflow:`<br/>
	- Consider two positive numbers: +127 and +1.<br/>
	- Binary representation of 127 is 01111111.<br/>
	- Adding 1 results in 10000000, which is -128(due to two's complement representation).<br/>
	- This is considered a signed overflow since adding two positive numbers resulted in a negative value.<br/>
`Unsigned Overflow:`<br/>
	- Adding 200 and 100 results in 300 which can't be represented in 8 bits. So an unsigned overflow occurs.<br/>
	- However, adding 100 and 50 gives 150, within the 8-bit range(0 - 255), so no overflow occurs.<br/>




### **<br/>What is Program Segment Prefix? Explain**

A Program Segment Prefix (PSP) is a data structure used in DOS (Disk Operating System) environments to store information about a program that is currently executing.
When a program is loaded in memory, DOS prefaces it with a 256-byte program segment prefix (PSP). The PSP contains information about the program. 
So that programs may access this area, DOS places its segment number in both DS and ES before executing the program. The result is that DS does not contain the segment number of the data segment.
<br/>To correct this, a program containing a data segment begins with these two instructions:<br/>

MOV AX, @DATA<br/>
MOV DS, AX<br/>

@DATA is the name of the data segment defined by .DATA. The assembler translates the name @DATA into a segment number.<br/>
Our second program will print a sting of characters on monitor.<br/>


TITLE	 PGM4_2:  PRINT STRING PROGRAM<br/>

.MODEL SMALL<br/>
.STACK 100H<br/>
.DATA<br/>
 MSG  DB  ‘HELLO$’<br/>
.CODE<br/>
MAIN PROC<br/>

MOV AX, @DATA<br/>
MOV DS, AX<br/>
LEA DX, MSG<br/>
MOV AH,9<br/>
INT 21H<br/>
MOV AH,4CH<br/>
INT 21H<br/>

MAIN ENDP<br/>
END MAIN<br/>


### **<br/>Properties of AND, OR, and XOR**

The AND instruction can be used to clear specific destination bits while preserving the others. A 0 mask bit clears the corresponding destination bit; A 1 mask bit preserves the corresponding destination bit.<br/>

The OR instruction can be used to set specific destination bits while preserving the others. A 1 mask bit sets the corresponding destination bit; A 0 mask bit preserves the corresponding destination bit.<br/>

The XOR instruction can be used to complement specific destination bits while preserving the others. A 1 mask bit complements the corresponding destination bit; A 0 mask bit preserves the corresponding destination bit.<br/>


### **<br/>Why do we write the following two statements in the assembly language code?**<br/>
MOV AH, 4CH<br/>
INT 21H<br/><br/>

The two assembly language statements:<br/>
MOV AH, 4CH<br/>
INT 21H<br/>
are commonly used in DOS (Disk Operating System) programs for terminating the program and returning control to the operating system.<br/>
MOV AH, 4Ch sets up the DOS function to terminate the program.<br/>
INT 21h makes the system call, invoking DOS to handle the function (terminate the program in this case).<br/>
This combination is standard for ending a DOS-based program.<br/>

