week1 Notes-- Linux & Networking
start date-- 2024 9/11
Goal learning Linux basics + networking fundamental

levels         commands                password
level 0-1    ls ,cat                          6y2kwnwK6grgvwvpvLaa2T1cpFEKOhNR
level 1-2    ls,cat ./                        PK8fYLZg2hnHSz83plBL1iEPKdD3QToB
level2-3     ls,cat ./spaces\         7ZZ2LFrykP2zEyvBl4m3clcL7tGYJPME
level 3-4    ls -a, cat                      xzTXq1rDJQVVAzdv5cHq1TQytTWufAMq
level 4-5    ls,cat, file ./*              6C7h9GD8M6ai5nr7wo1RonrzFjj9yIrG

# OSI Model & TCP/IP

## OSI 7 Layers (Top to Bottom)
7. Application - HTTP, DNS, FTP
6. Presentation - SSL/TLS, encryption
5. Session - cookies, sessions
4. Transport - TCP, UDP, ports
3. Network - IP addresses, routing
2. Data Link - MAC addresses, switches
1. Physical - cables, signals

## TCP/IP 4 Layers
4. Application (OSI 7+6+5)
3. Transport (OSI 4)
2. Internet (OSI 3)
1. Network Access (OSI 2+1)

This is the Transport Layer — Layer 4. You MUST understand this.

Feature	                 TCP	                                           UDP
Full name	               Transmission Control Protocol	                 User Datagram Protocol
Connection	             Connection-oriented (3-way handshake)	         Connectionless (fire and forget)
Reliability	             Reliable — confirms delivery	                   Unreliable — no confirmation
Speed	                   Slower	                                         Faster
Order	                   Data arrives in order	                         No guarantee of order
Use cases	               Web browsing, email, file transfer	             Video streaming, gaming, DNS


## TCP 3-Way Handshake
1. Client → SYN → Server
2. Server → SYN-ACK → Client
3. Client → ACK → Server

## Common Ports
22=SSH, 53=DNS, 80=HTTP, 443=HTTPS




