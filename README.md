# Web scanning with Nikto
Nikto can be used to identify vulnerabilities on a web server
## Overview: Nickto is used to identify which vulnerabilities exist according to its known vulnerabilities database toward the underlying web server.
By selecting nikto in the Web Vunerability Scanning section of Kali - it shows a terminal window with its various options.

<img width="317" height="268" alt="nikto A" src="https://github.com/user-attachments/assets/e812dfd8-c9b3-477d-bc65-fd3cde77d75f" /><br/>
<img width="971" height="655" alt="nikto 1" src="https://github.com/user-attachments/assets/c6320e84-51c1-4ffd-8761-c1727e0b63ac" /><br/>
I'm going to run nickto against my metasploitable virtual machine using the following command. the -h flag is for host.

nikto -h 10.0.2.5
