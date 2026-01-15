# 📂System-Administrative-Tasks-Linux

## This repository contains a collection of Administrative tasks of Linux based Systems.  These Projects are more focused on HOW-TOs of Daily Boring SysAdmin Tasks rather than complex and big projects. Each project includes documentation, screenshots, and working configurations. If Documentation followed, its easier to do daily boring tasks and reference it later. This project will continue to have new projects as I keep working and documenting them. 
---
## **1.Dummy Linux Storage Creation (Hardware->Kernel->Block->Partition->FileSystem->File)**
**Dummy Linux Storage Creation** [Dummy Linux Storage Creation](./Dummy-Disk-Creation-Storage)  
### This project shows how to create dummy disk storage from files, attach it to the system as block device, create partitions, assign filesystems to it, mount it and finally write to the mounted directory. Similarly, it also explains how to successfully remove the physical drive from the User level to all the way to Hardware Level. The Documentation includes all the steps clearly. 
### Concepts: dd, df, lsblk, fdisk, fsck, lsblk, mkfs, losetup, mount, umount and others.

---
## **2. FileSystem, Storage, BootLockout Project (Mount, fstab, crypttab, LUKS encryption, Simulated Boot Lockout)**
**FileSystem And Storage Lab,with Encryption and Boot lockout**[FileSystem And Storage Lab](./fileSystemLab)
### This project mounts the FileSystem both ways (temp and parmanent), adds encryption, simulates the System Lockout, troubleshoots the issue and successfully logs back in. The Documentation includes everything in detail to carryout this lab successfully.The snapshots are also included in the directory.
### Concepts: fstab, crypttab, dd, lsblk, losetup, cryptsetup, luks, mkfs, fdisk

---
## **3. FileShrink, Corrupt Filesystem Repair Project (FS RESIZING AND CORRUPT FS Repair)**
**FileSystem Resizing AND Repair Corrupt FS**[FileSystem Resizing](./File%20Shrink%20Corrupt%20FileSystem%20Repair%20Project/)
###  This project demonstrates how to resize filesystem in Linux System safely. I have used ext4 and xfs filesystem for this purpose. While doing this lab, I have encountered multiple tools, issues and troubleshooted them. Each section has all the steps in detail, and along with this documentation, I have also added CLI command documentation, that has all the necessary steps and commands required for this project.
### Concepts:  parted, partprobe, resize2fs, xfsdump, xfsrestore, e2fsck, fsck, losetup, and others.
## ⭐ Learn More on Next Steps:
1. Clone the repository:

```bash
git clone https://github.com/achaudhary002/System-Administrative-Tasks-Linux-.git
```
2. Read The Documentation:
    Each projects include the project documentation file. It explains in detail about all the steps, commands, and troubleshooting