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
![image](https://github.com/Saranyaaav/ARP-Attack-and-Network-Sniffing/assets/144870813/ead8183b-1e8e-4191-9a40-043e8364e8ca)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/Saranyaaav/ARP-Attack-and-Network-Sniffing/assets/144870813/6968a7ce-34ec-4053-b772-1544f7e0f730)


 dsniff:
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

## OUTPUT:
![image](https://github.com/Saranyaaav/ARP-Attack-and-Network-Sniffing/assets/144870813/cd186aad-7cb2-4b65-8e51-ef7d91acd5e6)


In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/Saranyaaav/ARP-Attack-and-Network-Sniffing/assets/144870813/d1c3ec67-1de5-4fd4-b29c-474cfb14897c)


Invoke the wireshark and examine the various menus  and controls of the tool:
![image](https://github.com/Saranyaaav/ARP-Attack-and-Network-Sniffing/assets/144870813/535d1484-88e5-42ca-904a-fca1c20d78af)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
