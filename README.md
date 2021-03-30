 # <img align="left" width="150" height="150" src="https://raw.githubusercontent.com/PlagueSec/PlagueSecOS/master/pictures/logo.png"> PlagueSecurity Operating System 
A Customed Operating System for Security Researchers and Penetration Testers. Based on [Kali Linux](https://www.kali.org/)

&nbsp;

### Available Desktop Environments
- MATE
- KDE
- GNOME
- XFCE
- BUG BOUNTY

### Instruction for building an ISO
1. Update the System
````
sudo apt update
````
2. Install Requirements to Build the Operating System
````
sudo apt install -y git live-build cdebootstrap devscripts
````
3. Clone the Repository
````
git clone https://github.com/PlagueSec/PlagueSecOS.git
````
4. Go into the Cloned Repository
````
cd PlagueSecOS/
````
5. Change Permission to be Executable
````
chmod +x ./build.sh
````
6. Build The Operating System
````
sudo ./build.sh --variant (mate,kde,gnome,xfce,bugbounty) -v
````

#### Burning ISO to USB
We Recommend you use [Balena Etcher](https://www.balena.io/etcher/)

----
#### Official Platforms
[Plague Security Official Website](https://plaguesec.com)

[Plague Security Official Facebook](https://www.facebook.com/PlagueSec-104041125002327)
