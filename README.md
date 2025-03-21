# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

To explore network sniffing and ARP Attacks

## STEPS:

- `Step 1:` Install kali linux either in partition or virtual box or in live mode
- `Step 2:` Investigate on the various categories of tools as follows.
-  `Step 3:` Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.

In windows 7 give the command arp -a
## OUTPUT:
![image](https://github.com/user-attachments/assets/1932d378-9f48-4a12-b4a2-e2225f2d5c2b)



From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/user-attachments/assets/0d5495de-206a-4218-8bd8-d320b9c06d5a)



 dsniff:In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/user-attachments/assets/ec879b8a-05e7-4caa-8799-45a816e0cf4c)



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/user-attachments/assets/3f565d9f-68ab-42f1-a5c8-42fe04acefdd)


Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/user-attachments/assets/318671f8-6917-416c-858b-a8b7c6fff3c7)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
