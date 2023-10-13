# Gigabyte B85M-D2V with Intel Core i5-4590S Hackintosh
This repository and project hosts the files necessary to boot macOS successfully on the Gigabyte B85M-D2V motherboard.
![B85M-D2V](https://github.com/BluePurplePro/Gigabyte_B85M-D2V_with_Intel_Core_i5-4590S_hackintosh/assets/84092284/7a97b603-220b-4457-89b2-9ca4a5d73b1b)

# DISCLAIMER
THIS INFORMATION/RESEARCH HAS BEEN DONE AND SHARED PURELY FOR EXPERIMENTAL AND RESEARCH PURPOSES, AND IS IN NO MAY MEANT TO PROMOTE CIRCUMVENTING OF ANYTHING THAT IS SOMEONE ELSE'S CORPORATE PRIVATE PROPERTY. THE INFORMATION LISTED HERE IS PURELY FOR EDUCATIONAL PURPOSES AND SHOULD YOU CHOOSE TO UTILIZE IT IN ANY WAY, I AM IN NO WAY RESPONSIBLE FOR ANY INJUNCTIONS/PROBLEMS THAT MAY OR MAY NOT ARISE AND/OR BE BROUGHT AGAINST ANOTHER FOR THEIR CHOOSING TO HAVE DONE SO.

# Acknowledgements
- https://dortania.github.io/OpenCore-Install-Guide/
  
# Deployment
To deploy this project properly, please obtain the EFI folder from this repository, edit the config.plist to generate new serial number, rom, UUID, etcetera, then save config.plist, and place the files onto the appropriate ESP EFI partition in order to boot using OpenCore bootloader and proceed with your installation of macOS.

# Documentation
The hardware in this Machine is as follows:
- Audio: Realtek ALC887
- CPU: Intel Core i5-4590S
- Network: RTL8111 GbE
- GPU: Intel(R) HD Graphics 4600
