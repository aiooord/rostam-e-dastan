# Ai000 AD Hercules
![Generic badge](https://img.shields.io/badge/version-1.1.0-red.svg)
![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)
![Generic badge](https://img.shields.io/badge/Windows-Passed-blue.svg)

Ai000 AD-Hercules (Codename: Ritchie Blackmoore) is a penetration testing tool for Windows infrastructure that has been developed by Ai000 Cybernetic QLab as an offensive research project. It can be used in the red-teaming projects and penetration testing of an active directory-based environment.

<p align="center">
<img src=https://github.com/aiooord/hercules/blob/main/v1.1.0.PNG">
</p>

Ai000 AD-Hercules has no dependency on third parties and other handy tools for Windows environments (like the pass-the-hash module of mimikatz).

## Ai000 AD-Hercules Components:
Ai000 AD-Hercules consists of the following executable components:
- **adh.exe:** It is the main executable that gets credentials to spawn processes and execute commands.
- **adh-engine.exe:** It is passing the hash operation in the background to spawn the file manager, making an rdp connection and other useful things with the right privileges.
- **adh-fmc.exe:** It is a console-based file system manager.
- **pdh-fmg.exe:** It is a graphical-based file system manager.

## Development of the PST:
![](https://img.shields.io/static/v1?label=&message=pst.exe:&color=blue)
- Getting credentials
- Spawn CMD.exe
- Make RDP Connection
- Spawn console-based file manager

![](https://img.shields.io/static/v1?label=&message=pst-engine.exe:&color=blue)
- Pass-the-hash module
- FUD it from some anti-viruses

![](https://img.shields.io/static/v1?label=&message=pst-fmc.exe:&color=blue)
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
![](https://img.shields.io/static/v1?label=&message=pst-v1.1.0:&color=red)
- no bug, no pain. :D

# Contact:
- e-mail: m.kahsari@gmail.com
- website: aiooo.ir
- telegram: aioooir
