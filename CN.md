1. * **UNICAST** - Message is sent from a *source to single destination*.
   * **ANYCAST** - Message is sent from a *source to any of the given destination*. Content Delivery Networks (CDN)
   * **MULTICAST** - Message is sent from *some subset to another*. Video Conferencing
   * **BROADCAST** - Message is sent to *all the nodes in the network*. DHCP and ARP

   

2. **What is Stop-and-Wait Protocol?**

   In Stop and wait protocol, a sender after sending a frame waits for an acknowledgment of the frame and sends the next frame only when acknowledgment of the frame has received.

   

3. **What is Piggybacking?**

   Piggybacking is used in bi-directional data transmission in the network layer (OSI model). The idea is to improve the efficiency.

   

4. **What happens when you type a URL in the web browser?**

   * If the content of the typed URL is in the cache and fresh, then display the content.

   * Else find the IP address for the domain so that a TCP connection can be set up. Browser does a DNS lookup.

   * Browser needs to know the IP address for a URL so that it can set up a TCP connection. This is why browser needs DNS service. The browser first looks for URL-IP mapping browser cache, then in OS cache. If all caches are empty, then it makes a recursive query to the local DNS server.  The local DNS server provides the IP address.

   * Browser sets up a TCP connection using three-way handshake.

   * Browser sends a HTTP request.

   * Server has a web server like Apache, IIS running that handles incoming HTTP request and sends an HTTP response.

   * Browser receives the HTTP response and renders the content.

     

5. **VPN** - Virtual Private Network, 

   * used to connect offices in different geographical locations remotely

   * used for secure transactions and confidential data transfer

   * encrypts the internet traffic and disguises the online identity

     

6. **Network Topology**  

   * ***Bus Topology*** - <img style="vertical-align:middle" src="https://github.com/44aayush/Placement_Q-A/blob/main/assets/bus_topo.PNG"/>

   * ***Star Topology*** - <img style="vertical-align:middle" src="https://github.com/44aayush/Placement_Q-A/blob/main/assets/star_topo.PNG" />

   * ***Ring Topology*** - <img style="vertical-align:middle" src="https://github.com/44aayush/Placement_Q-A/blob/main/assets/ring_topo.PNG" />

   * ***Mesh Topology*** - <img style="vertical-align:middle" src="https://github.com/44aayush/Placement_Q-A/blob/main/assets/mesh_topo.PNG" />

   * ***Tree Topology*** - <img style="vertical-align:middle" src="https://github.com/44aayush/Placement_Q-A/blob/main/assets/tree_topo.PNG" />

   * ***Hybrid Topology***

     

7. **OSI Reference Model** 

   - *Application* - sends data of any size to the transport layer

   - *Presentation* - translates data from/to encoded format

   - *Session* - establishes connection/session between different machines, Dialogue Control (Duplexity)

   - *Transport* - takes care of segmentation and reassembly

   - *Network* - control operations of subnet, feedback messaging via ICMP

   - *Data Link* - error detection via CRC, implement protocols like CSMA/{CD,CA}

   - *Physical* - transmit bits

     

8. **HTTP and HTTPS** 

   * HTTP is the Hypertext Transfer Protocol which defines the set of rules and standards on how the information can be transmitted on the World Wide Web (WWW). ***Stateless Protocol*** where each command is independent with respect to the previous command. 

   * HTTPS is the Hypertext Transfer Protocol Secure or Secure HTTP. On top of HTTP, SSL/TLS protocol is used to provide security.

     

9. **DNS** 

   * Domain Name System

   * Decentralized and hierarchical naming system for devices/services connected to the Internet.

   * Translates the domain names to their corresponding IPs.

     

10. **TCP** 

    * Transmission Control Protocol/Internet Protocol

    * Connection-Oriented Protocol

    * Reliable

    * Slow transmission

    * Packets order can be preserved

    * Three way handshake 

    * Error Checking mechanism

    * HTTP, FTP, Telnet, SMTP, HTTPS

      

11. **UDP** 

    * User Datagram Protocol, used for multicasting and broadcasting

    * Connectionless Protocol

    * Less reliable

    * Faster transmission compared to TCP

    * Packets order is not fixed 

    * No three way handshake

    * No error checking mechanism

    * DNS, RIP, SNMP, RTP, BOOTP, TFTP, NIP

      

