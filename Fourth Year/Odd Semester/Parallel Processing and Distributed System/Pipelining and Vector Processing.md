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


### **<br/>PLP Packet**
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


### **<br/>MAC (Medium Access Control)**
- The protocols used to determine who goes next on a multiaccess channel belong to a sublayer of the data link layer called the MAC (Medium Access Control) sublayer.<br/>
- The MAC sublayer is especially important in LANs, particularly wireless ones because wireless is naturally a broadcast channel.

### **<br/>The Channel Allocation Problem**
There are two scheme-<br/>
- Static Channel Allocation
- Dynamic Channel Allocation

### **<br/>Network links can be divided into two categories:**
- Those using point-to-point connections, and
- Those using broadcast channels.

### **<br/>Assumptions on dynamic channel allocation**
- Independent Trafic.
- Single channel.
- Observable collision.
- Continuous or slotted time.
- Carrier sense or No carrier sense.

### **<br/>Fixed/Static Channel Allocation**
Fixed Channel Allocation is a strategy in which fixed number of channels or voice channels are allocated to the cells. Once the channels are allocated to the specific cells then they cannot be changed. In FCA channels are allocated in a manner that maximize Frequency reuse. If all channels are occupied and user make a call then the call is blocked. Borrowing Channels handles this type of problem. In this cell borrow channels from other cells.
### **<br/>Dynamic Channel Allocation**
Dynamic Channel Allocation is a strategy in which channels are not permanently allocated to the cells. When a User makes a call request then Base Station(BS) send that request to the Mobile Station Center(MSC) for the allocation of channels or voice channels. This way the likelihood of blocking calls is reduced.

### **<br/>How a channel can be allocated statically?**
Suppose that there are N competing users. Here, the total bandwidth is divided into N discrete channels using frequency division multiplexing (FDM). In most cases, the size of the channels is equal. Each of these channels is assigned to one user.<br/>
o User needed to be constant N.
o When some users are quiescent, their bandwidth is simply lost.
o The traffic ratios  will 1000:1
o Most of the channels will be idle most of the time

### **<br/>The working principle of the pure Aloha protocol with its limitations.**
**`Working Principle of Pure Aloha:`**<br/>
**`Transmission:`** A user can transmit a frame at any time when it has data to send. There is no need to wait for a specific time slot or permission.<br/>
**`Collision Detection:`** After transmitting a frame, the sender listens for an acknowledgment from the receiver. If the sender does not receive an ACK within a certain time window, it assumes that a collision has occurred.<br/>
**`Collision Resolution:`** Upon detecting a collision, the sender stops transmitting and waits for a random amount of time before attempting to resend the frame.<br/>
**`Acknowledgment:`** If the receiver successfully receives the frame, it sends an acknowledgment back to the sender. The sender considers the transmission successful if it receives the acknowledgment within the acknowledgment time window.<br/><br/>
**`Limitations of Pure Aloha:`**<br/>
**`Vulnerability to Collisions:`** The primary limitation of Pure Aloha is its vulnerability to collisions. If two or more stations transmit at the same time, their signals may overlap, leading to a collision.<br/>
**`Scalability Issues:`** As the number of users increases, the likelihood of collisions also increases, leading to reduced efficiency. Pure Aloha becomes less scalable in terms of handling a larger number of stations sharing the same channel.<br/>
**`Low Efficiency:`** Pure Aloha is not very efficient because a significant portion of the channel time is wasted due to collisions and retransmissions. The protocol allows users to transmit at any time, which increases the likelihood of collisions.


### **<br/>How the slotted Aloha has minimized the shortcoming?**
**`Time Slot Synchronization:`** In Slotted Aloha, time is divided into fixed-length slots, and each slot corresponds to the time it takes to transmit one frame. All stations are required to synchronize their transmissions to these time slots.<br/>
**`Transmission Timing:`** Stations are allowed to transmit only at the beginning of a time slot. This eliminates the possibility of collisions within a slot because only one station can transmit during that specific time interval.<br/>
**`Reduced Collision Probability:`** Since transmissions occur only at the beginning of time slots, the probability of two or more stations attempting to transmit simultaneously is significantly reduced compared to Pure Aloha. This reduces the likelihood of collisions.<br/>
**`System Scalability:`** Slotted Aloha is more scalable than Pure Aloha in terms of handling a larger number of stations. The introduction of time slots reduces the probability of collisions, allowing the system to operate more efficiently even as the number of stations increases.<br/>

