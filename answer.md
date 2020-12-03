Q2-What is the difference between Telnet and SSH?Explain following status code:-
Telnet is the protocol that allows a user to communicate with a remote device. It is used mostly by network administrators to remotely access and manage devices.
SSH is the protocol used to remotely access and manage a device. SSH uses encryption, which means that all data transmitted over a network is secure from eavesdropping.

Startus code and meaning-:
--------------------------
200- OK The request has succeeded
204-There is no content to send for this request, but the headers may be useful. The user-agent may update its cached headers for this resource with the new ones.
400-The server could not understand the request due to invalid syntax.
401-Although the HTTP standard specifies "unauthorized", semantically this response means "unauthenticated". That is, the client must authenticate itself to get the requested response.
403-The client does not have access rights to the content; that is, it is unauthorized, so the server is refusing to give the requested resource. Unlike 401, the client's identity is known to the serve
500-The server has encountered a situation it doesn't know how to handle.
503-The server is not ready to handle the request. Common causes are a server that is down for maintenance or that is overloaded. 

Q3-ACID Properties-:
ACID Properties are used for maintaining the integrity of database during transaction processing. ACID in DBMS stands for Atomicity, Consistency, Isolation, and Durability.

Atomicity: A transaction is a single unit of operation. You either execute it entirely or do not execute it at all. There cannot be partial execution.
Consistency: Once the transaction is executed, it should move from one consistent state to another.
Isolation: Transaction should be executed in isolation from other transactions (no Locks). During concurrent transaction execution, intermediate transaction results from simultaneously executed transactions should not be made available to each other. (Level 0,1,2,3)
Durability: · After successful completion of a transaction, the changes in the database should persist. Even in the case of system failures.

Q4-Difference between  Latency and throughout
 Latency indicates how long it takes for packets to reach their destination. 
 Throughput is the term given to the number of packets that are processed within a specific period of time

Latency is used to measure how quickly these conversations take place. The more latency there is, the longer these conversations take to hold.
The level of latency determines the maximum throughput of a conversation. Throughput is how much data can be transmitted within a conversation.

Q5-3-way handshake-

TCP 3-way handshake or three-way handshake or TCP 3-way handshake is a process which is used in a TCP/IP network to make a connection between server and client.
Syn use to initiate and establish a connection
ACK helps to confirm to the other side that it has received the SYN.
SYN-ACK is a SYN message from local device and ACK of the earlier packet.
FIN is used for terminating a connection.
TCP handshake process, a client needs to initiate the conversation by requesting a communication session with the Server
In the first step, the client establishes a connection with a server
In this second step, the server responds to the client request with SYN-ACK signal set
In this final step, the client acknowledges the response of the Server
TCP automatically terminates the connection between two separate endpoints.

Q7-What is the difference between Telnet and SSH?
Telnet is the protocol that allows a user to communicate with a remote device. It is used mostly by network administrators to remotely access and manage devices.
SSH is the protocol used to remotely access and manage a device. SSH uses encryption, which means that all data transmitted over a network is secure from eavesdropping.

Q8-Explain symmetric and asymmetric encryption.
While communicating on an unsecured medium like the internet, you have to be careful about the confidentiality of the information you are sharing with other. The are two techniques use to preserve the confidentiality of your message, Symmetric and Asymmetric Encryption. The fundamental difference that distinguishes symmetric and asymmetric encryption is that symmetric encryption allows encryption and decryption of the message with the same key.
It is simpler and faster.
The two parties exchange the key in a secure way.

On the other hand, asymmetric encryption uses the public key for the encryption, and a private key is used for decryption. To acknowledge some more differences between symmetric and asymmetric encryption have a look at the comparison chart shown below.

Q9-What is an A record, an NS record, a PTR record, a CNAME record, and MX record?
The DNS records for each domain are stored in its active DNS zone. The active DNS zone is where the name servers of the domain are pointed. The DNS records of domains with active DNS zone here can be managed from Site Tools > Domain > DNS Zone Editor. The most commonly used DNS record types are:

A – specifies IP addresses corresponding to your domain and its subdomains.
MX – specifies where the emails for your domain should be delivered.
CNAME – specifies redirects from your domain’s subdomains to other domains/subdomains.
TXT – used to store text-based information related to your domain. Most commonly used for storing SPF data.
SPF – a mail validation protocol used to prevent email spoofing.
AAAA – it maps a domain name to the IP address (IPv6) of the computer hosting the domain.
SRV – stands for Service Record and it specifies on only an IP but also a port.