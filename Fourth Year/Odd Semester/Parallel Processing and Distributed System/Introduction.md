### Chapter 1 (Introduction)

### **<br/>What is Computer Network?**
A computer network is a Collection of autonomous computers interconnected by a
single technology. Two computers are said to be interconnected if they can exchange information. The connection need not be via a copper wire; fiber optics, microwaves, infrared, and communication satellites can also be used.

### **<br/>Application of Computer Network**
  - Business Application
  - Home Application
  - Mobile Users
  - Social Issues

### **<br/>Some negative and positive uses of computer network**
Positive Uses:<br/>
- Efficient communication
- Information access on the internet
- Collaborative work environment
- Resource sharing
- E-commerce
- Remote access<br/>

Negative Uses:<br/>
- Cyber crime
- Unauthorized access to sensitive data
- Spreading Fake News and Propaganda
- Social media and online game Addiction

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
There are two types of transmission technology that are in widespread use.<br/>
- Broadcast links.
- Point-to-point links.

### **<br/>Define broadcast, multicast, unicast, and point-to-point  transmission technology.**
- Unicast<br/>
    `Definition:` Unicast is a one-to-one communication method where data is sent from one sender to one specific receiver. It is the most common form of communication in networks and the internet. In unicast, the sender and the receiver have a dedicated, individual connection.
- Broadcast<br/>
    `Definition:` Broadcast is a one-to-all communication method where data is sent from one sender to all devices in the network. It is a broadcast mechanism where the information is distributed to all connected devices, and each device decides whether to process the information based on its own criteria.
- Multicast<br/>
    `Definition:` Multicast is a one-to-many or many-to-many communication method where data is sent from one sender to a specific group of receivers. In multicast, the sender transmits data to a multicast group, and only the devices that are part of that group receive the data. It's a more efficient way to transmit data to multiple recipients without sending separate copies to each one.
- Point-to-Point<br/>
    `Definition:` Point-to-Point communication refers to a direct, dedicated connection between two devices. It is a communication model where data is exchanged between a single sender and a single receiver without involving other devices. 


### **<br/>Can you distinguish between point-to-point and broadcast link?**
`Point-to-Point Link:`<br/>
  - Point-to-point links involve a dedicated communication channel between exactly two devices.
  - Data transmission occurs exclusively between the two connected devices.
  - This type of communication forms a direct, one-to-one connection.
- Example: Leased lines, VPN connections, USB cables.<br/>

`Broadcast Link:`<br/>
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

### **<br/>There are two reference model**
- OSI (Open System Interconnection)
- TCP/IP

### **<br/>The OSI reference model**
- OSI stands for Open System Interconnection.
- It is a model for understanding and designing a newtork architecture that is flexible, robust, and interoperable.
- Developed by International Standards Organization(ISO).
- The OSI model is not a protocol.
- It is only a guideline and hence it is referred as OSI reference model.

#### `Purpose of the OSI model:`<br/>
- To show how to facilitate communication between different systems without requiring changes to the logic of the underlying hardware and software.
- The OSI model was never fully implemented.

### **<br/>Layers in the OSI Reference Model**
- Application layer
- Presentation layer
- Session layer
- Transport layer
- Network layer
- Data Link layer
- Phisical layer<br/>
Order of the layer is very important. We cann't change the order of layer.

### **<br/>What do you know about the primary concern of the Physical Layer?**
The physical layer is concerned with transmitting raw bits over a communication channel..

### **<br/>The design issues are applicable for a physical layer**
- When one side sends as a 1 bit, it is received by the other side as a 1 bit, not as a 0 bit.
- What electrical signals should be used to represent a 1 and a 0.
- How many nenoseconds a bit lasts.
- Whether transmission may proceed simultaneously in both directions,
- How the initial connection is established.
- How it torn down when both sides are finished,
- How many pins the network connector has, and
- What each pin is used for.


