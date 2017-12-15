### An Easy rclone Install onto a Raspberry Pi Computer with Folder sync demo
## [For Detailed Instructions See Wiki](https://github.com/pageauc/rclone4pi/wiki)

## Quick Install
**Step 1** Highlight curl command in code box below using mouse left button. Right click mouse in highlighted area and Copy.    
**Step 2** On RPI putty or terminal session right click, select paste then Enter to download and run script.  

    curl -L https://raw.github.com/pageauc/rclone4pi/master/rclone-install.sh | bash

This will install rclone-install.sh, rclone-sync.sh and create a subfolder rpi-sync in users home eg. /home/pi    
    
## Manual Install
Using logged in putty SSH or RPI Terminal session execute commands below

    cd ~
    mkdir -p rpi-sync
    wget -O rclone-install.sh https://raw.github.com/pageauc/rclone4pi/master/rclone-install.sh
    wget -O rclone-sync.sh https://raw.github.com/pageauc/rclone4pi/master/rclone-sync.sh
    wget -O rpi-sync/Readme.md https://raw.github.com/pageauc/rclone4pi/master/Readme.md
    chmod +x rclone-install.sh
    chmod +x rclone-sync.sh
    ./rclone-install.sh     # Run Install Script.  You may review script first.

## See [How to Configure a Remote Storage Service](https://github.com/pageauc/rclone4pi/wiki#how-to-configure-a-remote-storage-service)

## Description
Rclone is a command line program to sync files and directories to and from many remote storage services.
This utility can be used to sync raspberry pi computer folders/files to one or more remote services. For more information about rclone See
 https://rclone.org/ and/or https://github.com/ncw/rclone

 
My Raspberry Pi YouTube Stuff https://www.youtube.com/user/pageaucp/search?query=raspberry+pi  
My YouTube Channel https://www.youtube.com/user/pageaucp   
Claude Pageau




