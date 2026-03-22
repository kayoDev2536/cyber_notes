# Networking Fundamentals

This note covers:
- Types of networks based on geographic size
- IP address classes
- Basic IP addressing concepts

---

# Types of Networks (by Geography)

## LAN (Local Area Network)
- Covers a small area such as a home, office, or school
- High speed and low latency
- Example: a home or office Wi-Fi network

---

## MAN (Metropolitan Area Network)
- Covers a city or a large campus
- Connects multiple LANs together

---

## WAN (Wide Area Network)
- Covers large geographic areas such as countries or continents
- The Internet is the largest example of a WAN

---

## PAN (Personal Area Network)
- Covers a very small area (a few meters)
- Example: Bluetooth connection or mobile hotspot

---

# IP Address Classes (IPv4)

## Class A
- Range: 1.0.0.0 – 126.255.255.255
- Used for large networks
- Default subnet mask: 255.0.0.0

---

## Class B
- Range: 128.0.0.0 – 191.255.255.255
- Used for medium-sized networks
- Default subnet mask: 255.255.0.0

---

## Class C
- Range: 192.0.0.0 – 223.255.255.255
- Used for small networks
- Default subnet mask: 255.255.255.0

---

## Class D
- Range: 224.0.0.0 – 239.255.255.255
- Used for multicast

---

## Class E
- Range: 240.0.0.0 – 255.255.255.255
- Reserved for experimental use

---

# Private IP Address Ranges

These addresses are used inside local networks and are not accessible directly from the internet:

- 10.0.0.0 – 10.255.255.255
- 172.16.0.0 – 172.31.255.255
- 192.168.0.0 – 192.168.255.255

---

# Basic IP Concepts

## IP Address
- A unique identifier for a device on a network
- Example: 192.168.1.1

---

## Subnet Mask
- Defines which part of the IP address represents the network and which part represents the host

Example:
IP: 192.168.1.10  
Subnet Mask: 255.255.255.0

---

## CIDR Notation
- A modern way to represent subnet masks

Example:
192.168.1.0/24

---

## Network Address
- The first address in a subnet
- Identifies the network itself

Example:
192.168.1.0

---

## Broadcast Address
- The last address in a subnet
- Used to send data to all devices in the network

Example:
192.168.1.255

---

# Key Takeaways

- Networks are categorized by size: PAN, LAN, MAN, WAN
- IP classes define address ranges (historical concept)
- Private IP addresses are used within local networks
- Subnetting helps divide networks efficiently
- CIDR is the modern standard for IP addressing
