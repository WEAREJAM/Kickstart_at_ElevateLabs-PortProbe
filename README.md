# Kickstart_at_ElevateLabs-PortProbe
My kickstart journey at Elevate Labs as an intern. This is my first task — many more to go and much more to learn!

## Overview
This project explores TCP Port Scanning using Nmap, capturing and analyzing packets with Wireshark, and documenting SYN/SYN-ACK behavior to understand how port probing functions at the network level.

## Objective
To perform a TCP SYN scan (nmap -sS)

To analyze packet flow using Wireshark

To observe TCP handshake flags involved in scanning

To document findings with annotated screenshots

## Tools Used
Tool	Purpose
Nmap          	To perform SYN-based port scanning

Wireshark	      To capture and analyze TCP/IP packet traffic

## Key Command Used  
nmap -sS 192.168.xxx.xxx       ___SYNC SCAN___

nmap -sS -sV 192.168.xxx.xxx   ___SYCN AND VERSION SCAN___

nmap -A -T4 192.168.xxx.xxx   ____AGRESSIVE SCAN___

## Screenshots
![Wireshark SYN Scan](https://github.com/WEAREJAM/Kickstart_at_ElevateLabs-PortProbe/blob/main/asserts/sample2.png?raw=true)
![Wireshark Output](https://github.com/WEAREJAM/Kickstart_at_ElevateLabs-PortProbe/blob/main/asserts/sample3.png?raw=true)

## Files in this Repo
findings.md – Contains detailed scan findings with explanations

asserts/ – Screenshot folder for packet captures

README.md – Project summary and overview

## Learnings
Behavior of TCP SYN scan (stealth scan) in Nmap

Identification of open, closed, and filtered ports via packet flags

Hands-on analysis of SYN, SYN-ACK, and RST packet responses

Observing connection patterns and interpreting Wireshark data

## Privacy Notice
All IP addresses, hostnames, and environment-specific details in this repository have been masked or edited to protect privacy and comply with ethical standards.
The scans were performed in a controlled and legal lab setup.

✅ Legal & Ethical Use
This project follows strict ethical hacking practices. All scans and tests were conducted on authorized systems in isolated environments for educational purposes only.
