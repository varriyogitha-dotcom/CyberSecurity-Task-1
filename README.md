# CyberSecurity-Task-1

## Objective
Set up a cybersecurity lab environment using Kali Linux and Metasploitable.

## Tools Used
- Kali Linux
- Metasploitable
- Wireshark
- Burp Suite
- Netcat

## Activities
- Installed Kali Linux in VirtualBox.
- Installed Metasploitable.
- Configured Host-Only Networking.
- Verified connectivity using ping.
- Explored Wireshark packet capture.
- Tested Netcat communication.
- Learned Burp Suite basics.
## Lab video demonstration:-https://drive.google.com/file/d/1MspGTxc8emfm_YSxsl71P9k3LQRwIM0m/view?usp=drivesdk

<img width="1356" height="720" alt="Videoshot_20260605_151742" src="https://github.com/user-attachments/assets/1ba6172f-45d0-4f20-9b36-75b37520f973" />
<img width="1356" height="720" alt="Videoshot_20260605_151800" src="https://github.com/user-attachments/assets/3dbe56a9-11a7-4cc0-9ee1-79ee6696e5eb" />
<img width="1356" height="720" alt="Videoshot_20260605_151811" src="https://github.com/user-attachments/assets/87302686-1e54-4bb0-8b2a-74c975acfe43" />
<img width="1356" height="720" alt="Videoshot_20260605_151814" src="https://github.com/user-attachments/assets/c14fac70-6aca-40f7-84bc-0059ce5af26e" />
<img width="1356" height="720" alt="Videoshot_20260605_151819" src="https://github.com/user-attachments/assets/7092a8d2-6788-44f9-b75c-adc5d2ee2ce7" />
<img width="1356" height="720" alt="Videoshot_20260605_151847" src="https://github.com/user-attachments/assets/ceb23175-db9c-43a5-a5bf-ce39d1a03445" />



## Outcome:-Successfully created a cybersecurity lab environment and learned basic cybersecurity tools.
## 📝 Linux & Tool Cheat Sheet
Here are the essential terminal commands used during this lab setup and verification.

### 1. Networking & Connectivity
* `ip a` or `ifconfig` – Check the network interfaces and retrieve the IP address of the machine.
* `ping <IP_Address>` – Test the network connectivity between Kali and Metasploitable (e.g., `ping 192.168.56.102`).
* `ping -c 4 <IP_Address>` – Send exactly 4 packets and stop automatically.

### 2. Netcat (nc) Basics
Used to test raw network connections, banner grabbing, and basic data transfer.
* `nc -lvp <port>` – **On Kali (Listener):** Sets up Netcat to listen (`-l`) verbosely (`-v`) on a specific port (`-p`) like 4444.
* `nc <Kali_IP> <port>` – **On Metasploitable (Client):** Connects to the listening Kali machine.

### 3. System & Directory Navigation
* `pwd` – Print Working Directory (shows exactly where you are in the system).
* `ls -la` – List all files and directories in long format, including hidden ones.
* `sudo su` – Switch to the root (administrator) user for full control.
