# Talk & NameServer - Socket Programming

This project is the result of a socket programming workshop during the 3rd semester. The objective was to build a deep understanding of network communication and distributed systems through the implementation of a chat client and an associated name service.

## Features
* **Multi-threaded Chat:** Implementation of a Talk client/server that, via thread management (`SenderThread` and `ReceiverThread`), allows asynchronous message exchange (full-duplex).
* **TCP & UDP Implementation:** Experience with both connection-oriented (TCP) and connectionless (UDP) communication.
* **NameServer (Service Discovery):** A central name service that tracks the network identification of active clients, allowing users to find each other via nicknames instead of IP addresses.
* **Client Handling:** Server logic capable of handling multiple clients simultaneously via dedicated `ClientHandlers`.

## Technologies
* **Language:** Java
* **Networking:** Java Sockets (TCP/UDP), IP/Port handling
* **Concurrency:** Java Threads (Multi-threading)
* **Tools:** IntelliJ IDEA, Git

## Structure
The project is divided into iterations:
1. **Version 1:** Simple sequential TCP chat.
2. **Version 2:** Thread-based chat for simultaneous sending/receiving.
3. **Version 3:** Integration of a name service with both TCP and UDP support.

## Authors
Karsten Kirkegaard, Rune Hyldgaard Jensen, and Sidse Borch Mogensen
