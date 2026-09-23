## PM5 - Zenmap / Network Scanning

Networkwalks Cybersecurity Internship | B083| Week 2

## Practical Overview

This practical focused on Zenmap, the graphical interface for Nmap, to perform network discovery within a controlled local laboratory environment.
The exercise covered identifying the following:
```
local network configuration.
Determining the LAN scope.
Discovering live hosts.
Identifying their IP and MAC address.
```

## Practical Objective

The practical objective was to gain experience in the following:
```
Installing and launch Zenmap on Windows.
Identify the local IP address and LAN subnet.
Discover live hosts within the subnet.
Determine the number of responsive hosts.
Identify the IP addresses of a discovered host.
Identify the MAC addresses associated with the discovered host. 
```

## Tools

The tools used were:
```
Zenamp.
Nmap.
Windows Command Prompt.
Windows PC
```

## Task 1

## Zenmap Installation

Zenmap was downloaded and installed on the Windows Pc. 
The application was successfully launched and used for the network discovery exercise.

## Task 2

## Identify Local IP Address & LAN Subnet

Windows Command Prompt was opened and the following command was executed:
```
ipconfig

The command displayed the system's IPv4 address, subnet mask, and default  gateway.
```
Local IPv4 Address: 172.20.10.11

The network information obtained from "ipconfig" was used to establish the appropriate LAN scanning scope.

## Task 3

## Discover Live Hosts

Zenmap was used to perform host discovery across the identified local network.
The scan identified the following responsive hosts:
```
172.20.10.1
172.20.10.2
172.20.10.11
```

## Task 4

## Number Of Live Hosts

Total live hosts discovered was Three(3)
The scan returned three responsive hosts within the examined network scope.

## Task 5

## IP Addresses Of Live Hosts
```
| Host | IP Address | Status |
| --- | --- | --- |
| Host 1 | 172.20.10.1 | Live |
| Host 2 | 172.20.10.2 | Live |
| Host 3 | 172.20.10.11 | Live |
```

## MAC Addresses

The scan provided MAC adress information for the discovered hosts where available
```
| IP Address | MAC Address |
| --- | --- |
| `172.20.10.1` | `EA:FB:E9:53:71:64` |
```


## Analysis

This practical demonstrated the basic workflow of local network reconnaissance. The ipconfig command was first used to establish the host's network configuration and determine the information required for the scanning scope. Zenmap was then used to identify responsive systems within the network and retrieve available network identifiers.
The discovery of the three live hosts provided an initial view of the systems accessible within the local network environment.

## Skills
```
Network Discovery.
Host Enumeration.
IP Adress Identification.
Subnet Identification.
MAC Address Identification.
Network Reconnaissance.
Zenmap.
Nmpa.
Windows Command Line.
Technical documentation.
```

## Evidence

## Author

Chibueze Ifeoma | Networkwalks Cybersecurity Internship| B083| Week 2
