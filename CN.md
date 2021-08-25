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

     

5. **DHCP** - Dynamic Host Configuration Protocol, helps enabled devices to get IP address without any manual configuration.

   

6. **ARP** -  Address Resolution Protocol, used to find MAC address from the IP address.

   

7. **VPN** - Virtual Private Network, 

   * used to connect offices in different geographical locations remotely

   * used for secure transactions and confidential data transfer

   * encrypts the internet traffic and disguises the online identity

     

8. 
