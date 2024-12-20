# Vivado-Design-Suite-in-Ubuntu

Follow the steps below for installing vivado in ubuntu

1. Click the link https://www.xilinx.com/support/download.html
2. Select a version, newer versions are preferred
3. Download the bin file **AMD Unified Installer for FPGAs & Adaptive SoCs "Year": Linux Self Extracting Web Installer**
4. After Downloading, Go to terminal and install the following additional packages
   ```bash
   sudo apt install libtinfo5
   sudo apt install libncurses5
5. Head to the folder in Files where you have downloaded the bin file and open in terminal
6. Now, give permissions to the bin file using the following command
   ```bash
   chmod a+x <BIN file>
7. **Note: Make sure your system's time corresponds with the world time**
8. After Giving permissions, type the following command
   ```bash
   ./<BIN file>
9. A window pops up, follow these further.
10. Check your system is compatible with the vivado
11. Give your credentials in further step, mail and password
12. Select what you want to install, ex: ultrascale, etc,
13. Installation starts from here, **Note: Do not close the terminal where the installation is in progress**
14. It will take 1 to 2 hours for installing, depending on the network speed
