# Kali Foundation

## Current Setup
Set up Kali Linux in VirtualBox with two network adapters:

eth0 = NAT, 10.0.2.15/24, used for internet

eth1 = LAB-NET, 192.168.50.10/24, used for the homelab network

Used ip -br addr and ip route to check the interfaces, IP addresses, and routes.

Set a static IP on eth1 with NetworkManager and confirmed it stayed after reboot.

Also set up Git and SSH for GitHub using an Ed25519 key and tested the connection successfully.

So far I learned more about NAT, internal networks, static IPs, routing, SSH keys, and basic Linux networking.


