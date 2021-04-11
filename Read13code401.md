Q1
Yes, websockets are bidirectional. An important consequence is that you may efficiently push data from the server to the client. Underlying sockets are just kept open (or reopened when needed if they couldn't be kept open).

Q2
server will attach to an HTTP server so it can serve its own client code through /socket.io/socket.io.js.

That said, although you don't need an HTTP server to regular websockets, there's no denying that the websocket protocol was designed with HTTP in mind (as to allow HTTP and websocket servers to co-exist on the same TCP port).

Q3
The event gets passed to the server through websockets. Its a tcp connection from the browser to the server. The connection is full duplex meaning the server can send real time data to the client and vise versa.

Q4
server Sent Events are a standard allowing browser clients to receive a stream of updates from a server over a HTTP connection without resorting to polling. Unlike WebSockets, Server Sent Events are a one way communications channel - events flow from server to client only.

Q5
Client may perform several sends. On the server side TCP/IP stack will store the data in the internal buffer. Then server code will call ReceiveAsync again and read the data up.

Because of this, you can often see situations when client makes 3 operations, sending 10 bytes of data each, while server can read 30 bytes using 1 read (receive) operation.

Q6
The operating system has a receive buffer which holds packets that have been received from the network but not yet recv()ed by the application. If that buffer fills up packets will be lost. You don't have to be in a recv() call when packets arrive, though you should make sure you call it often enough to keep the buffer from overflowing.

socket When a computer program needs to connect to a local or wide area network such as the Internet, it uses a software component called a socket. The socket opens the network connection for the program, allowing data to be read and written over the network. It is important to note that these sockets are software, not hardware, like a wall socket. So, yes, you have a much greater chance of being shocked by a wall socket than by a networking socket.

Socket.IO is a library that enables real-time, bidirectional and event-based communication between the browser and the server.

WebSocket is a computer communications protocol, providing full-duplex communication channels over a single TCP connection. The WebSocket protocol was standardized by the IETF as RFC 6455 in 2011, and the WebSocket API in Web IDL is being standardized by the W3C.

clinet The client knows the hostname of the machine on which the server is running and the port number on which the server is listening. To make a connection request, the client tries to rendezvous with the server on the server's machine and port. The client also needs to identify itself to the server so it binds to a local port number that it will use during this connection. This is usually assigned by the system.

server runs on a specific computer and has a socket that is bound to a specific port number. The server just waits, listening to the socket for a client to make a connection request.

OSI model is a conceptual model that characterises and standardises the communication functions of a telecommunication or computing system without regard to its underlying internal structure and technology. Its goal is the interoperability of diverse communication systems with standard communication protocols.

TCP model does not consider the specifics of formatting and presenting data and does not define additional layers between the application and transport

TCP  is one of the main protocols of the Internet protocol suite. It originated in the initial network implementation in which it complemented the Internet Protocol (IP). Therefore, the entire suite is commonly referred to as TCP/IP. TCP provides reliable, ordered, and error-checked delivery of a stream of octets (bytes) between applications running on hosts communicating via an IP network. Major internet applications such as the World Wide Web, email, remote administration, and file transfer rely on TCP, which is part of the Transport Layer of the TCP/IP suite. SSL/TLS often runs on top of TCP.

UDP is one of the core members of the Internet protocol suite. With UDP, computer applications can send messages, in this case referred to as datagrams, to other hosts on an Internet Protocol (IP) network. Prior communications are not required in order to set up communication channels or data paths.

packet is a small segment of a larger message. Data sent over computer networks*, such as the Internet, is divided into packets. 

















