# How The Internet Works Infographic
An infographic that simplifies and illustrates the way the internet works.

## ISP (Internet Service Provider)
An organization that provides its subscribers with services accessing and using the Internet.

### Clients
A client is a computer or a device that makes requests to a server. Clients can be Desktops, Phones, Tablets, Apps, etc.

### Servers
A server is both a piece of hardware, the computer itself, and a piece of software that responds to requests. Examples of servers would be Database Servers, DNS Servers, File Servers, Mail Servers, Web Servers, Gaming Servers.

### Protocols
Protocols are basically languages that Clients and Servers speak in order to communicate. Some of those common protocols are the following: HTTP, HTTPS, FTP, SMTP & WebSocket.

### HTTP (Hyper Text Transfer Protocol)
HTTP is a protocol followed in the web to GET, PUT, DELETE and POST data from and to servers. HTTP is how clients and servers transfer webpages on the web.

### HTTPS
The s stands for secure. It means communication between a client and a server is private and encrypted.

TCP/IP
Responsible for transmitting data efficiently on the internet.

TCP = How
Transmission Control Protocol splits data up into packets and puts them back together at their destination.

IP = Where
Internet Protocol, tells the packets where to go and where they should return to.

URL (Uniform Resource Locator)
URI (Uniform Resource Identifier)
URL  =  DomainName.TLD/URI

Domain Names
Domain names are organized from right to left, it means each label or section between the dots, specifies a subdomain of the section to its right. For example, in yoursite.com, .com is the Top Level Domain, teamtreehouse is its subdomain

TLDs
.com .net .org .edu .us .ca .uk
Top Level Domains are considered a parent to domain names.

DNS (Domain Name Server)
Servers use numbers to locate each other (i.e. IP addresses). The DNS system is the address book of the internet. Domain Name Servers are servers that match the domain name requested by a client with the IP address of the server hosting the requested content then forwards the request to that server.

Resolving Name Servers 
A resolving name server is usually provided by your ISP. Resolving name servers directly find out information about the root, top level domains (TLD) and authoritative name servers. It also speeds up queries by caching results locallly. At least two resolving name servers must be specified that the resolver should query. 

Resolver 
A resolver is nothing but a standard set of routines in the Operating Systems (or C library) which provides access to the Internet Domain Name System. You can set 3 name servers. If there are multiple servers, the resolver library queries them in order. If no nameserver entries are present, the default is to use the name server on the local machine.

IP Address (Internet Protocol Address)
A unique number that identifies every computer connected to the internet. The IP protocol uses IP addresses to route the TCP packets.

In order to transmit the data to the correct location, the IP protocol also adds a small header of information to the packet (e.g. the source IP address and the destination IP address.), just like TCP.

IPv4
Nearly everything on the web uses Internet Protocol version 4. It is comprised of four numbers, each between 0 and 255, separated by dots (e.g. 0.0.0.0 , 255.255.255.255, etc.). It has the capacity to identify about 4.3 billion unique addresses.

IPv6
The new IP, Internet Protocol version 6 will support every person on Earth having billions of devices connected to the web at once.

Routers
Routers connect multiple networks. Routers are intermediary devices that route data packets destined for places outside the local network, and move them to other routers using protocols until all the data reaches its correct destination. Routers bridge the gap between computers across towns, states, and countries.

Routing Tables
Routers determines the best path (route) to send each data packet from one router to the next. Each router keeps information about other routers in what’s called a routing table.

When a packet is received, a router examines the packet and determines where it needs to go next, using the information from the routing table, which contains at least three bits 
