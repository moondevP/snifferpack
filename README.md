# Network Packet Sniffer

A simple network packet sniffer implemented in Python using the `scapy` library. This tool captures packets on a specified network interface and performs basic analysis to detect potentially malicious activity, such as ARP spoofing.

## Features

- **Packet Sniffing**: Capture packets on a specified network interface.
- **ARP Spoofing Detection**: Monitor ARP packets for anomalies and discrepancies in IP-MAC address mappings.
- **Logging**: Log detected ARP spoofing incidents for further analysis.

## Requirements

- Python 3.x
- `scapy` library

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/network-packet-sniffer.git
   cd network-packet-sniffer
