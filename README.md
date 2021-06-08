# Anexnet.py

Contributors: Gaurav, Meeraj, Akshat.

This is a new initiative to extract critical information from network traffic which is obtained in the form of a .pcap file via various software such as Wireshark or Network Miner. Basically we have used some predefined python libraries such as scapy, dpkt, argparse, os, sys, and pyfiglet to show all the data transactions in the form of sessions and display the detailed information according to the flags used.  Full content packet analysis provides analysts with the ability to review exactly what has transpired on a network. Analyst neither have to rely on questionable logs nor perform guesswork when determining what data have been transferred. One of the benefits to utilizing full packet captures is the ability to extract specific files that are transferred between host and the network. These files can then be used for more in- depth analysis to determine the true nature of Malware.(collage project)
System Design
In this program we just take a .pcap file (already existing or taken
at same time) simply downloaded from Wireshark or Network Miner.
Now, open the terminal in any operating system and just type the name
of python file name and the mention which flag you want to use initially
you may type help for getting general overview of the tool.
Using this tool we can perform following tasks,
1) Accept a .pcap file.
2) Find total number of packets, including separate tcp and udp packets.
3) find the geo-location.
4) All host and Destination IPs from which files are downloaded during
the sessions.
