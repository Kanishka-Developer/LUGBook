# Bootable USB guide (using BalenaEtcher)

## Introduction

To install an Linux Distro onto our PC, we will need to first create a bootable USB drive.
We will be using BalenaEtcher for doing this.

## BalenaEtcher

- BalenaEtcher is a cross-platform tool for flashing OS images onto SD cards and USB drives.
- It runs on any platform supported by Electron like Windows,MacOS and Linux.

## Installation

- BalenaEtcher can be downloaded from their [website](https://www.balena.io/etcher).

- It is also avaiable in the AUR(Arch User Repository) and winget(Windows Package Manager).

- ## For Arch :
  
  ```
  yay -S balena-etcher
  ```

- ## For Windows :
  
  ```
  winget install BalenaEtcher
  ```

## Creating a Bootable USB :

- Open BalenaEtcher :
  
  ![Image](/Images/Step1.png)

- Choose an ISO image : 
  
  ![Image](/Images/Step2.png)

- Then choose an USB drive : 
  
  ![Image](/Images/Step3.png)

- After confirming that the details are correct, click on 'Flash!' :
  
  ![Image](/Images/Step4.png)

- Wait for the BalenaEtcher to finish flashing the USB drive :
  
  ![Image](/Images/Step5.png)

- And congrats! The USB drive is now a bootable drive with the ISO of the distro you want
  
  ![Image](/Images/Step6.png)

---

### [Return to Index](../)
