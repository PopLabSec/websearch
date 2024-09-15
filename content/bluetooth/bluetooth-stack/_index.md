+++
title = "Bluetooth Stack"
description = ""
weight = 1
+++

{{< lead >}}
Bluetooth stack is a software layer that enables Bluetooth devices to communicate with each other. It consists of various components that handle different aspects of Bluetooth communication, including:

{{< /lead >}}



### 1. Host Controller Interface (HCI)

The lowest layer of the stack.
Provides a standardized interface between the host processor (e.g., a smartphone, laptop) and the Bluetooth controller (a specialized chip).
Handles data transmission and control commands between the host and the controller.

### 2. Link Layer

Manages the physical connection between Bluetooth devices.
Handles tasks such as frequency hopping, packet formatting, error correction, and power management.
Ensures reliable data transmission over the wireless channel.

### 3. Logical Link Control and Adaptation Layer (L2CAP)

Provides multiplexing, segmentation, and reassembly of data packets.
Allows different protocols (e.g., TCP/IP, SDP) to coexist on a single Bluetooth connection.
Handles flow control and error recovery.

### 4. Service Discovery Protocol (SDP)

Enables Bluetooth devices to discover and advertise available services.
Provides a mechanism for clients to find and connect to specific services on other devices.
Uses a database to store information about services and their attributes.

### 5. Attribute Protocol (ATT)

Used for accessing and manipulating attributes within a Bluetooth service.
Defines the structure and operations for reading, writing, and notifying attributes.
Provides a framework for building various Bluetooth profiles and services.

### 6. Security Manager

Handles security aspects of Bluetooth communication.
Manages authentication, encryption, and key exchange.
Ensures data confidentiality and integrity.

### 7. Profiles

Define specific use cases and functionalities for Bluetooth devices.
Provide a set of rules and procedures for how devices should interact in different scenarios.

#### Examples of profiles include
- Hands-Free Profile (HFP) for hands-free calling
- Headset Profile (HSP) for wireless headsets
- Advanced Audio Distribution Profile (A2DP) for high-quality audio streaming
- Personal Area Network Profile (PAN) for creating a personal network

{{< childpages >}}