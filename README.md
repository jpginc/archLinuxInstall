# Arch Linux Virtual box Install script
Quick basic install script for arch linux. Run the following commands from the live CD

    pacman -Syy git
    git clone https://github.com/jpginc/archLinuxInstall.git
    cd archLinuxInstall
    chmod +x * 
    ./first

During the first script the screen may go black due to inactivity. Try pressing one of the arrow keys and if your at a prompt type the following commands to continue the installation

    cd /home/archLinuxInstall
    ./second
    
follow the prompts which will instruct you to restart the virtual machine. Unless you have already removed the live CD (Devices -> CD/DVD Devices -> Remove disk from virtual drive) you will be shown a menu asking you to chose how to boot up. "Select Boot existing OS"



