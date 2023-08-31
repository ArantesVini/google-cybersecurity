# Security hardening

The process of strengthening a system to reduce its vulnerability and attack surface.

## Attack surface

All the potential vulnerabilities that a threat actor could exploit.

## Penetration test

A simulated attack that helps identify vulnerabilities in systems, networks, websites, applications, and processes.

# OS Hardening

## Operating system (OS)

The interface between computer hardware and the user

## Patch update

A software and operating system update that addresses security vulnerabilities within a program or product

## Baseline configuration (baseline image)

A documented set of specifications within a system that is used as a basis for future builds, releases, and updates.

# Network hardening

- Port filtering;
- Network access privilege;
- Encryption.

## Tasks performed

- FIrewall rules maintenance;
- Network log analysis;
- Patch updates;
- Server backups.

## Network log analysis

The process of examining network logs to identify events of interest.

## Security Information and Evenet Management tool (SIEM)

An application that collects and analyzes log data to monitor critical activities in an organization.

## Port filtering

A firewall function that blocks or allows certain port numbers to limit unwanted communication.

## Advantages and Disadvantages about Network security devices

### Firewall

**Advantages**: A firewall allows or blocks traffic based on a set of rules.

**Disadvantages**: A firewall is only able to filter packets based on information provided in the header of the packets.

### Intrusion Detection System (IDS)

**Advantages**: An IDS detects and alerts admins about possible intrusions, attacks, and other malicious traffic.

**Disadvantages**: An IDS can only scan for known attacks or obvious anomalies; new and sophisticated attacks might not be caught. It doesn’t actually stop the incoming traffic.

### Intrusion Prevention System (IPS)

**Advantages**: An IPS monitors system activity for intrusions and anomalies and takes action to stop them.

**Disadvantages**: An IPS is an inline appliance. If it fails, the connection between the private network and the internet breaks. It might detect false positives and block legitimate traffic.

### Security Information and Event Management (SIEM)

**Advantages**: A SIEM tool collects and analyzes log data from multiple network machines. It aggregates security events for monitoring in a central dashboard.

**Disadvantages**: A SIEM tool only reports on possible security issues. It does not take any actions to stop or prevent suspicious events.

# Cloud hardening

## Cloud network

A collection of servers or computers that stores resources and data in a remote data center that can be accessed via the internet.

## Baseline image

A key distinction between cloud and traditional network hardening is the use of a server baseline image, which enables security analysts to prevent unverified changes by comparing data in cloud servers to the baseline image.
