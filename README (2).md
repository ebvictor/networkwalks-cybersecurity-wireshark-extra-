# Network Traffic Analysis Using Wireshark | Networkwalks Internship

## Project Overview

As part of my Networkwalks cybersecurity internship, I carried out an additional practical exercise using Wireshark to analyse captured network traffic.

The exercise focused on understanding how network packets can reveal suspicious activities, exposed information and possible attack attempts.

Through this practical session, I explored different features of Wireshark and learnt how to examine network communication more closely.

## Objectives

The main objectives of this exercise were to:

- Identify suspicious traffic and trace the suspected attacker.
- Follow TCP streams to understand communication between devices.
- Discover hidden information within captured network traffic.
- Identify passwords transmitted in clear text.
- Examine network traffic associated with brute-force attacks.
- Analyse captured VoIP (Voice over Internet Protocol) calls.

## Tools Used

- **Wireshark:** For capturing and analysing network packets.
- **PCAP/PCAPNG files:** For examining previously captured network traffic.

## Practical Activities

### 1. Identifying the Attacker

I examined captured network packets to identify suspicious communication and determine the source IP address associated with the suspected attack.

This helped me understand how packet information, source addresses and destination addresses can assist in investigating suspicious network activities.

### 2. Following TCP Streams

I used the Follow TCP Stream feature to reconstruct and examine conversations between communicating devices.

This made it easier to understand how data was exchanged and view the contents of network communication where the traffic was not encrypted.

### 3. Discovering Hidden Data

I inspected captured packets and TCP streams to locate information that was not immediately obvious when viewing individual packets.

This demonstrated how detailed packet inspection can reveal information that might otherwise go unnoticed.

### 4. Identifying Cleartext Passwords

I examined network traffic for passwords transmitted without encryption.

This practical exercise showed me why transmitting login credentials over unencrypted connections can expose sensitive information to anyone with access to the captured traffic.

### 5. Analysing Brute-Force Attacks

I examined captured traffic showing evidence of brute-force attempts.

I learnt how repeated login requests and communication patterns can help indicate attempts to guess user credentials.

### 6. Analysing VoIP Calls

I also explored captured Voice over Internet Protocol (VoIP) traffic to understand how voice communication packets can be identified and examined in Wireshark.

This introduced me to another area of network traffic analysis beyond ordinary web communication.

## Screenshots and Evidence

The following screenshots provide evidence of selected activities carried out during the practical exercise.

Networkwalks Wireshark Internship work.png

Following Tcp Streams
Networkwalks wireshark intership 3.0.png

Score on one of the labs

![Score on one of the labs](images/Networkwalks%20internship%20wireshark%204.0.png)

## Key Lessons Learned

This practical exercise helped me understand that network traffic contains useful information that can support security investigations.

I learnt that:

- Source and destination IP addresses can help trace suspicious communication.
- Following TCP streams makes it easier to understand conversations between devices.
- Unencrypted communication can expose sensitive information, including login credentials.
- Repeated authentication attempts can provide evidence of brute-force activity.
- Wireshark can also be used to investigate VoIP communication.

Most importantly, I learnt that analysing network traffic is not just about looking at packets but understanding what those packets reveal about activities taking place across a network.

## Safety Notice

All activities documented in this project were carried out in a controlled lab environment using captured traffic for educational purposes only.

No unauthorised networks, devices or systems were targeted.

## Conclusion

This additional Wireshark exercise gave me more practical exposure to network traffic analysis and helped me understand how security analysts investigate suspicious network activities.

I look forward to learning more and improving my practical cybersecurity skills.

**Programme:** Networkwalks Cybersecurity Internship  
**Area:** Network Traffic Analysis  
**Tool:** Wireshark

Author: Victor Ebubechukwu

Linkedin: https://lnkd.in/p/eri9deGZ
