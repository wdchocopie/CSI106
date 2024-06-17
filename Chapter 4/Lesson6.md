# Computer, network and internet

----
# Network
* Defined as the interconnection of a set of devices capable of communication
* A device can be a host \(endpoint\) such as computer, desktop, etc....
* A device cab can connect device such as router, which connects network to network, a switch which connect devices toghether.
* Device in network are connected using wired or wireless.

----
# LAN - Local Area Network
* A LAN is usually privately owned and connects some hosts in a single office, building, campus
* A LAN can be 2 PC's and a printer.
* Each host in a lan has an identifier, an address, that unique in LAN
* A Packet sent by a host to another host carries both source host and destination host address

----
# WAN - Wide Area Network
* Multiple LAN connect toghether
* Wider geographical span
* Interconnection: Switches, Routers, Modems.

----
# Router, Modem, Hub, Switch
* Modem: this device translates the signal from your internet service provider (ISP) into a format that your devices can understand and vice versa. It acts as the bridge between your home network and the wider internet.  
* Router: This device manages the traffic between your home network and the internet. It directs data packets to the correct devices on your network and also performs security functions like firewalls.  You can think of it as a traffic cop for your network, making sure data gets to where it needs to go.
* Switch: A network switch connects devices on a local area network (LAN). It provides a dedicated connection for each device, unlike a hub which broadcasts data to all connected devices. This reduces congestion and improves overall network performance.
* Hub: This is a legacy device that is no longer commonly used. It acts as a central connection point for devices on a network, simply transmitting any data it receives out to all connected devices. This can be inefficient as all devices receive all data, even if it’s not meant for them.

| Device  | Function                                                                                           | Network Layer | Number of Ports | Data Transmission Method |
|---------|----------------------------------------------------------------------------------------------------|---------------|-----------------|--------------------------|
| Switch  | Connects multiple devices within a local network, intelligently forwards data to the correct device| Data Link     | Multiple        | Uses MAC addresses       |
| Hub     | Connects multiple devices within a local network, broadcasts data to all devices                   | Physical      | Multiple        | Broadcasts data          |
| Modem   | Modulates and demodulates signals for data transmission over telephone lines or cable systems      | Physical      | Usually 1       | Converts digital data to analog and vice versa |
| Router  | Connects multiple networks, routes data packets between them, typically provides internet access   | Network       | Multiple        | Uses IP addresses        |


----
# Internet
* An internet is two or more networks that can communicate with each other and is composed of thousands of interconnected networks
![image] -> Backbones -> network provider -> customers
* ISP = Backbones, Network provider

----
# TCP/IP
* A protocol defines the rules that both the sender and receiver and all intermediate devices need to follow to be able to communicate effectively in internet
* Need a protocol for each layer
* TCP/IP \(Transmission Control Protocol / Internet Protocol\)
![Image Layer in TCP IP protocol suite]

----
# Addressing and packet name
* Communication neeed sources and destination adresses.
* Normally have 4 layers.
  * Physical layer does not need addresses.
* There is a relationship between the layer, the address used in that layer, and the packet name at that layer.

----
# Application layer
* The fifth layer of the TCP/IP protocol is called application layer
* Start from the fifth -> first
* Provides services to user.
* Using Logical connection

----
# Application-Layer Paradigms
* Client-server paradigm
* Peer to peer Paradigm
* Should both application programs be able to:
   * Request services?
   * Provide service?

----
# Applications of standart Client-Server
* WWW \(World Wide Web\)
* HTTP \(HyperText Transfer Protocol\)
* FTP \(File Transfer Protocol\)
* SSH \(Secure Shell\)
* Email

----
# Dns in the Internet
* Is a Protocol
* 3 Diffrent sections: 
   * Generic domains
   * Country domains
   * Inverse domains

----
# Transport Layer
* The transport layer acts as a liaison between a client program and a server progam

----
# Addressing Port Number
* Port number in range: 0 -> 65,535 \(bits\)
* Client programs port greater than 1023

----
# Translayer-Layer Protocol
* UDP -> Less Secure
* TCP -> More Secure

----
# Network layer
* Accepts a packet from a transport layer, encapsulated the packet in a datagram, and deliver the packet to data-link layer

----
# Packetizing at network layer
* Packetizing: Encapsulating the payload \(data recieve from upper layer\) in a network-layer packet at the source and decapsulating the payload at the end
* Pack -> Send -> unpack

----
# Network-layer Protocols
* The main protocol is called the Internet Protocol \(IP\).
* IPv4 - IPv6
* Common notation to show an IP address: Base 2, Base 256, Base 16

----
# Data Link Layer
* Nodes and Links: refer to the two end hosts and the routers as nodes and the networks in between as links . 

----
# Wred LANs: Ethernet
![Image]
----
# Wireless Ethernet
* Wireless Ethernet or WiFi is a wireless LAN. Two kinds of services: the basic service set (BSS) and the extended service set (ESS). The second service uses an extra device (access point or AP) that serves as a switch for connection to other LANs or WANs. 
 
![Image]

----
# Cable Service
* Refers to TV
![Image]

----
# Wireless WAN: WiMax
* Cellular data / Satelite network

![Image]

----
# Physical Layer
* The role of the physical layer is to transfer the bits received from the data-link layer and convert them to electromagnetic signals for transmission. 
 
