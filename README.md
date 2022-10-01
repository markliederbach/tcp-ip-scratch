# TCP/IP - The Hard Way <!-- omit in toc -->
The following provides examples for performing the TCP/IP handshake, in order to teach the fundamentals of how it works.

- [Getting Started](#getting-started)
  - [Dependencies](#dependencies)
- [Background](#background)
  - [What is TCP?](#what-is-tcp)
  - [What is IP?](#what-is-ip)
# Getting Started
This project relies on the following requisite packages to bootstrap your development environment.
- [Taskfile](https://taskfile.dev) - used to run common tasks and install dependencies

## Dependencies
Start by running `task deps` to install all necessary packages.


# Background
## What is TCP?
The [Transmission Control Protocol (TCP)](https://en.wikipedia.org/wiki/Transmission_Control_Protocol) is a network communication standard first developed in 1973, which provides the fundamental backbone for most network traffic today. Unlike other protocols like [UDP](https://en.wikipedia.org/wiki/User_Datagram_Protocol), it provides a reliable, error-corrected data stream upon which applications can communicate and transfer information across a network.
![TCP State Diagram](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f6/Tcp_state_diagram_fixed_new.svg/1920px-Tcp_state_diagram_fixed_new.svg.png)
## What is IP?
[Internet Protocol (IP)](https://en.wikipedia.org/wiki/Internet_Protocol) is a separate [OSI layer](https://en.wikipedia.org/wiki/OSI_model) which sits atop the transport layer, providing data encapsulation and routing metadata for the information being sent. The primary components of the IP network layer are the header (source/destination addressing plus metadata), and the payload (information being sent).
