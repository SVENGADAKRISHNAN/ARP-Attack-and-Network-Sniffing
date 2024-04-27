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
![image](https://github.com/SVENGADAKRISHNAN/ARP-Attack-and-Network-Sniffing/assets/139331438/3f352eb6-2fb4-4b3d-90db-d27759f3d739)
/ARP-Attack-and-Network-Sniffing/assets/139331438/cda8e885-ddd8-4cac-bf99-af5b2e98b068)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/SVENGADAKRISHNAN/ARP-Attack-and-Network-Sniffing/assets/139331438/3f352eb6-2fb4-4b3d-90db-d27759f3d739)
/ARP-Attack-and-Network-Sniffing/assets/139331438/2a91035d-d0df-434c-a62e-3ada7233d803)


 dsniff:






In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/SVENGADAKRISHNAN/ARP-Attack-and-Network-Sniffing/assets/139331438/3f352eb6-2fb4-4b3d-90db-d27759f3d739)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/SVENGADAKRISHNAN/ARP-Attack-and-Network-Sniffing/assets/139331438/3f352eb6-2fb4-4b3d-90db-d27759f3d739)
/ARP-Attack-and-Network-Sniffing/assets/139331438/6ea0b2ac-0022-4e6f-b390-4715492e7684)



Invoke the wireshark and examine the various menus  and controls of the tool:
![ethical hacking final-212223240116-ponguru aasrith sairam-wireshark](https://github.com/AasrithSairam/ARP-Attack-and-Network-Sniffing/assets/139331438/436c9b36-5451-489c-a5a2-f50d8be0019b)



## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
