# Introduction to Python Socket Programming
## What are sockets ?
Sockets and the socket API are used to send messages across a network. They provide a form of inter-process communication ([IPC](https://en.wikipedia.org/wiki/Inter-process_communication)). The socket is the software abstraction used to represent the "terminals" of a connection between two machines.
> For a given connection, there's a socket on each machine, and you can imagine a hypothetical "cable" running between the two machines with each end of the "cable" plugged into a socket. 
> -- <cite>[Bruce Eckel (Thinking in Java)][1]</cite>

A socket is one endpoint of a two-way communication link between two programs running on the network. A socket is bound to a port number so that the TCP layer can identify the application that data is destined to be sent to.

## TCP


[1]: https://www.amazon.com/Thinking-Java-4th-Bruce-Eckel/dp/0131872486
