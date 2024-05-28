### Chapter 3 (Process Management)

### **<br/>Define Process**
In the operating system, a process is a program currently under execution. An active program can be called a process.<br/><br/>
<img src ="./Capture1.PNG" width = "350"/>
<br/>
#### `Stack: `The process stack contains the temporary data such as method/function, parameters, return address, and local variables.<br/>
#### `Heap: `This is dynamically allocated memory to a process during its run time.<br/>
#### `Text: `This includes the current activity represented by the value of the program counter and the contents of the processor's registers.<br/>
#### `Data: `The section contains the global and static variables.<br/>

### **<br/>Process state transition**
As a process executes, it changes state. The state of a process is defined in part by the current activity of that process. Each process may be in one of the following states:<br/>
- `New: `The process is being created.
- `Ready: `The process is waiting to be assigned to a processor.
- `Running: `Instructions are being executed.
- `Waiting: `The process is waiting for some event to occur (such as an I/O completion or reception of a signal).
- `Terminated: `The process has finished execution.
<br/>
<img src ="./Capture2.PNG" width = "600"/>




