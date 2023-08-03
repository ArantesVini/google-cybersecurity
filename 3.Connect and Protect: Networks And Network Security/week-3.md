# Introduction to network intrusion tatics

## Common network intrusion attacks:

- Malware;
- Spoofing;
- Packet sniffing.

## Attacks can harm an organization by

- Leaking valuable or confidential information;
- Damaging an organization's reputation;
- Impacting customer retention;
- Costing money and time.

## Backdoor attacks

A type of attackthat work arround the security measures. Backdoors are weakness intetionally left by programmers or system and network admin istratos that **bypass** normal access control.

# Secure networks againt Denial of Service (DoS) attacks

## Denial of service attack (DoS)

An attack that targets a network or server and floods it with network traffic

## Distributed denial of service attack (DDoS)

A type of denial of service attack that uses multiple devices or servers in different locations to flood the target network with unwanted traffic.

## SYN( synchronize) flood attack

A type of Dos attack that simulates a TCP connection and floods a server with SYN packets.

## Internet Control Message Protocol (ICMP)

An internet protocol used by devices to tell each other about data transmission erros across the network.

## ICMP Flood

A type of DoS attack performed by an attacker repeatdly sending ICMP packets to a network server.

## Ping od death

A type of DoS attack caused when a haker pings a system by sending it an oversized ICMP packet that is bigger than 64KB

## tcpdump

A CLI network protocol analyzer. it is open source and can run using little memory and CPU usage.
To interpet a ouput of tcpdump you must go for the next:
![tcpdump_output](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/B-PaECh0ToSFgBWpFczYZg_4896abe8c06443f08eec4dc003dcf8f1_image.png?expiry=1691193600000&hmac=8XsCvqbF8pBRQDdyC-IP0aV_My31XW5LKMV6UBckXY4)

# Network attack tatics and defense

## Passive packet sniffing

A type of attack where data packets are read in transit.

## Active packet sniffing

A type of attack where data packets are manipulated in transit.

## Observation about defense

If you use a VPN your data can also be manipulated but cannot be read, because is encoded.

## IP Spoofing

A network attack performed when an ttacker changes the source IP of a data packet to impersonate an authorized system and gain acces to a network.

## Common IP spoofing attacks

### On-path attack

An attack where a malicious actor places themselver in the middle of an authorized connection and intercepts or alters the data in transit.

## Replay attack

A network attack performed when a malicious actor intercepts a data packet in transit and delays it or repeats it at another time.

## Smurf attack.

A network attack performed when an attacker sniffs an authorized user's IP address and flood it with packets.
