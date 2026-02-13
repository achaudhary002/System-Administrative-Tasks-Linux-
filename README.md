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

---
## **4. Network File Share Creation And Mount**
**4. Network File Share Creation And Mount**[NFSCreation Lab](./NFSCreationAndMount/)
### NFS or Network File Share is essential feature in linux where files or directories can be easily shared across multiple machines or network. In this lab, I have showed the base level way of creating a fileshare, and share it across the network.
### Concepts: SysAdmin TAsks ( Network File Sharing Techniques and Tools like nfs-kernel-server, nfs-common, /etc/export file)

---
## **5. CIFS/SMB Share Creation And Mount (Samba and CIFS) **
**5. CIFS/SMB Share Creation And Mount**[CIFS/SAMBA SHARE LAB](./CIFS_SMB_SHARE%20mount/)
### Samba File share  Using SMB protocol is essential feature in linux where files or directories can be easily shared across multiple machines or network, in addition to the compatibility with crossplatform. In this lab, I created fileshare and mounted to the client using CIFS-UTILS.
### Concepts: SysAdmin TAsks ( Use of Samba File Sharing Techniques and Tools like samba, sambacredentials, sambauser, cifs-utils)

---
## **6. Cleanup Orphaned Users and Files Residue **
**6.  Cleanup Orphaned Users and Files Residue**[Orphan Users Lab](./Cleanup%20Orphaned%20Users%20and%20Files/)
### This Project is my created guide to work with orphaned users. The documentation simplifies the whole concepts and process into simple steps. The online community and resources often confuse new comers and beginners with their heavy technical jargons and buzz words leaving beginners clueless about the issue, when it can be put simple and easy for everyone to understand. In this lab, I have worked with my own system to find these orphaned users and files. I have been working on it for sometime now. Its easy to understand, once the document is understood, it will be far easy than before to look for what you need. Trust Me. 

---
## **7. Share Files from User's Private Home Directory Lab **
**7.  Share Files from User's Private Home Directory to Anyone**[PrivateHomeShareLab](./Access_SharedFile_From_Someone's_Private_HomeDir/)
### In this lab, I have demonstrated a share of directory or files from a user's private home directory to anyone in the particular group using 'acl' tool. I have also considered the permission rules accordingly to minimize the security risk to the sharing user's private directory. This is done from scratch. And this lab assumes the users and groups are already created before attempting this lab. If you have not, my CLI Documentation also shows quick command to do that as well. This is a part of my SysAdmin task list. I have tried keeping simple and easy, most importantly, as out of much technical jargons and acronyms as possible. I understand, this might be challenging for beginners. I have had this experience alot in the beginning, I still have it sometime. Thank you for reading out. 

---
## ⭐ Learn More on Next Steps:
1. Clone the repository:

```bash
git clone https://github.com/achaudhary002/System-Administrative-Tasks-Linux-.git
```
2. Read The Documentation:
    Each projects include the project documentation file. It explains in detail about all the steps, commands, and troubleshooting