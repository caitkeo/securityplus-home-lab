# Lab Setup

## Environment 

- Hypervisor: VirtualBox
- VMs: Kali Linux, Metasploitable2, Kioptrix
- Network: Host-only adapter (isolated from LAN + Internet)

## Steps Taken
1. Created a host-only network in VirtualBox
2. Attached Kali Linux, Metaploitable2, and Kioptrix to the network
3. Give Kali a seperate adapter (NAT) for Internet access and for updates
4. Verified isolation by pinging gateway and 8.8.8.8 from target VMs


## Result 
Isolated lab network is confirmed to be working and target VMs are shown to be connected to Kali Linux via pinging
