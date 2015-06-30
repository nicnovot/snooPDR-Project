# snooPDR-Project
Capture RSA-SSL-Encrypted RDP traffic and replay that traffic to the server.

This Linux distro will focus on decrypting RSA-SSL-Encrypted RDP traffic through exploiting the
relative computational weakness of the RSA encryption method.  The aim of this project is to decrypt SSL encrypted RDP
traffic and extract administrator credentials, then replay the authentication packets.  This tool will use tshark, wireshark,
mimikatz, MySQL, and scapy.
