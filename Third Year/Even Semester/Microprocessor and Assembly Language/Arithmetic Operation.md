### **<br/>What is addressing mode? Discuss Based and Indexed addressing modes with examples.**
Addressing mode refers to the method used by a microprocessor to locate the memory address of an operand during program execution. 
Different addressing modes offer varying levels of flexibility and efficiency for accessing data.<br/><br/>
Types of Addressing Modes:<br/>
Some common addressing modes include:<br/>
  - Immediate Addressing Mode
  - Register Addressing Mode
  - Direct Addressing Mode
  - Indirect Addressing Mode
  - Based Addressing Mode
  - Indexed Addressing Mode
  - Based-Indexed Addressing Mode<br/>
<br/>Now, let's focus on Based and Indexed addressing modes, along with examples.

#### Based Addressing Mode<br/>
In based addressing mode, the effective address (the actual memory address of the operand) is calculated by adding a base register to a displacement value. 
The base register typically holds the starting address of a data structure, while the displacement specifies the offset within that structure.<br/><br/>
Syntax:<br/>
operand = [base_register + displacement]<br/><br/>
Example:<br/>
MOV AX, [BX + 10]<br/><br/>

#### Indexed Addressing Mode<br/>
In indexed addressing mode, the effective address is calculated by adding an index register to a base register and a displacement. 
This mode is commonly used for accessing elements of arrays or tables.<br/><br/>
Syntax:<br/>
operand = [base_register + index_register + displacement]<br/><br/>
Example:<br/>
MOV AX, [BX + SI + 2]<br/><br/>


### **<br/>Explain the near type and far type of procedures used in assembly language.**
`Near-type procedure: ` A near-type procedure is located within the same code segment as the calling procedure. 
This means that the offset address of the procedure is relative to the current code segment register.<br/>
When a near procedure is called, only the offset address is pushed onto the stack. 
The current code segment remains unchanged.<br/><br/>

`Far-type procedure: ` A far-type procedure can be located in any code segment, even a different one than the calling procedure. 
This means that both the offset address and the segment address of the procedure must be specified.<br/>
When a far-type procedure is called, both the segment address and offset address are pushed onto the stack. 
The current code segment is changed to the segment address of the procedure<br/>


### **<br/>What happens when CALL and RET instructions are executed?**

The CALL and RET instructions are fundamental to subroutine or function calls in assembly language. 
They are used to transfer control to a specific procedure and then return back to the original calling point.<br/><br/>
CALL Instruction transfers control to a specified procedure.<br/>
`CALL Instruction pushes the return address onto the stack:` The current instruction pointer (IP) value is saved on the stack so that the program can return to the correct location after the procedure finishes.<br/><br/>
`Loads the procedure's address into the instruction pointer:` The address of the procedure to be called is loaded into the IP, causing the processor to start executing instructions from that location.<br/><br/>

RET Instruction returns from a procedure to the calling point.<br/>
`RET Instruction pops the return address from the stack:` The top value on the stack is removed and loaded into the IP.<br/><br/>
`Resumes execution:` The processor continues execution at the address stored in the IP, effectively returning control to the calling procedure.<br/>






