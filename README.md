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

<img width="846" height="672" alt="Screenshot 2026-11-26 000755" src="https://github.com/user-attachments/assets/8d5e89f5-adf9-41e6-8919-965f4247d48f" />


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:


 dsniff:

<img width="921" height="736" alt="Screenshot 2026-11-26 005548" src="https://github.com/user-attachments/assets/68ee00c9-928e-4d05-91ce-465baa44b576" />





In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:



<img width="837" height="695" alt="Screenshot 2026-11-26 005056" src="https://github.com/user-attachments/assets/7d659a76-5cb4-4712-891e-fc84c8658fff" />


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

<img width="877" height="707" alt="Screenshot 2026-11-26 001516" src="https://github.com/user-attachments/assets/8a49b6bb-a028-40d0-a3fa-b538201c25ad" />



Invoke the wireshark and examine the various menus  and controls of the tool:

<img width="925" height="691" alt="Screenshot 2026-11-26 010816" src="https://github.com/user-attachments/assets/2673fa2d-3971-45a9-bbf2-8935c1ce627c" />


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
