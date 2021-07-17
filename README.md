# DHCP-Simulation

### Description

  - Simple DHCP Simulation using C# WinForm and .NET Framework 4.8

  - This is my Basic network programming class final project

### Requirement

  - .NET Framework 4.8

### Main Features

  - DHCP simulation
  - 2 modulo: Server DHCP and Client DHCP
  - 6 type of DHCP: Discover, Offer, Request, ACK, NAK, Release (not include Inform, Decline)
  - Log interface display type and time of received DHCP Packet
  - Friendly display detail of DHCP Packet
  - Real-time network config in client and IP Table in server (with release time)
  - Manual or default network config (with some advance like static IP, DNS, ...)
  - Import/Export network config
  - Login in Server (password in password.txt, saving passwork with hash and AES encryption)
  - Manual New, Extend, Release in DHCP Client
  - Can switch between auto extend or manual extend (For simulate more detail how DHCP work)
  - Save IP for rebooting case
  - Re-used same Mac-same IP if in release time
  - Can work multi-client, multi-server on LAN
  - Random allocate IP Address (valid in IP Address pool and switch to first-IP-valid allocate if random to much number of times)  
