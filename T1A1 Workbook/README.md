# T1A1 Workbook
## Megan Van Der Weide. Student number: 12048

## Q1. Identify and explain common and important components and concepts of web development markup languages

answer here. 

## Q2. Define the features of the following technologies that are essential in terms of the development of the internet. Explain how each technology has contributed to the development of the internet.

- packets
  
  Packets are distributing messages by chopping up big messages into smaller pieces to pass these through flexible routes with spare capacity. This was to solve the issue of big files transferring causing links to be tied up in the process. This allows for efficiency and fault-tolerant. (reference computer networks youtube)

  An example of when we see corrupt or missing packets would be when skype gets glitchy during a meeting. It has discarded some of the UDP. 5:15 to clean up on (The internet youtube)

 - IP addresses (IPv4 and IPv6)
  
    Packets must conform to a standard format called an internet protocol or 'IP'. (reference computer networks youtube).Every message requires an address of destination which is an IP Header. In addition each message has a weight limit per packet, which is why it is broken up. Each computer connected to a network receives an IP address. (reference computer networks youtube). Each packet has destination address on the network so routers know where to forward them. The packet also requires the User Datagram Protocol which has extra information including a port number to direct the packets information to the correct program running and a checksum to check the data. (reference youtube the internet)

 - routers and routing
  
    Routing is adding a communication line between computer networks. The technology of routing has developed from a physical switch board called circut switching. Another is message switching which has the message move between different stops by routing... hop count. ... Create flexiblity, reduction of costs, exclusivity, reduce routing errors from hop count/limit?. Speedy and reliable delivery by bouncing between different routes using congestion control. 

  Packet switching is a routing approach of using packets. Creates Desentialised or single point of failure. 
  (reference computer networks youtube)

 - domains and DNS
  
    Domains are... Domains are used to reduce collisions of data being transmitted from one to another. When you have a few computers on one shared ethernet cable, or one collision domain.. or two collision domain. This is how computer networks are constructed including the internet. (reference computer networks youtube)

    Domain Name System. When a user requestes a sight, the first thing that happens is the server performs a look up in the DNS server. This takes the domain name input and replies with the matching IP address. connects the user to the domain internet browser which connects to the DNS server this DNS server.. connects IP.. webbrowsers opens a TCP connection to the webserver... The DNS server consults registery to reply with the address. The DNS server looks up the IP addresses in relation to the domain names typed in by the user. This information of addresses is stored in a tree data structure such as top level, second level and sub-domains. (youtube internet)

    internet of things - keeping up with growth? 

  ## Q3. Define the features of the following technologies that are essential in terms of the development of the internet.Explain how each technology has contributed to the development of client and server communication over the internet (50 - 150 words for each technology)

   - TCP

    Transmission Control Protocol. When messages cannot handle dropping any packets whilst transferring a message to a program. Contains destination port checksum and .. Suquenstial numbers of the packets, allow for receiving computer to put it in order - piece together correctly. Once receive packet and data passes the checksum it sends back an acknloedgement to sending computer. Sender will then next packet. Duplicates discarded. Sends many packets even with outstanding acknowledgements which increases bandwith as it's not waiting on direct communication. TCP adjusts rate of packets being sent by it's rate of sending and acknowledging which allows for congestion control. Used for time critical applications like multi player computer games to avoid lag. (youtube the internet)
  Packets arriving out of order. TCP/IP
  DNS server - IP address - connects to TCP ... 

 - HTTP and HTTPS
  
 - web browsers (requests, rendering and developer tools)
    (the internet youtube) Open system connection: application layer and presentation layer. Application on computer that lets you talk to web servers. Requests and renders content of media. 
    
    Web browsers introduced features like hyperlinks, images embedded in the web pages. Web browsers were used to find things. Instead of web directories - search engines were developed. 

    Search engines were developed from the search term appearing on the page to (content). Auhority of backlinks from other reputable sites. 
