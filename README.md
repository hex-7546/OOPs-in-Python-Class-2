# OOPs-in-Python
Notes and Keywords - 07/08/2025

# Keywords
## ⚙️ Computation
Closed Source:
  - x86 - Intel and AMD
  - ARM

Open Source:
  - RISC V

Processing Units:
  - CPU (Central Processing Unit)
  - GPU (Graphics Processing Unit)
  - TPU (Tensor Processing Unit)
  - DPU (Data Processing Unit)
  - QPU (Quantum Processing Unit)

## 🌐 Networking
  - Internet <br>
  Inter means between two or more different entities and net means connection or web. So a connection between two or more computer systems or devices (smartphones, desktops, data center etc) is known as the Internet. Any device accessing the internet uses a public IP address that is assigned to it
  - Intranet <br>
  - LAN (Local Area Network) <br>
  - MAN (Metropolitan Area Network) <br>
  - WAN (Wide Area Network) <br>
  - IP (Internet Protocol) <br>
  - Private IP <br>
  - Public IP <br>
  - VPN (Virtual Private Network) <br>
  - ISP (Internet Service Provider) <br>
  - DNS (Domain Name System) <br>
  - Local Host <br>
  - OSI Models (Open Systems Interconnection) <br>
  - MAC Address <br>
  - NIC (Network Interface Card)
  - SmartNIC
  - DPDK (Data Plane Development Kit)
  - SR IOV (Single Root I/O Virtualization)
  - TSMC (Taiwan Semiconductor Manufacturing Company)
  - ASML (Photolithography equipment manufacturing company)
  - SSL (Secure Sockets Layer)

## 💾 Storage
Primary Storage (Volatile storage):
  - RAM (Random Access Memory)
  - ROM (Read Only Memory)

Secondary Storage (Non Volatile storage):
  - HDD (Hard Disk Drive)
  - SSD (Solid State Drive)
  - Optical Disk (Eg: CD, DVD etc.)
  - USB Flash Drive

Tertiary Storage:
  - Cloud Storage

## Operating System
Closed Source:
  - Windows (Microsoft)
  - Mac (Apple)

Open Source:
  - Linux (Linux Foundation) <br>
  Linux is actually a kernel and not a operating system. Several operating system has been made on it. The <b>Debian</b> family is the most popular one and in that too <b>Ubuntu</b> is particularly beginner friendly. You can also try Arch Linux if you dare 💀

## Bare Metal System
A computer system that runs the processes directly on the hardware without the help of any operating system. It speeds up the process and is much more efficient and optimized compared to other systems with OS running on them

# Notes

## IP
Internet protocol is a set of instructions/standards/rules that is followed by the internet. IP address is the address given to particular network so that it can communicate with other devices via the internet. It is of two types IPv4 and IPv6. IPv6 is more modern and newer while IPv4 is the traditional way of giving addresses. To address the limitations of IPv4 we are switching towards IPv6

## OSI (Open System Interconnection) Model
It is the building block of internet. It determines how different networking systems communicate with each other. It consists of seven layers.
<img width="771" height="493" alt="image" src="https://github.com/user-attachments/assets/eea89afc-4e4b-4fca-93e5-7913fbfd76ab" />

- L1 - Physical Layer
  Deals with physical connection with devices. Includes cables, switches and electrical signals that travel over them
- L2 - Data Link Layer
  Deals with data transfer over the physical layer. It is here that the NIC lies which facilitates the communication between two or more devices
- L3 - Network Layer
  This layer deals with routing data packets across different networks. Determines the best path for the data to travel from source to destination. VPN's (Virtual Private Network) operates in this layer which routes the device's connection through its own servers before it reaches the destination. It thus allows masking of IP Address
- L4 - Transport Layer
  This layers ensures data is transferred securely and relaibly. It breaks down large data packets into smaller ones for transmission and then reassembles them at the destination. The SSL works here which basically encrypts the link between the server and the client ensuring the data transmitted remains private and secure
- L5 - Session Layer
  This layer enables, manages and terminates connections between applications
- L6 - Presentation Layer
  this layer translates data between application layer and the network
- L7 - Application Layer
  Top most layer of the model where end-user apps and services operate which includes web browsing etc.


<b>Mac Address: </b>
Address given to a specific device which signifies various information related to it is known as mac address


