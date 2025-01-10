### Chapter 1 (Interfacing IO Devices))

### **<br/>What is meant by computer peripheral interfacing? Explain with an example.**

##### `Computer Peripherals:`
Computer Peripherals are the components or devices that are connected to the processor and extend the work of the processor. All input and output devices are known as computer peripherals. For this reason, computer peripherals are sometimes called I/O devices.<br/>
In other words, Computer peripherals are the hardware connected to the computer's CPU.<br/>
##### `Interface:`
An interface is the concept of communication between two components, objects, elements, or two parts of a single object or component and it may occur on both hardware and software levels.<br/>
Simplifying, the interface is the interaction between two things.<br/>
#### `Computer Peripherals and Interfacing:`
Computer Peripheral Interfacing is the interaction between computer processors and computer peripherals. Any input or output process that
occurs through a peripheral device is computer peripheral interfacing.<br/>

##### `Components of Computer Peripheral Interfacing:`
To interface among peripheral devices three components are needed.
  - `I/O Processor:` I/O processor is the processor of the computer which means CPU. To interface between peripherals, there must be a central device that will control the interface.
  - `I/O Module:` While computer peripheral interfacing there must be a mediator between peripherals and processors. Which is normally known as the I/O module.
  - `I/O Device:` I/O device is the peripheral device with which the interface will occur. This can be any input or output device.

##### `Examples of Computer Peripheral Interfacing:`
  - Taking input from a keyboard is peripheral interfacing. Here the keyboard is the peripheral device.
  - Printing a document with a printer is peripheral interfacing where the printer is the peripheral device.
  - Showing a video on the monitor is peripheral interfacing and in this case monitor is the peripheral device.

### **<br/>Distinguish between port-addressed I/O and memory-mapped I/O.**
`Port-Addressed I/O:` In Port addressed I/O or Peripheral I/O or I/O mapped I/O an 8-bit port is used to interface I/O with the processor. Intel 8085 processor uses peripheral I/O for data transfer.<br/>
`Memory-mapped I/O:` In memory-mapped I/O a 16-bit memory register is used to interface I/O with the processor. Motorola 68000 processor uses memory-mapped I/O for data transfer.<br/><br/>
Differences between port-addressed I/O and memory-mapped I/O are given below.<br/>
| Port-Addressed I/O | Memory-Mapped I/O |
|---|---|
| It uses an 8-bit address. | It uses a 16-bit address. |
| Control Signals for input/output is IOR/IOW.| Control Signals for input/output are MEMR/MEMW. |
| Available instructions are IN and OUT. | Available instructions are STA, LDA, MOV M, R, ADD M, SUB M, etc. |
| Data transfer occurs between I/O devices and accumulators. | Data transfer occurs between I/O devices and registers. |
| The I/O map is independent of the memory map. 256 input devices and 256 output devices can be connected. | The memory map is shared between I/Os and system memory. |
| Execution speed is 10 T-states. | Execution speed is 13 T-states for STA, LDA, and 7 T-states for MOV M, R. |
| Less Hardware is needed to decode 8-bit addresses. | More hardware is needed to decode 16-bit addresses. |
| Arithmetic and Logical Operations can not be directly performed with I/O data. | Arithmetic and Logical Operations can be directly performed with I/O data. |


### **<br/>Is it possible to interfacing, IN 20H and OUT 20H? Explain why and why not.**
Yes. It is possible to interfacing, IN 20H and OUT 20H.<br/>
Since the instructions are IN, OUT. So it’s a port-addressed I/O. Since port-addressed I/O uses an 8-bit address, the second byte of IN and OUT instructions can be any 256 combinations of eight bits from 00H to FFH. Since 20H falls between 00H and FFH, it is
possible to interfacing IN 20H and OUT 20H.

### **<br/>Explain absolute address decoding and partial address decoding with examples.**