### **<br/>Carrier Sense Multiple Access Protocols**
- Carrier Sense Multiple Access Protocols - CSMA
- Protocols in which stations listen for a carrier and act accordingly are called carrier sense
protocols

### **<br/>The working principle of the 1 - Persistent CSMA Protocol**
- A station first listens to the channel to see if anyone else is transmitting at that moment.
- If the channel is idle, the stations sends its data.
- If the channel is busy, the station waits until it become idle. Then the station transmits a frame.
- If a collision occurs, the station waits a random amount of time and starts all over again.
- The protocol is called 1-persistent because the station transmits with a probability of 1 when it finds the channel idle.


### **<br/>Nonpersistent CSMA**
A second carrier sense protocol is nonpersistent CSMA.<br/>
- A station senses the channel when it wants to send a frame, and if no one else is sending, the station begins doing so itself.
- However, if the channel is already in use, the station does not continually sense it for the purpose of seizing it immediately upon detecting the end of the previous transmission.
- Instead, it waits a random period of time and then repeats the algorithm.

### **<br/>P-persistent CSMA**
The last carrier sense protocol is p-persistent CSMA.<br/>
It applies to slotted channels and works as follows:<br/>
- When a station becomes ready to send, it senses the channel.
- If it is idle, it transmits with a probability p.
- With a probability q = 1 - p, it defers until the next slot.
- If that slot is also idle, it either transmits or defers again, with probabilities p and q.
- This process is repeated until either the frame has been transmitted or another station has begun transmitting.
- If there had been a collision - it waits a random time and starts again.
- If the station initially senses that the channel is busy, it waits until the next slot and applies the above algorithm.

### **<br/>Compare between CSMA/CA and CSMA/CD**
|  CSMA/CA |  CSMA/CD |
|---|---|
|1.Collision avoidance using handshake mechanism before transmission.|1.Collision detection after transmission.|
|2.Efficiency is Higher - avoids wasted transmissions.|2.Efficiency is Lower - no handshake delay.|
|3.Scalability is Better - handles larger networks effectively.|3.Scalability is Worse - performance degrades with increased collisions.|
|4.Complexity is Higher - requires RTS/CTS packets and additional logic.|4.Complexity is Lower - simpler implementation.|
|5.It use in Wireless LANs (Wi-Fi), Bluetooth,etc.|5.It use in Wired LANs (Ethernet).|


### **<br/>Explain the token ring as a collision-free protocol.**

Here's an explanation of the token ring protocol as a collision-free protocol:<br/>
Devices (nodes) are connected in a physical ring, forming a continuous loop. A special control frame called a "token" circulates around the ring. Only the node holding the token can transmit data. Only one device can transmit at a time, eliminating collisions and ensuring reliable data transfer.<br/>
**`Working Principle:`**<br/>
- The token continuously travels around the ring, passing from one device to the next.
- A device with data to send waits for the token to arrive. Upon receiving the token, the device:<br/>
    - Places its data on the ring.<br/>
    - Passes the token to the next device in the ring.<br/>
- All devices on the ring read the data as it passes by. The intended recipient copies the data.
- The original sender removes its data from the ring. It then passes the token to the next device, allowing others to transmit.

### **<br/>Explain the basic bitmap protocol as a Collison free protocol with necessary figures.**
Bit map protocol is collision free Protocol. In bitmap protocol method, each contention period consists of exactly N slots. If any station has to send frame, then it transmits a 1 bit in the corresponding slot. For example, if station 2 has a frame to send, it transmits a 1 bit to the 2nd slot.<br/>In general, Station 1 Announce the fact that it has a frame to send by inserting a 1 bit into slot 1. In this way, each station has complete knowledge of which station wishes to transmit. There will never be any collisions because everyone agrees on who goes next. Protocols like this in which the desire to transmit is broadcasting for the actual transmission are called Reservation Protocols.





