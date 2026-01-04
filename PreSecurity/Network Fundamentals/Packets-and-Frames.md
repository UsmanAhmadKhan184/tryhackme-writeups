# Packets and Frames

## Overview
Data sent over a network is broken into small pieces
called packets and frames to ensure efficient and
reliable transmission.

## What is a Packet?
A packet is a unit of data used at the **Network layer**
that contains:
- Source IP address
- Destination IP address
- Payload data

## What is a Frame?
A frame is a unit of data used at the **Data Link layer**
that contains:
- Source MAC address
- Destination MAC address
- Encapsulated packet

## What I Learned
- Packets operate at Layer 3 (Network)
- Frames operate at Layer 2 (Data Link)
- Frames carry packets inside them
- Data is encapsulated and decapsulated during transmission

## Why This Matters in Cybersecurity
Packet and frame analysis is essential for:
- Network sniffing
- Detecting malicious traffic
- Understanding attacks like MITM

## Key Takeaway
Packets and frames explain how data actually moves
across a network and how attackers analyze traffic.
