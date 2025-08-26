# MlengelaTCPServerClient
A Simple TCP Server and Client program. The network connection between the host and the port, represented by their assigned numbers written in a tuple. The client makes a connection to servers, and the servers wait for the incoming connections and provide a service (e.g., web, mail, etc). In their connection cycle, these network programs use a request and response model based on messages. Referring to the GET method, the client sends a request message (e.g., HTTP). The server sends back a response message. The format of the response message depends on the application. As the name of the project suggests, Streams(TCP) and Datagrams(UDP) are the basic types of communication. With TCP, computers establish a connection with each other and read/write data in a continuous stream of bytes as a file, and this is what this project specifically does.   
# Library Used:
* Socket():
  
  Provides a low-level interface for network connection. These are the [functionalities](https://docs.python.org/3/library/socket.html) of the socket module for creating a socket. This project implements them for establishing client and server connections. 
# Features:
* Socket creation by importing the socket library.
* Address families and protocols.
* Sockety type
* TCP connection
* Server for listening for incoming connections
* Client for making outgoing connections
# Usage: 
# Contributions: 
I welcome contributions to the program! Who knows? It might not run on the user's end. If you have any suggestions, bug reports, or any kind of feature requests, please contact me or submit a pull request.
