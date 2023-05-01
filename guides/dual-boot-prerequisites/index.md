# Prerequisites to Dual-Boot
---

## 1.  Check the Encryption Status of Storage.
	
To verify the encryption status of storage, follow the steps below:

a. Go to the Settings menu and search for encryption.

b. Turn off encryption and decrypt the data. Note that this process could take up to 2-3 hours.
    
## 2.  Check the Secure Boot Status.

To verify the secure boot status, follow the steps below:

a. Click on the Start menu.

b. In the search bar, type "msinfo32" and press Enter.

c. System Information opens. Select System Summary.

d. On the right side of the screen, look at the BIOS Mode and Secure Boot State. If the BIOS Mode shows UEFI and Secure Boot State shows Off, then Secure Boot is disabled.
    
## 3.  Take a Backup of All Important Data.

Before proceeding with the installation of Linux, it is important to take a backup of all important data to prevent any loss or corruption.
    
## 4.  Create an NTFS Partition for Linux Installation.

To create an NTFS partition for Linux installation, follow the steps below:

a. Using Disk Management, create the NTFS partition with the desired size and name.

b. For first-time users, it is suggested to note all partitions on a paper.

## 5.  Disable Secure Boot in the BIOS/UEFI Menu.

To disable Secure Boot in the BIOS/UEFI menu, follow the steps below:

a. At the Windows desktop, open the Start menu and click on the Settings icon (cog icon).

b. Select Update & Security.

c. Select Recovery from the left-side menu.

d. Under Advanced Startup, click the Restart Now button on the right side of the screen.

e. The computer restarts and boots to an Options Menu.

f. Choose the UEFI settings option.

g. Carefully navigate the UEFI/BIOS menu and turn off Secure Boot.

h. After this, go to the boot order setting (if available) and make USB boot the first priority.

i. Press F10 to save and exit settings.
    
## 6.  Install Linux on Your Machine.

Now that Secure Boot has been disabled, you are ready to install Linux on your machine. To do so, follow the steps below:

a. Boot into Linux using a bootable USB.

b. While installing Linux, carefully select the partition created in Step 4 for installation.

## 7.  Additional Resources
    
If you have any doubts or require further guidance, you can refer to the [Archwiki]([https://wiki.archlinux.org/](https://wiki.archlinux.org/)) or the forum of your respective distribution for assistance. 
These resources can be useful not only for Arch but for nearly all distributions.
    
---
### [Return to Index](../)