🔐 **Cyber Security Practicals**

This repository contains hands-on practical implementations related to Cyber Security concepts, including Steganography and Network Scanning using Nmap. These experiments help in understanding real-world security techniques and tools.

Practicals Included\
🧪 **Practical 1**: **Sending Secret Message using Steganography**

**Aim**\
To hide and send a secret message inside an image using steganography techniques.\

**Tools Used**\
1.OpenStego Software\
2.Notepad\
3.Image File (JPG/PNG)\

**Steps Overview**\
1.Create a secret message file (message.txt)\
2.Open OpenStego software\
3.Select Hide Data option\
4.Choose message file and cover image\
5.Set output file and optional password\
6.Embed the message into the image\
7.Extract the hidden message when needed\

**Output**\
Secret message successfully embedded and extracted from the image\
Confirmation messages shown in OpenStego (as seen in screenshots on pages 2–3)

🌐 **Practical 2**: **Network Scanning and Host Discovery using Nmap**

**Aim**\
To perform network scanning and identify active hosts in a network using Nmap.

**Tools Used**\
Kali Linux\
Nmap

**Steps Overview**\
1.Launch Kali Linux terminal\
2.Check Nmap version\
   nmap --version\
3.Find system IP address\
   ip a\
   hostname -I\
4.Check network configuration\
   ifconfig\
5.Perform host discovery (Ping Scan)\
   nmap -sn 192.168.1.0/24\
6.Scan a specific host\
   nmap 192.168.1.10\
7.Scan specific port range\
   nmap -p 1-1000 192.168.1.10\
8.Save scan results\
   nmap -oN output.txt 192.168.1.10

**Output**\
Active hosts identified in the network (shown in page 2 screenshot)\
Open ports and scan results displayed in terminal

**Learning Outcomes**\
Understanding of data hiding (Steganography) techniques\
Hands-on experience with OpenStego tool\
Knowledge of network scanning and reconnaissance\
Practical use of Nmap commands\
Ability to identify active hosts and open ports

⚠️ Disclaimer\
These practicals are performed for educational purposes only. Do not use these tools or techniques on unauthorized systems or networks.

**Author**
**Abhi Singh Yadav**
