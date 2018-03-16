# Util-tools
Repo with scripts and other useful stuff that I use. I can't guarantee the tools work flawlessly.

## install_dotnet_ubuntu_17.10 

This script installs .NET Core 2.1.4 SDK and the latest release of Mono on Ubuntu 17.10. After running this script, JetBrains Rider can be installed (Rider will automatically detect Mono and .NET Core).

---
### Installing Rider

1. First, clone the repo (or download single script):

       git clone https://github.com/TheWhiteSpark/Util-tools.git
       cd Util-tools
    
2. Next add execute permission and run the script (as root):

       chmod a+x install_dotnet_ubuntu_17.10.sh
       sudo ./install_dotnet_ubuntu_17.10.sh
     
3. Download Rider IDE from official JetBrains website:
https://www.jetbrains.com/rider/

4. Unpack Rider to the preferred directory:

       mkdir -p ~/tools/IDE
       tar -xzf ~/Downloads/JetBrains.Rider-2017.3.1.tar.gz -C ~/tools/IDE

5. All done. To launch Rider, go to:

       cd ~/tools/IDE/JetBrains\ Rider-2017.3.1/bin/
    
6. Run:
    
       ./rider.sh
