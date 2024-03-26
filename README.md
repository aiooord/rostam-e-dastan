# Responsibility
The authors are not responsible for third parties' actions while using the provided software. This software is considered a tool for legal penetration testing or research. In case of misuse, the authors don't bear any responsibility for the actions of third parties.

# Ai000 AD Rostam
![Generic badge](https://img.shields.io/badge/Version-v.0.1.0.20240306-red.svg)
![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)
![Generic badge](https://img.shields.io/badge/Windows-Passed-blue.svg)

Ai000 AD-Rostam (Codename: Ritchie Blackmoore) is a penetration testing tool for Windows infrastructure that Ai000 Cybernetic QLab has developed as an offensive research project. It can be used in red-teaming projects and penetration testing for an active directory-based environment.

<p align="center">
<img src="https://github.com/aiooord/hercules/blob/main/v.0.1.0-20240306.PNG">
</p>

Ai000 AD-Rostam has no dependency on third parties and other handy tools for Windows environments (like the pass-the-hash module of mimikatz).

## Ai000 AD-Rostam Components:
Ai000 AD-Hercules consists of the following executable components:
- **aar_cui.exe:** This process is a command line-based launcher for other components of the program.
- **aar_gui.exe:** This process is a graphical-based launcher for other components of the program.
- **aar_pth.exe:** It passes the hash operation in the background to spawn the file manager, making an RDP connection and other useful things with the right privileges.
- **aar_cfs.exe:** It is a console-based file system manager.
- **aar_gfs.exe:** It is a graphical-based file system manager.
- **aar_rpe.exe:** It is a console-based process that executes programs on remote machines and delivers their output to launcher processes.
- **aar_drp.exe:** It is an agent that drops malicious components on the target machines, and the launcher can interact with them via HTTP/HTTPS/RPC and other protocols. 

## Development of the AAR:
![](https://img.shields.io/static/v1?label=&message=aar_cui.exe:&color=blue)
- Getting credentials
- Spawn CMD.exe
- Make RDP Connection
- Spawn console-based file manager
- Spawn graphical-based file manager

![](https://img.shields.io/static/v1?label=&message=aar_gui.exe:&color=blue)
- Getting credentials
- Spawn CMD.exe
- Make RDP Connection
- Spawn console-based file manager
- Spawn graphical-based file manager
  
![](https://img.shields.io/static/v1?label=&message=aar-pth.exe:&color=blue)
- Pass-the-hash module
- FUD it from some anti-viruses

![](https://img.shields.io/static/v1?label=&message=aar-cfs.exe:&color=blue)
- Change directories
- Make files
- Make directories
- Delete files
- Delete directories
- List directories content
- Show files/directories attributes
- Change files/directories attributes
- Make an RDP connection with a remote machine
- Create a CMD.exe instance of the remote machine
- Upload and Download files from/to the remote machine

![](https://img.shields.io/static/v1?label=&message=aar-gfs.exe:&color=blue)
- Change directories
- Make files
- Make directories
- Delete files
- Delete directories
- List directories content
- Show files/directories attributes
- Change files/directories attributes
- Make an RDP connection with a remote machine
- Create a CMD.exe instance of the remote machine
- Upload and Download files from/to the remote machine
  
# Bug Tracker:
![](https://img.shields.io/static/v1?label=&message=aar-v.0.1.0.20240306:&color=red)
- no bug, no pain. :D

# Developers:
- Milad Kahsari Alhadi
- Mohammad Mahdi Anbaraki
- Amir Moahmmad Jahangirzad
- Mahdyar Bahrami
  
# Contact:
- e-mail: m.kahsari@gmail.com
- website: aiooo.ir
- telegram: aioooir
