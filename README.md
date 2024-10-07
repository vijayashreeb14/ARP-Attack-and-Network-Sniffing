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

![image](https://github.com/user-attachments/assets/3994c4d1-d76b-4c59-9d40-fc8449d97cab)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![image](https://github.com/user-attachments/assets/7a251082-f246-4166-a5cc-cdd8cc7d19d4)



 dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

![image](https://github.com/user-attachments/assets/1b6f2462-190a-46a0-af22-05e6643c6075)





In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

![image](https://github.com/user-attachments/assets/708d811a-5e84-4e9f-beb0-7a2da889e8e0)


Invoke the wireshark and examine the various menus  and controls of the tool:

![image](https://github.com/user-attachments/assets/fdae0a0a-5cf0-4f50-810c-3ac75c846b03)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
