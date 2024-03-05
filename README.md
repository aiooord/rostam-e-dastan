# Responsibility
The authors are not responsible for third parties' actions while using the provided software. This software is considered a tool for legal penetration testing or research. In case of misuse, the authors don't bear any responsibility for the actions of third parties.

# Ai000 AD Hercules
![Generic badge](https://img.shields.io/badge/version-1.0.0-red.svg)
![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)
![Generic badge](https://img.shields.io/badge/Windows-Passed-blue.svg)

Ai000 AD-Hercules (Codename: Ritchie Blackmoore) is a penetration testing tool for Windows infrastructure that has been developed by Ai000 Cybernetic QLab as an offensive research project. It can be used in the red-teaming projects and penetration testing of an active directory-based environment.

<p align="center">
<img src="https://github.com/aiooord/hercules/blob/main/v1.1.0.PNG">
</p>

Ai000 AD-Hercules have no dependency on third parties and other handy tools for Windows environments (like the pass-the-hash module of mimikatz).

## Ai000 AD-Hercules Components:
Ai000 AD-Hercules consists of the following executable components:
- **aah_cui.exe:** This process is a command line-based launcher for other components of the program.
- **aah_gui.exe:** This process is a graphical-based launcher for other components of the program.
- **aah_engine.exe:** It passes the hash operation in the background to spawn the file manager, making an RDP connection and other useful things with the right privileges.
- **aah_cmd.exe:** It is a console-based file system manager.
- **adh_fmg.exe:** It is a graphical-based file system manager.

## Development of the ADH:
![](https://img.shields.io/static/v1?label=&message=adh.exe:&color=blue)
- Getting credentials
- Spawn CMD.exe
- Make RDP Connection
- Spawn console-based file manager

![](https://img.shields.io/static/v1?label=&message=adh-engine.exe:&color=blue)
- Pass-the-hash module
- FUD it from some anti-viruses

![](https://img.shields.io/static/v1?label=&message=adh-fmc.exe:&color=blue)
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
![](https://img.shields.io/static/v1?label=&message=pst-v1.0.0:&color=red)
- no bug, no pain. :D

# Contact:
- e-mail: m.kahsari@gmail.com
- website: aiooo.ir
- telegram: aioooir
