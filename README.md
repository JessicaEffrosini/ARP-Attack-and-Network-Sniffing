# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:
<img width="786" height="633" alt="Screenshot 2025-11-29 202130" src="https://github.com/user-attachments/assets/285e2cd9-4142-4dfb-8b0c-e004e2ca5286" />

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

<img width="949" height="636" alt="image" src="https://github.com/user-attachments/assets/725f9076-6e2e-439b-83ae-e9ff3510ac11" />

 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

<img width="1104" height="579" alt="image" src="https://github.com/user-attachments/assets/a898aadb-3aff-4f82-b96a-259c85996f45" />



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
<img width="1149" height="279" alt="image" src="https://github.com/user-attachments/assets/6a0347dc-f658-4439-aad7-fe3756674b78" />



Invoke the wireshark and examine the various menus  and controls of the tool:
<img width="1267" height="681" alt="512745237-279def0d-fb49-44f6-95ed-68580a80fbac" src="https://github.com/user-attachments/assets/1654538b-f304-4e92-9cf2-03dc3f78d888" />


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
