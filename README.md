# WiFi_Cracking
This repository offers educational resources and tools for exploring Wi-Fi security using the TP-Link TL-WN722N V2/V3 wireless adapter. It aims to provide a hands-on learning experience in understanding and testing WPA/WPA2 encryption vulnerabilities. The contents include setup guides, scripts for network scanning, handshake capture, and decryption methods.

## Requirements

- **WireLess Adapter**:
    - TP-Link TL-WN722N V2/V3 -
      You can Purchase The WireLess Adapter From 👇
      
      ```bash
      https://shorturl.at/Ed6sm
      
- VM Ware
- Specified Kali File

    ```bash
    https://shorturl.at/txAVD
- Customized Adapter Driver

  ```bash
  https://shorturl.at/bdTv9
  
## Lets Change The Device Driver
     ```bash
    
    sudo apt update
    sudo apt upgrade
    sudo apt install bc
    sudo apt-get install build-essential
    sudo apt-get install libelf-dev
Try Either Of These Commands
    ```bash
    
    sudo apt-get install linux-headers-`uname -r
    sudo apt-get install linux-headers-5.10.0-kali6-amd64
Continue The Other Commands
    ```bash

    sudo apt install dkms
    cd rtl8188eu
    sudo -1
    echo "blacklist r8188eu" > "/etc/modprobe.d/realtek.conf"
    exit
    sudo reboot
    sudp apt update
    cd rtl8188eu
    sudo make
    sudo make install
    sudo modprobe 8188eu
Lets Check The Adapter Enabled The Monitor Mode
    ```bash

    airmon-ng start wlan0

Use Tools Like Wifite TO Crack Wifi
    ```bash

    wifite --kill

### Thank You 
### Credits
    @AnuPras4d
    @a6h1n0v


