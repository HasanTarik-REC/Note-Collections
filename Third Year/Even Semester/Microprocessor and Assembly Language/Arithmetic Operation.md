### **<br/>What is addressing mode? Discuss Based and Indexed addressing modes with example.**
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












