### Chapter 1 (Introduction)

### **<br/>What is Computer Network?**
A computer network is a Collection of autonomous computers interconnected by a
single technology. Two computers are said to be interconnected if they can exchange information. The connection need not be via a copper wire; fiber optics, microwaves, infrared, and communication satellites can also be used.

### **<br/>Application of Computer Network**
  - Business Application
  - Home Application
  - Mobile Users
  - Social Issues

### **<br/>Define Distributed System**
A distributed System is a collection of autonomous computer systems that are physically separated but are connected by a centralized computer network. The autonomous computers will communicate among each system by sharing resources and files and performing the tasks assigned to them.

### **<br/>How "Distributed System" is different from a "Computer Network"?**
A computer network is a Collection of autonomous computers interconnected by a single technology. On the other hand, a Distributed System is a collection of autonomous computer systems that are physically separated but are connected by a centralized computer network.<br/>
The primary goal of computer networks is data communication and resource sharing between independent devices. On the other hand, the primary goal of a distributed system is to achieve a common task or goal  by coordinating the activities of multiple independent computers.<br/>
Computer network provides services like file sharing, email, internet access, and remote printing. On the other hand, a Distributed system offers features like scalability, parallel processing, fault tolerance, etc.


### **<br/>Can you clarify the mechanism of the client-server model in the context of a computer network?**
If we look at the client-server model in detail, we see that two processes are involved, one on the client machine and one on the server machine. Communication takes the form of the client process sending a message over the network to the server process. The client process then waits for a reply message. When the server process gets the request, it performs the requested work or looks up the requested data and sends back a reply.


### **<br/>Business application of Computer Network**
#### `Primary goal`
- Resource sharing:<br/>
The goal is to make all programs equipment, and especially data available to anyone on the network without regard to the physical location of the resource or the user.
    - Share printer
    - More important than sharing physical resources - sharing data.
    - Share customer records.
 - VPNs(Virtual Private Networks)
 - Client-Server Model
    - web application<br/>
#### `Secondary Goal`
 - Powerful communication medium
      - Email, VOIP, Video calling
 - Desktop Sharing
     - TeamViewer<br/>
#### `Tertiary Goal`<br/>
  - E-commerce(electronic commerce)


### **<br/>Home Application of Computer Network**
- Connectivity:
  - to remote computers.
  - home users can access information, communicate with other people, and buy products and services with e-commerce.
  - people can surf the net for fun, movies, chatting, etc.
  - people can surf the net for news portals.
  - people can surf the net for research like IEEE, Springers, etc.
- Instant messaging.
- Twitter, Facebook, WhatsApp.
- E-commerce.

### **<br/>Mobile User Application of Computer Network**
- Connectivity
- Mobile Hotspot
- Texting, sms
- GPS
- M-commerce
- NFC(Near Field Communication)

### **<br/>What kinds of transmission technology we use?**
There are two types of transmission technology that are in widespread use.
    - Broadcast links.
    - Point-to-point links.

### **<br/>Define broadcast, multicast, unicast, and point-to-point  transmission technology.**
- Unicast
    `Definition:` Unicast is a one-to-one communication method where data is sent from one sender to one specific receiver. It is the most common form of communication in networks and the internet. In unicast, the sender and the receiver have a dedicated, individual connection.
- Broadcast
    `Definition:` Broadcast is a one-to-all communication method where data is sent from one sender to all devices in the network. It is a broadcast mechanism where the information is distributed to all connected devices, and each device decides whether to process the information based on its own criteria.
- Multicast
    `Definition:` Multicast is a one-to-many or many-to-many communication method where data is sent from one sender to a specific group of receivers. In multicast, the sender transmits data to a multicast group, and only the devices that are part of that group receive the data. It's a more efficient way to transmit data to multiple recipients without sending separate copies to each one.
- Point-to-Point
    `Definition:` Point-to-Point communication refers to a direct, dedicated connection between two devices. It is a communication model where data is exchanged between a single sender and a single receiver without involving other devices. 


### **<br/>Can you distinguish between point-to-point and broadcast link?**
`Point-to-Point Link:`
    - Point-to-point links involve a dedicated communication channel between exactly two devices.
    - Data transmission occurs exclusively between the two connected devices.
    - This type of communication forms a direct, one-to-one connection.
    - Example: Leased lines, VPN connections, USB cables.
`Broadcast Link:`
    - Broadcast links involve a communication channel where data from one sender is transmitted to all devices in the network.
    - Data is broadcasted to all devices on the network, and each device decides whether to process the information based on its own criteria.
    - This type of communication is more one-to-all or one-to-many, where one sender reaches multiple receivers.
    - Example: Wi-Fi signals, radio broadcasts, public announcements.

### **<br/>Classification of computer network by its scale? How?**
| Interprocessor Distance | Processors located in same |  Example | 
|---|---|---|
|    1m  | Square meter | Personal area network |
|   10m | Room | Local area network | 
|  100m |  Building | Local area network | 
|  1km  |  Campus | Local area network | 
|  10km | City | Metropolitan area network |
|  100km  | Country | Wide area network |
|  1000km | Continent | Wide area network |
|  10000km | Planet | The Internet |

### **<br/>Define LAN, MAN, and WAN.**
`LAN:` A Local Area Network(LAN) is a computer network that interconnects computers within a limited area such as a residence, school, laboratory, university campus, or office building.

`MAN:` A Metropolitan Area Network(MAN) is a computer network that interconnects users with computer resources in a geographic region of the size of a metropolitan area(city).

`WAN:` A Wide Area Network(WAN) is a telecommunications network that extends over a large geographical area for the primary purpose of computer networking.

### **<br/>Difference between LAN, MAN, and WAN.**
| LAN | MAN | WAN |
|---|---|---|
|1. LAN stands for Local Area Network.  |1. MAN stands for Metropolitan Area Network.|1. WAN stands for Wide Area Network.|
|2. Operates in small areas such as rooms, buildings, and campuses.|2. Operates in large areas such as a city.|2. Operates in large areas such as country or continent.|
|3. The transmission speed of a LAN is high.|3. The transmission speed of a MAN is average.|3. The transmission speed of a WAN is low.|
|4. Design and maintenance  are easy.|4. Design and maintenance are more difficult than LAN.|4. Design and maintenance are more difficult than LAN as well MAN.|


### **<br/>Define protocol and protocol stack**
A protocol is an agreement
between the communicating
parties on how communication is to
proceed.<br/>
A list of protocols used by a certain system, one protocol per layer, is called a protocol stack.

### **<br/>Define network architecture**
A set of layers and protocols is called a network architecture.

### **<br/>Define peer**
The entities comprising the corresponding layers on different machines are called peers. The peers may be processes, hardware devices, or even human beings. In other words, it is the peers that communicate by using protocol.<br/>
A five-layer network is illustrated in Fig. 1

### **<br/>Design Issues for the layers**
- Reliability
  - uses codes for error detection.
  - error correction
  - They are used at low layers
- Routing
  - Finding a working path through a network.
  - addressing or naming.
  - internetworking.
- Resource allocation
  - who will get priority
  - flow control
  - Quality of service.
- Confidentiality
  - authentication
  - Integrity

