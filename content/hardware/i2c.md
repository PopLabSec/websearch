+++
title = "I2C Protocol"
description = ""
image = "https://offensive-wireless.com/wp-content/uploads/2021/05/Universal-Radio-Hacker.png" 
weight = 2
+++

I2C (Inter-Integrated Circuit) is a widely used serial communication protocol for connecting multiple devices on a single bus. It's designed for short-distance communication, typically within a single PCB or between devices close to each other.

{{< lead >}}
I'm a lead paragraph. That means I'm more important. And you can see that.
{{< /lead >}}

## Usage
I2C (Inter-Integrated Circuit) is a serial communication protocol widely used for short-distance communication between integrated circuits (ICs) on a printed circuit board (PCB). It's a simple, flexible, and easy-to-implement protocol that requires only two wires:

- 1. SDA (Serial Data): Carries the data to be transmitted.
- 2. SCL (Serial Clock): Generates the clock signal that synchronizes data transfer.

## How I2C Works

Initiation: A device (master) initiates communication by pulling the SCL low and then the SDA low.
Addressing: The master sends a 7-bit address to the desired slave device. The slave device acknowledges the address by pulling the SDA low.
Data Transfer: The master sends data bytes to the slave, and the slave acknowledges each byte by pulling the SDA low.
Stop Condition: The master terminates communication by pulling the SDA high while SCL is high.

## Key Features of I2C

Multi-master capability: Multiple devices can act as masters and initiate communication.
Multi-slave capability: A single master can communicate with multiple slaves on the same bus.
Open-collector output: Devices can share the SDA and SCL lines without requiring external pull-up resistors.
Simple addressing: Each device has a unique 7-bit address.
Low-speed operation: Typically operates at speeds up to 100 kHz, but can reach higher speeds (up to 1 MHz) in some implementations.

## Common Applications of I2C

Sensor communication: Connecting sensors like temperature, humidity, and light sensors to microcontrollers.
EEPROM and flash memory: Programming and reading data from non-volatile memory devices.
Real-time clocks: Setting and reading time and date information.
LCD displays: Controlling the display of text and graphics.
Audio codecs: Interfacing with audio devices for playback and recording.
In summary, I2C is a versatile and widely used protocol for short-distance communication between ICs. Its simplicity, flexibility, and low-cost implementation make it a popular choice for various electronic applications.


{{< youtube 6IAkYpmA1DQ >}}