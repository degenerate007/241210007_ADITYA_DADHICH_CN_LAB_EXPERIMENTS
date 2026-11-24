<div align="center">

# 🌐 Computer Networks Lab

**A complete record of my Computer Networks (CN) laboratory experiments** — Cisco Packet Tracer simulations, lab reports, and Python socket programs.

![Experiments](https://img.shields.io/badge/Experiments-13-blue)
![Tool](https://img.shields.io/badge/Cisco-Packet%20Tracer-1BA0D7?logo=cisco&logoColor=white)
![Language](https://img.shields.io/badge/Python-3-3776AB?logo=python&logoColor=white)

</div>

---

## 👤 Student Information

| | |
|---|---|
| **Name** | Aditya Dadhich |
| **Roll No.** | 241210007 |
| **Subject** | Computer Networks Lab (CN Lab) |
| **GitHub** | [@degenerate007](https://github.com/degenerate007) |
| **Repository** | [241210007_ADITYA_DADHICH_CN_LAB_EXPERIMENTS](https://github.com/degenerate007/241210007_ADITYA_DADHICH_CN_LAB_EXPERIMENTS.git) |

---

## 📑 Table of Contents

- [Experiment Index](#-experiment-index)
- [Repository Structure](#-repository-structure)
- [Tools & Requirements](#-tools--requirements)
- [How to Open the Simulations](#-how-to-open-the-simulations)
- [Running the Python Programs](#-running-the-python-programs)
  - [Experiment 10: TCP & UDP](#experiment-10--tcp--udp-client-server)
  - [Experiment 11: Multi-client Server](#experiment-11--multi-client-socket-programming)
- [Author](#-author)

---

## 🧪 Experiment Index

| # | Experiment | Report | Packet Tracer | Code |
|:-:|---|:-:|:-:|:-:|
| 1 | [Network Cables](1_Network_cabels) | [📄 PDF](1_Network_cabels/1_Network_cabels.pdf) | [🖧 .pkt](1_Network_cabels/1_Network_cabels.pkt) | — |
| 2 | [Basic Network Commands](2_Basic_Network_Commands) | [📄 PDF](2_Basic_Network_Commands/2_Basic_Network_Commands.pdf) | [🖧 .pkt](2_Basic_Network_Commands/2_Basic_Network_Commands.pkt) | — |
| 3 | [Network Devices](3_Network_Devices) | [📄 PDF](3_Network_Devices/3_Network_Devices.pdf) | [🖧 .pkt](3_Network_Devices/3_Network_Devices.pkt) | — |
| 4 | [Networking & IP Addressing](4_Networking_IP) | [📄 PDF](4_Networking_IP/4_Networking_IP.pdf) | [🖧 .pkt](4_Networking_IP/4_Networking_IP.pkt) | — |
| 5 | [LAN Connection](5_LAN_Connection) | [📄 PDF](5_LAN_Connection/5_LAN_Connection.pdf) | [🖧 .pkt](5_LAN_Connection/5_LAN_Connection.pkt) | — |
| 6 | [Router Configuration](6_Router_confi) | [📄 PDF](6_Router_confi/6_Router_confi.pdf) | [🖧 .pkt](6_Router_confi/6_Router_confi.pkt) | — |
| 7 | [Peer-to-Peer (P2P)](7_P2P) | [📄 PDF](7_P2P/7_P2P.pdf) | [🖧 .pkt](7_P2P/7_P2P.pkt) | — |
| 8 | [NAT](8_NAT) | [📄 PDF](8_NAT/8_NAT.pdf) | [🖧 .pkt](8_NAT/Exp08_NAT.pkt) | — |
| 9 | [Routing Protocols](9_Routing_Protocols) | [📄 PDF](9_Routing_Protocols/9_Routing_Protocols.pdf) | [🖧 .pkt](9_Routing_Protocols/9_Routing_Protocols.pkt) | — |
| 10 | [TCP / UDP Client-Server](10_TCP_UDP_Client_Server) | [📄 PDF](10_TCP_UDP_Client_Server/10_TCP_UDP_Client_Server.pdf) | [🖧 .pkt](10_TCP_UDP_Client_Server/10_TCP_UDP_Client_Server.pkt) | [🐍 TCP server](10_TCP_UDP_Client_Server/tcp_server.py) · [client](10_TCP_UDP_Client_Server/tcp_client.py) · [UDP server](10_TCP_UDP_Client_Server/udp_server.py) · [client](10_TCP_UDP_Client_Server/udp_client.py) |
| 11 | [Socket Programming](11_Socket_Programming) | [📄 PDF](11_Socket_Programming/11_Socket_Programming.pdf) | [🖧 .pkt](11_Socket_Programming/11_Socket_Programming.pkt) | [🐍 server](11_Socket_Programming/threaded_server.py) · [client](11_Socket_Programming/client.py) |
| 12 | [Network Tools Exploration](12_Network_Tools_Exploration) | [📄 PDF](12_Network_Tools_Exploration/12_Network_Tools_Exploration.pdf) | [🖧 .pkt](12_Network_Tools_Exploration/12_Network_Tools_Exploration.pkt) | — |
| 13 | [DHCP Implementation](13_DHCP_implentation) | [📄 PDF](13_DHCP_implentation/13_DHCP_implentation.pdf) | [🖧 .pkt](13_DHCP_implentation/13_DHCP_implentation.pkt) | — |

<div align="right"><a href="#-computer-networks-lab">⬆ back to top</a></div>

---

## 📂 Repository Structure

```text
241210007_ADITYA_DADHICH_CN_LAB_EXPERIMENTS/
├── 1_Network_cabels/              # report (.pdf) + Packet Tracer file (.pkt)
├── 2_Basic_Network_Commands/
├── 3_Network_Devices/
├── 4_Networking_IP/
├── 5_LAN_Connection/
├── 6_Router_confi/
├── 7_P2P/
├── 8_NAT/
├── 9_Routing_Protocols/
├── 10_TCP_UDP_Client_Server/      # + tcp/udp client & server (.py)
├── 11_Socket_Programming/         # + threaded server & client (.py)
├── 12_Network_Tools_Exploration/
├── 13_DHCP_implentation/
└── README.md
```

Each experiment folder contains its **lab report (PDF)** and the **Cisco Packet Tracer simulation (.pkt)**. Experiments 10 and 11 also include runnable Python code.

---

## 🛠 Tools & Requirements

## 📁 Folder Overview

- [1_Network_cabels](1_Network_cabels)
- [2_Basic_Network_Commands](2_Basic_Network_Commands)
- [3_Network_Devices](3_Network_Devices)
- [4_Networking_IP](4_Networking_IP)
- [5_LAN_Connection](5_LAN_Connection)
- [6_Router_confi](6_Router_confi)
- [7_P2P](7_P2P)
- [8_NAT](8_NAT)
- [9_Routing_Protocols](9_Routing_Protocols)
- [10_TCP_UDP_Client_Server](10_TCP_UDP_Client_Server)
- [11_Socket_Programming](11_Socket_Programming)
- [12_Network_Tools_Exploration](12_Network_Tools_Exploration)
- [13_DHCP_implentation](13_DHCP_implentation)

| Tool | Used for |
|---|---|
| [Cisco Packet Tracer](https://www.netacad.com/cisco-packet-tracer) | Network simulation (`.pkt` files) |
| [Python 3](https://www.python.org/downloads/) | Socket programming (Experiments 10 & 11), standard library only, no `pip install` needed |
| Any PDF viewer | Reading the lab reports |

---

## 🖧 How to Open the Simulations

1. Install **Cisco Packet Tracer** (free with a Cisco Networking Academy account).
2. Clone the repo, or download the `.pkt` file you need:
   ```bash
   git clone https://github.com/degenerate007/241210007_ADITYA_DADHICH_CN_LAB_EXPERIMENTS.git
   ```
3. Open the `.pkt` file in Packet Tracer (`File → Open`, or double-click it).

---

## 🐍 Running the Python Programs

All programs use the loopback address `127.0.0.1`. Start the **server first**, then the client, each in its own terminal.

### Experiment 10 — TCP & UDP Client-Server

[Open folder](10_TCP_UDP_Client_Server)

| Protocol | Port | Terminal 1 (server) | Terminal 2 (client) |
|---|:-:|---|---|
| TCP (connection-oriented) | `5000` | `python3 tcp_server.py` | `python3 tcp_client.py` |
| UDP (connectionless) | `6000` | `python3 udp_server.py` | `python3 udp_client.py` |

```bash
cd 10_TCP_UDP_Client_Server
python3 tcp_server.py      # terminal 1
python3 tcp_client.py      # terminal 2
```

The client sends a greeting and the server replies with `ACK: <message>`. TCP shows the three-way handshake (`connect` / `accept`); UDP sends a datagram with no connection setup.

### Experiment 11 — Multi-client Socket Programming

[Open folder](11_Socket_Programming)

A threaded TCP server on port `7000` that handles one thread per client, welcomes each client by name, and returns their message in UPPERCASE. It serves three clients and then stops.

```bash
cd 11_Socket_Programming
python3 threaded_server.py                      # terminal 1
python3 client.py Alice "hello network"         # terminal 2
python3 client.py Bob   "second client"         # terminal 3
```

`client.py` takes optional arguments: `[name] [message]`.

<div align="right"><a href="#-computer-networks-lab">⬆ back to top</a></div>

---

## ✍️ Author

**Aditya Dadhich** · Roll No. **241210007**

<sub>Made for the Computer Networks Lab. Please use these files for reference and learning.</sub>
