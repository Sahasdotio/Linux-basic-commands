# Ubuntu Installation and Basic Setup Guide

This guide walks you through installing Ubuntu Linux on your machine and setting up a basic environment for development and learning.

---

## 1. Download Ubuntu ISO

- Go to the official Ubuntu website:  
  [https://ubuntu.com/download/desktop](https://ubuntu.com/download/desktop)  
- Download the latest LTS (Long Term Support) version, e.g., Ubuntu 22.04 LTS.

---

## 2. Create Bootable USB

- Use tools like **Rufus** (Windows), **Etcher** (Windows/Linux/macOS), or `dd` command (Linux) to create a bootable USB drive with the downloaded ISO.
  
**Example with Rufus:**  
- Insert USB drive (minimum 4GB)  
- Open Rufus  
- Select the Ubuntu ISO file  
- Click **Start** and wait for the process to complete

---

## 3. Boot from USB and Install Ubuntu

- Restart your PC and enter the BIOS/UEFI settings (usually by pressing F2, F12, DEL, or ESC during boot).  
- Change the boot order to boot from USB first.  
- Save and exit BIOS. The system will boot from the USB.  

**Install Steps:**  
- Select **Try Ubuntu** to test it without installing (optional).  
- Or click **Install Ubuntu**.  
- Follow the installation wizard:  
  - Choose your language  
  - Select keyboard layout  
  - Connect to Wi-Fi  
  - Choose installation type (normal/recommended or minimal)  
  - Select disk partition (erase disk or install alongside other OS)  
  - Set your username and password  
  - Wait for installation to finish  
- Reboot when prompted and remove USB.

---

## 4. Initial Setup After Installation

- Log in with your username and password.  
- Open Terminal (`Ctrl + Alt + T`).

---

## 5. Update & Upgrade System

Run these commands to update package lists and upgrade installed packages:

```bash
sudo apt update
sudo apt upgrade -y
