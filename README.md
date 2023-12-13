# Final Project 
OS Server & Sistem Admin

# Machine
- CPU		: Intel G4560
- Memory	: 16GB
- Storage	: 500GB
- OS		: Ubuntu 22.04, Windows 11 Pro

# Server Minecraft Java Edition on Ubuntu 22.04
![Yoimiyaaa❤](https://static.wikia.nocookie.net/logopedia/images/a/aa/Minecraft-java-logo.png/revision/latest/scale-to-width-down/1000?cb=20190316052713)
1. Update Repository
    ```sh
    sudo apt upgrade && sudo apt update
2. Install Htop
    ```sh
    sudo apt install htop
    ```
3. Install JDK dan Screen
   ```sh
   sudo apt install openjdk-19-jre-headless wget screen
   ```
4. Membuat Folder Minecraft Server
   ```sh
   mkdir mc_server
   ```
5. Download Minecraft latest version
    ```sh
   https://piston-data.mojang.com/v1/objects/8dd1a28015f51b1803213892b50b7b4fc76e594d/server.jar
   ```
6. Allow SSH dan Port
   ```sh
   sudo ufw allow OpenSSH
   ```
   ```sh
   sudo ufw allow 25565
   ```
    ```sh
   sudo ufw enable
   ```
