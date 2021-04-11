
Q1
When data is formatted into packets, packet switching is possible and the bandwidth of the communication medium can be better shared among users than with circuit switching. A packet consists of control information and user data, which is also known as the payload.

Q2
to the communication between two network endpoints without a prior arrangement in which one network endpoint simply sends a message to the other. At the sending end, the device transmits the unit of data before ensuring that the receiving end’s device is ready.

Q3
A server socket listens on a single port. All established client connections on that server are associated with that same listening port on the server side of the connection. 

Q4
Yes we can create multiple sockets in order to communicate with clients concurrently.

Q5
it is possible, and not unusual, to process both input and output streams of a socket on the same thread and supporting a single connection at a time allows the Runnable requirement to be dropped, i.e. no additional thread is needed for the handler and the ServerSocket accept call is postponed until the current connection is closed.

observer pattern :- is a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods.

listener :- is a function that is invoked when a particular event occurs, typically with an event object containing information about the event. 

event handler is a callback routine that operates asynchronously and handles inputs received into a program (events).

event-driven programming is a programming paradigm in which the flow of the program is determined by events such as user actions (mouse clicks, key presses), sensor outputs, or message passing from other programs or threads. Event-driven programming is the dominant paradigm used in graphical user interfaces and other applications (e.g., JavaScript web applications) that are centered on performing certain actions in response to user input. This is also true of programming for device drivers (e.g., P in USB device driver stacks[1]).

event loop is a programming construct or design pattern that waits for and dispatches events or messages in a program. The event loop works by making a request to some internal or external "event provider" (that generally blocks the request until an event has arrived), then calls the relevant event handler ("dispatches the event"). The event loop is also sometimes referred to as the message dispatcher, message loop, message pump, or run loop.

event queue is a repository where events from an application are held prior to being processed by a receiving program or system.

call stack is a stack data structure that stores information about the active subroutines of a computer program.

Emit In Node.js an event can be described simply as a string with a corresponding callback. An event can be "emitted" (or in other words, the corresponding callback be called) multiple times or you can choose to only listen for the

Subscribe is used in software architecture to decouple modules that would otherwise be dependent of each other by using a message queue paradigm.

database is an organized collection of data, generally stored and accessed electronically from a computer system. Where databases are more complex they are often developed using formal design and modeling techniques.



SOCKET IO

Socket.IO is a library that enables real-time, bidirectional and event-based communication between the browser and the server. It consists of:

a Node.js server: Source | API
a Javascript client library for the browser (which can be also run from Node.js): Source | API

io.protocol
(Number)
The protocol revision number (currently: 5).

The protocol defines the format of the packets exchanged between the client and the server. Both the client and the server must use the same revision in order to understand each other.

Manager
The Manager manages the Engine.IO client instance, which is the low-level engine that establishes the connection to the server (by using transports like WebSocket or HTTP long-polling).

ocket.connected
(Boolean)
Whether or not the socket is connected to the server.

socket.disconnected
(Boolean)
Whether or not the socket is disconnected from the server.


