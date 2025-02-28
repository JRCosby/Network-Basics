# Network-Basics

**Servers**

**Web Servers**

A software app or hardware device that processes client requests, for example, a web browser, and serves web pages, files, or other resources to users. 

**Application Servers**

A software framework or platform that runs and manages applications, such as web-based or enterprise applications. Application Servers typically handle business logic or database processing. 

**Database Servers**

Database servers provide database services to other computers or clients. They store, retrieve, and manage data in a database.

**Network**

A network is a connection of computers, servers, and other devices. This allows them to communicate and store data.



**Types of Networks**

**LANs(Local Area Network)**

Used to connect computers and devices within a limited area. This allows for fast data transfer and resource sharing.

**WANs(Wide Area Network)**

Connects computers and devices over a larger geographical area—for example, cities, states, and countries. The internet is also a good example of a WAN; the internet connects millions of networks worldwide. In other words, WANs connect LANs over larger distances, linking networks in different cities or countries.

**WiFi(Wireless Network)**
Provides connectivity without the need for physical cables.

**VPN(Virtual Private Network)**

Creates secure connections over the internet, allowing remote users to access a network as if they were directly connected to it. VPNs are crucial for remote work and protecting data in transit.
Networking Basics

**Switches**

Switches make sure data goes directly to the device it’s meant for.

**Routers**

Routers decide the best path for data to travel between networks.

**Firewalls**

Firewalls have rules, like a set of instructions. Some rules, Ingress, decide what can enter. Whereas, some rules, Egress, decide what can leave. There’s also a feature called “Stateful Inspection” that watches what is happening. Firewalls are like guards monitoring the entrance and exit of your network. Firewalls also make sure different parts can communicate with each other. 



**The OSI Model**

The Open Systems Interconnection Model is a conceptual framework used to understand network connection in seven layers. 

**The OSI Model has two main components:**

1. A seven-layer structure.
2. A group of protocols. 

**Application Layer(High Level API): Layer 7**

Interfaces directly with apps responsible for network services like email, file transfers, web browsing, etc.

**Presentation Layer: Layer 6**

Translates data between the network and application formats and is responsible for data encryption/decryption and compression. For example, HTML, DOCX, avi, etc.

**Session Layer: Layer 5**

Manages communication sessions and continuous exchange of info in the form of multiple transmissions between nodes.

**Transport Layer(Segment Datagram): Layer 4**

Reliable transmission of data segments, including segmentation, acknowledgements, and multi-plexing. Examples are TCP, UDP, SSL, etc.

**Network Layer(Packet): Layer 3**

Manage a multi-node network, including addressing, routine, and traffic control.

**Data Link Layer(Frame): Layer 2**

Node-to-node data transfer, error detection, and connection from the physical layer. Examples include Ethernet 802.11, Token Ring, etc.

**Physical Layer(Bit, Symbol): Layer 1**

Transmission and reception of all bit streams over a physical medium. Examples are wires, antennas, etc.
