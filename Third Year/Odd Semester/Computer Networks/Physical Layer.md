### **<br/>Define switching.**
Switching is the practice of directing a signal or data
element toward a particular hardware destination.<br/>

There are two types of switch:<br/>
- Circuit switching
- Packet Switching

### **<br/>Define Circuit switching**

Circuit switching is a method for communication networks where a dedicated path, or circuit, is established between two devices before any data transmission can begin. This dedicated path remains open for the entire duration of the communication session, and no other devices can use it during that time.

### **<br/>Define Packet switching**

Packet switching is a method of data transmission in computer networks where messages are divided into smaller units called packets, which are individually routed and transmitted over the network. Each packet contains control information (source, destination, and its position in the sequence of packets) and a portion of the message data.

### **<br/>Defference between circuit switching and packet switching.**
| Circuit Switching | Packet Switching |
|---|---|
|1.In-circuit switching has 3 phases: Connection Establishment, Data Transfer, Connection Released.|1.In Packet switching directly data transfer takes place.|
|2.Connection-oriented|2.Connectionless|
|3.Less efficient|3.More efficient|
|4.Call setup is required in circuit switching.|4.No call setup is required in packet switching.|
|5.It is not a store and forward technique.|5.It is a store and forward technique.|
|6.Less flexible|6.More flexible|
|7.More expensive|7.Often cheaper|
|8.Real-time communication (voice,video)|8.General data transfer (Internet,Email)|


### **<br/>Define X.25 protocol**
The X.25 protocol is a suite of standards developed by the International Telecommunication Union (ITU) that defines how data communication works in wide area networks (WANs) using packet switching.  It was first published in 1976 and played a crucial role in the early development of the internet, but has largely been superseded by more modern protocols like IP.

### **<br/>X.25 protocol specifies 3 layers**
- Physical Layer
- Frame Layer
- Packet Layer

### **<br/>Functionalty of X.25**
X.25 network devices fall into three general
categories:<br/>
1. Data Terminal Equipment (DTE),
2. Data Circuit-terminating Equipment (DCE),
3. Packet-switching Exchange (PSE)
    - PAD- Packet Assembler/ Dissembler<br/>

#### **`DTE`**<br/>
- Data terminal equipment devices are end systems that communicate across the X.25
- They are usually Terminals, personal computers, or network hosts, and are located on the premises of individual subscribers.

#### **`DCE`**<br/>
- DCE devices are communications devices, such as Modems and packet switches, that provide the interface between DTE devices and a PSE, and are generally located in the carrier's facilities.<br/>
- PSEs are switches that compose the bulk of the carrier’s network.<br/>
- They transfer data from one DTE device to another through the X.25 PSN.

#### **`PSE`**<br/>
- PSEs are switches that compose the bulk of the carrier's network.
- They transfer data from one DTE device to another through the X.25 PSN.

#### **`Packet Assembler/Disassembler(PAD)`**<br/>
- The packet assembler/disassembler (PAD) is a device commonly found in X.25 networks.
- The PAD is located between a DTE device and a DCE device, and 
- It performs three primary functions:<br/>
    - Buffering (storing data until a device is ready to process it),
    - Packet assembly,
    - Packet disassembly.

 ### **<br/>X.25 Protocol**
- Communication in this layer involves 3 phases:<br/>
    - Link Set Up
    - Data and Control transfer
    - Link disconnect
- These phases use different frames such as:<br/>
    - **`U-Frame:`**  U-Frame is used to set up and disconnect the conncetion between DTE and DCE.
    - **`I-Frame:`** I-Frames are used to encapsulate PLP packets from the upper layer.
    - **`S-Frame:`** S-Frame is used to for error control and flow control.


### **<br/>Virtual Circuits in X.25**
- Two types of virtual circuit exists in x.25<br/>
    - Switched virtual circuits (SVCs)<br/>
    - Permanent virtual circuit (PVCs)<br/>

### **<br/>Switched virtual circuits**
Switched virtual circuits (SVCs) are temporary connections
used for irregular data transfers. They require that two DTE
devices establish, maintain, and terminate a session each time
the devices need to communicate.
### **<br/>Permanent virtual circuits**
Permanent virtual circuits (PVCs)are permanently established
connections used for frequent and consistent data transfers.
PVCs do not require that sessions be established and
terminated.<br/>
Therefore, DTEs can begin transferring data whenever
necessary because the session is always active.

### **<br/>The following 5 events occur in X.25 protocol**
- Link is set up between local DTE & DCE node and also between the remote DTE and DCE.
- VC is established between local and remote DTE.
- Data is transferred between two DTEs.
- VC is released.
- Link is desconnected.

### **<br/>PLP Packet**
- GFI or General Format Identifier is a 4 bit field.
- LCN- Logical Channel Number
- PTI or Packet Type Identifier defines the type of packet, viz. data packet or control packet.


### **<br/>PLP Packet
- GFI or General Format Identifier is a 4 bit field.<br/>
    - The first bit (Q bit, Qualifier) defined source of control information.<br/>
        - 0 for PLP and 1 for upper layer protocol.<br/>
    - The D bit(Delivery) defines which device should acknowledge the packet 0 for local DCE, 1 for remote DTE.<br/>
    - The last two bits indicate size of sequence number fields.<br/>
- LCN- Logical Channel Number<br/>
    - 12 bit

### **<br/>PLP Packet<br/>Virtual Channel ID Numbers**
- Up to 4096(2^12) multiplexed channels between each DTE and DCE.
- The calling and called hosts use different numbers.

### **<br/>LCNs in X.25**
- Logical Channel Number identifies the VC at different sections of the network.<br/>
- A pair of LCN is defined when a VC is established between two DTE's.