12. **ICMP** 

    * Internet Control Message Protocol

    * Network layer protocol used for error handling

      

13. **DHCP**  

    * Dynamic Host Configuration Protocol
    * helps enabled devices to get IP address without any manual configuration.

    

14. **ARP**

    * Address Resolution Protocol

    * Used to find MAC address for the corresponding IP address

      

15. **SMTP**

    * Simple Mail Transfer Protocol

    * Sets the rule for communication between servers

    * Supports both End-to-End and Store-and-Forward methods

      

16. **Subnet** 

    * A subnet is a network inside a network achieved by the process called subnetting which helps divide a network into subnets.

    * Used for getting a higher routing efficiency and enhances the security of the network

      

17. **Firewall**

    * Network security system that is used to monitor the incoming and outgoing traffic and blocks the same based on the firewall security policies.

      

18. | Name                                | Port No. |
    | ----------------------------------- | -------- |
    | ICMP echo                           | 7        |
    | File Transfer Protocol (FTP) - Data | 20       |
    | File Transfer Protocol (FTP)        | 21       |
    | SSH                                 | 22       |
    | Telnet                              | 23       |
    | SMTP                                | 25       |
    | DNS                                 | 53       |
    | DHCP Services                       | 67       |
    | DHCP Client                         | 68       |
    | HTTP                                | 80       |
    | HTTPS                               | 443      |



19. **HUB** 
    * Layer-1 device (Physical Layer), deals with the data in the form of bits or electrical signals.
    * Used to connect devices on the same network only.
    * Half-duplex mode of communication.
    * Broadcasts the data packets, hence less securea and induces traffic on the channel due to collision.
    * Not an intelligent device, it forwards the incoming messages to other devices without checking for error or processing it.
        ** ***Active Hub*** - Also called Concentrator. It analyses data packets and amplify the transmission signals, if needed.
        ** ***Passive Hub*** - Forwards the data as it is.



20. **BRIDGE** 
    * Layer-2 device, interpretes data in the form of data frames.
    * In Physical Layer - Acts as a Repeater - regenerates the weak signals
      In Data-Link Layer - Checks the MAC address on the data frames for transmission
    * Also has Filtering capacity - discard faulty data frames 
        ** ***Transparent Bridge*** - Work as transmission medium between two devices
        ** ***Routing Bridge*** - Have Unique identity, source can send data packets through specific bridges
        


21. **SWITCH** 
    * Layer-2 connecting devices, acts as a multiport bridge. Hence, provides bridging functionality with greater efficiency.
    * Maintains a SEitch table, which has all the MAC address of the devices connected to it.
    * Full-duplex 
    * Intelligent device with filtering capabilities and has multiple collision domains , so it has atleast or no collision.
        ** ***Store n Forward Switch*** - Does not forward unless data frames are errorless, RELIABLE
        ** ***Cut-through Switch*** - Forward without any checks as soon as it starts receiving.
        ** ***Fragment-Free Switch*** - Combination of Store n Forward and Cut-through Switch,  checks only 64bytes before forwarding.
        ** ***Adaptive Switch*** - Choose anyone of the above switch as per needs.
    
   

22. **ROUTER**
    * Layer-3 network connecting device, interpretes data in the form of data packets.
    * Gateway of a network
        ** ***Static Routing*** - The path of the data is manually set.
        ** ***Dynamic Routing*** - Various algorithms are used to find the best and shortest path for transmission.



24. **ROUTING PROTOCOLS
    * Distance Vector
         - Selects best path on the basis of hop counts to reach the destination network
         - RIP => Routing Information Protocol

    * Link State / Shortest Path First
         - Knows about Internetworks than Distance vector 
         - - Neighbor Table => information about neighbor of the routers
         - - Topology Table => best and backup route to dest
         - - Routing Table => best route to dest
         - OSPF => Open Shortest Path First

    * Advanced Distance Vector
         - Hybrid protocol
         - EIGRP => Enhanced Interior Gateway Routing Protocol
         - - Acts as a link state routing protocol as it uses the concept of Hello protocol for neighbor discovery and forming adjacency
         - - Acts as distance vector routing protocol as it learned routes from directly connected neighbors


    

    

    
