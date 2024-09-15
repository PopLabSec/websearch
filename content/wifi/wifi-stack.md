+++
title = "Wi-Fi Stack"
description = ""
weight = 1
+++


{{< lead >}}
Imagine the Wi-Fi stack as a layered cake, each layer responsible for a specific task in ensuring smooth wireless communication.
{{< /lead >}}

## Description

{{ $image := .Resources.GetMatch "wifistack.png" }}
{{ with $image }}
  <img src="{{ .RelPermalink }}" width="{{ .Width }}" height="{{ .Height }}">
{{ end }}

## Physical Layer (PHY)
The foundation handles the actual transmission of radio waves.

- Encoding and decoding data into electrical signals.
- Modulating and demodulating signals to carry information.
- Frequency hopping to avoid interference.
## Media Access Control (MAC) Layer
The traffic cop manages access to the shared wireless medium.   

- Assigning time slots to devices for transmission.
- Detecting and resolving collisions.
- Handling frame synchronization.
## Logical Link Control (LLC) Layer
The bridge connects the MAC layer to the higher-level network protocols.

- Flow control to prevent overwhelming the receiver.
- Error detection and correction.
- Multiplexing data from multiple applications.
## Internet Protocol (IP) Layer
The navigator provides addressing and routing for data packets.

- Assigning IP addresses to devices.
- Routing packets through the internet.
- Fragmenting and reassembling packets if necessary.
## Transport Layer
The delivery service ensures reliable data transfer between applications.

- Establishing connections between devices.
- Flow control to prevent data loss.
- Error detection and correction.

{{< childpages >}}