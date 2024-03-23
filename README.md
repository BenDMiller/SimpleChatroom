# Overview

This is a simple messaging application written to help gain experiences with networking in Python, and sockets.

Utilizing network protocols and sockets, a server is set up to handle communication between each client that is in the messaging chatroom.

[Software Demo Video](https://youtu.be/5T1WbnhR7hc)

# Network Communication

We utilized a server-client model for this program.

Utlizing TCP protocol, we set up the network to work on the port 1234.

The messages delivered are encoded to and decoded from utf-8.

# Development Environment

Tools:
- VS Code

Language and Libraries:
- Python
- Socket
- Select
- Sys
- Errno

# Useful Websites

* [Python Programming](https://pythonprogramming.net/)

# Future Work

* Allow for asynchronous message receiving, not waiting on first sending a message
* Create a simple GUI for messaging
* Fix the IP address and port to work for all computers