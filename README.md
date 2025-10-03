# Exp 4 - ARP Attack and Network Sniffing

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

<img width="1085" height="991" alt="image" src="https://github.com/user-attachments/assets/1d2d34d6-b546-4628-a1e3-21f6000050a9" />

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>

## OUTPUT:

<img width="1920" height="945" alt="image" src="https://github.com/user-attachments/assets/83995a1b-dd00-4903-9250-a5e1f2895711" />

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

## OUTPUT:

<img width="1920" height="945" alt="image" src="https://github.com/user-attachments/assets/0e52cd9f-4062-469a-b866-e48e12b05f60" />

In Kali issue the following commands:
sudo dsnifff

## OUTPUT:

Invoke the wireshark and examine the various menus  and controls of the tool:

## RESULT:

The kali linux tools for ARP Attack and Network Sniffing were identified successfully.