### **<br/>Three concepts are central to the OSI model**
- Services.
- Interfaces.
- Protocols.<br/><br/>
The **`service`** definition tells what the layer does, not how entities above it access it or how the layer works.<br/>
A layer's **`interface`** tells the processes above it how to access it. It specifies what the parameters are and what results to expect.<br/>
The peer **`protocols`** used in a layer are the layer's own business. It can use any protocols it wants to as long as  it gets the job done. It can also change them at will without affecting software in higher layers.


### **<br/>The reasons for the failure of the OSI reference model**
- Bad timing.
- Bad technology.
- Bad implementations.
- Bad politics.<br/><br/>
**`Bad timing:`** When the OSI came around, this model was perfectly released regarding research, but at that time TCP/IP model was already receiving huge amounts of investments from companies and manufacturers did not feel like investing in OSI model. So, there were no initial offerings for using OSI technique. While every company waited for any of other companies to firstly use this model technique, but unfortunately none of company went first to use this model. This is first reason to failure the OSI reference model.<br/><br/>
**`Bad technology:`** The second reason that OSI never caught on is that both the model and the protocols are flawed. The choice of seven layers was more political than technical, and two of the layers(session and presentation) are nearly empty, whereas two other ones (data link and network) are overfull.<br/><br/>
**`Bad implementations:`** The OSI model is extraordinarily and much more complex due to which initial implementations were very slow, huge, and unwidely. This is the third reason due to which OSI became synonymous with poor quality in early days.<br/><br/>
**`Bad Politics:`** OSI model was not associated with UNIX. This was fourth reason to failure of the OSI model. On that time, TCP/IP was largely and closely associated with Unix, which helps TCP/IP to get popular in academia.

### **<br/>Differences between OSI Model and TCP/IP Model**
| OSI Model | TCP/IP Model |
|---|---|
| OSI stands for Open Systems Interconnection.| TCP/IP stands for Transmission Control Protocol/Internet Protocol.|
| It has 7 layers.| It has 4 layers.|
| It is low in usage.| It is mostly used.|
| It is vertically approached.| It is horizontally approached.|
| Delivery of the package is guaranteed in OSI Model.| Delivery of the package is not guaranteed in TCP/IP Model.|
| Replacement of tools and changes can easily be done in this model.| eplacing the tools is not easy in this model.|
| It is less reliable than TCP/IP Model.| It is more reliable than OSI Model.|

### **<br/>What is ARPANET?**
ARPANET, stands for Advanced Research Projects Agency Network, was the first wide-area packet-switched network with distributed control. It was first to implement TCP/IP protocols. It was basically beginning of Internet with use of these technologies. It was designed with a basic idea in mind that was to communicate with scientific users among an institute or university. It played a crucial role in paving the way for the modern internet.<br/><br/>
Characteristics of ARPANET :<br/>
- It is basically a type of WAN.<br/>
- It used concept of Packet Switching Network.<br/>
- It used Interface Message Processors(IMPs) for sub-netting.<br/>
- ARPANETs software was split into two parts- a host and a subnet.<br/>


### **<br/>Structure of ARPANET**
The subnet would consist of minicomputers called IMPs (Interface Message Processors) connected by 56-kbps transmission lines. For high reliability, each IMP would be connected to at least two other IMPs. The subnet was to be a datagram subnet, so if some lines and IMPs were destroyed, message could be automatically rerouted along alternative paths.<br/>
Each node of the network was to consist of an IMP and a host, in the same room, connected by a short wire. A host could send messages of up to 8063 bits to its IMP, which would then break these up into packets of at most 1008 bits and forward them independently toward the destination. <br/>
The software was split into two parts: subnet and host. The subnet software consisted of the IMP  end of the host-IMP connection, the IMJP-IMP protocol, and a source IMP to destination IMP protocol designed to improve reliability. 


### **<br/>Define Internet**
The Internet is a worldwide interconnected network of hundreds of thousands of computers of various types that belong to multiple networks. It use certain common protocols and provide centain common services.
