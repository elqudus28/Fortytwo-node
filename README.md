## Fortytwo-node
* Guide to install Fortytwo node 
## Fortytwo node requirements
CPU: Modern multi-core processor (e.g., Intel Core i7 or AMD Ryzen 7)
RAM: At least 16 GB of system memory (32 GB or more recommended)
GPU: Nvidia RTX series GPU or Apple Silicon with the highest available VRAM or Unified Memory for enhanced performance.
Storage: SSD with at least 20 GB of free disk space for storing model data
Network: Stable internet connection (minimum 10 Mbps download and upload speed)

* Before proceeding, ensure the following dependencies are installed: curl and libgomp

```console
 sudo apt update && sudo apt install -y curl libgomp1
```
You will need access code to run the node, check your mail if you filled the form, or import your wallet pass phrase if you have run it before 

* make and change directory to fortytwo node
```console
mkdir -p ~/Fortytwo && cd ~/Fortytwo
```

* Execute the commands below to download the Node package, extract its contents, and run the installation script
```console
#run the node on screen 

screen -S Fortytwo
curl -L -o fortytwo-console-app.zip https://github.com/Fortytwo-Network/fortytwo-console-app/archive/refs/heads/main.zip
unzip fortytwo-console-app.zip
cd fortytwo-console-app-main
chmod +x linux.sh && ./linux.sh
```

* Copy your passphrase and store it somewhere safe
* Follow the on-screen instructions to complete the setup

  Join Forty node DISCORD: https://discord.gg/8cx8YjmKdr
