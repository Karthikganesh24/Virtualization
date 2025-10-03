## Ex.3 Virtualization: Installation and Configuration of Oracle VirtualBox & Kali Linux, and Execution of Linux Commands
## NAME: Karthik ganesh G
## REG NUMBER: 212223223003
## Aim:
To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.

## 3.a) Installation and Configuration of Oracle VirtualBox
## Aim:
To install and configure Oracle VM VirtualBox.

## Pre-requisites:
- Machine with Internet access
- Minimum 4 GB RAM
- Sufficient storage space
## Steps:
1.Download Oracle VM VirtualBox:

- Visit Oracle VirtualBox Official Site
- Download installer for your OS (Windows/macOS/Linux).

2.Install Oracle VM VirtualBox (Example: Windows):

- Launch Installer → Allow Changes → Click Next.
- Choose Installation Options → Click Next.
- Accept Network Interface Warning → Click Yes.
- Click Install.
- Finish Installation and Launch VirtualBox.

3.Configure VirtualBox:

- Open VirtualBox.
- Click New → Name VM → Select Type (Linux/Windows) and Version.
- Allocate:
  
     Minimum 2 GB RAM
  
     Create Virtual Hard Disk (20 GB recommended).
  
- Start Virtual Machine and provide ISO to install OS.
## Result:
Thus, Oracle VM VirtualBox was installed successfully.

## 3.b) Installation and Configuration of Kali Linux
## Aim:
To install and configure Kali Linux in Oracle VirtualBox.

## Pre-requisites:
- Oracle VM VirtualBox Installed
- 4 GB RAM and 20 GB Storage Minimum
- Kali Linux ISO image
## Steps:

1.Download Kali Linux ISO:
- Visit Kali Linux Official Site
- Download 64-bit ISO (Installer version).
  
2.Create a New Virtual Machine:
- Open VirtualBox → Click New.
- Name: "Kali Linux" → Type: Linux → Version: Debian (64-bit).

3. Allocate Memory:
- Minimum 2 GB RAM (recommended 4 GB).
  
4.Create Virtual Hard Disk:
- Select VDI (VirtualBox Disk Image).
- Choose Dynamically allocated.
- Set Disk size to 20 GB or more.
  
5.Configure ISO Image:
- Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali Linux ISO.
  
6.Start Installation:
- Boot Virtual Machine → Choose Graphical Install.
- Set Language, Region, Keyboard.
- Configure Network → Set Hostname (e.g., kali).
- Set root password.
- Disk Partitioning: Use entire disk → All files in one partition.
- Install System → Install GRUB Bootloader → Finish Installation.
  
7.Login to Kali Linux:
- Use root credentials.
  
8.(Optional) Install Guest Additions:
- Devices → Insert Guest Additions CD Image → Follow steps inside Kali.
  
## Snapshots:

AWS Account Creation Snapshot
## Snapshot 1: Installing Oracle VirtualBox image
<img width="927" height="497" alt="Screenshot 2025-08-28 103507" src="https://github.com/user-attachments/assets/80010f1b-318d-437f-962c-a741cfda0d3d" />


## Snapshot 2: Kali Running in Virtual image
<img width="935" height="573" alt="Screenshot 2025-08-28 103519" src="https://github.com/user-attachments/assets/4894b551-1dc5-4ffd-8354-eadb514f50ba" />


## Result:
Thus, Kali Linux guest OS was installed and configured successfully.

## 3.c) Execution of Linux Commands in Kali
## About Linux:
- Open-source operating system.
- Kernel manages communication between hardware and software.
- Commands are case-sensitive.
## Commands:
## 1) ls Command
The ls command is used to display a list of content of a directory.

Syntax: ls

<img width="611" height="130" alt="image" src="https://github.com/user-attachments/assets/805765d1-65db-4035-94fa-a5ef1407bbbe" />


## 2) pwd Command
The pwd command is used to display the location of the current working directory.

Syntax: pwd
<img width="683" height="78" alt="image" src="https://github.com/user-attachments/assets/634997ff-f6cd-4cf8-bd0f-7b40be784170" />


## 3) mkdir Command
The mkdir command is used to create a new directory under any directory.

Syntax: mkdir

<img width="526" height="72" alt="image" src="https://github.com/user-attachments/assets/8bc6e437-8f97-4425-84ee-61f7b13e104d" />


## 4) rmdir Command
The rmdir command is used to delete a directory.

Syntax: rmdir

<img width="655" height="171" alt="image" src="https://github.com/user-attachments/assets/54cccfd4-6312-47a2-84ec-6a342b6bcf36" />



## 5) cd Command
The cd command is used to change the current directory.

Syntax: cd

<img width="710" height="107" alt="image" src="https://github.com/user-attachments/assets/6c98d385-899e-42e1-8a41-7d15d89926d7" />


## 6) cat Command
The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content of the file, copy the content of one file to another file, and more.

Syntax: cat [OPTION]... [FILE]..

<img width="584" height="178" alt="image" src="https://github.com/user-attachments/assets/3c5ddedd-205b-4dfb-ae36-1c6ffc501673" />


## 7) cp Command
The cp command is used to copy a file or directory.

Syntax: cp

<img width="485" height="121" alt="image" src="https://github.com/user-attachments/assets/6074f8cb-13d0-4c75-ae7e-ed4ed9843d58" />


## 8) gedit Command
The gedit is a general-purpose text editor. It can be used to create and edit all kinds of text files.

Syntax: gedit file_name

<img width="454" height="50" alt="image" src="https://github.com/user-attachments/assets/8bb9ff37-8e54-4d9a-b5a5-c42375ca81d6" />


## 9) su Command
The su command provides administrative access to another user. In other words, it allows access of the Linux shell to another user.

Syntax: su

<img width="296" height="88" alt="cs9" src="https://github.com/user-attachments/assets/7ac4ef75-ca8e-4d35-8d53-0aaee9637d26" />


## 10) mv Command
The mv command is used to move a file or a directory form one location to another location.

Syntax: mv

<img width="520" height="238" alt="image" src="https://github.com/user-attachments/assets/af6eb197-40c2-4293-88f6-21cbd43b98e2" />


## 11) rename Command
The rename command is used to rename files. It is useful for renaming a large group of files.

Syntax: rename 's/old-name/new-name/' files

<img width="534" height="185" alt="image" src="https://github.com/user-attachments/assets/f540e9cd-d755-4470-982b-3481630fbe4b" />



## 12) head Command
The head command is used to display the content of a file. It displays the first 10 lines of a file.

Syntax: head

<img width="536" height="420" alt="image" src="https://github.com/user-attachments/assets/52156c41-4144-4cdf-b50b-7562b0403ff1" />


## 13) tail Command
The tail command is similar to the head command. The difference between both commands is that it displays the last ten lines of the file content. It is useful for reading the error message.

Syntax: tail

<img width="425" height="204" alt="image" src="https://github.com/user-attachments/assets/5fa83bac-485e-43f7-98ed-3fa0ba086763" />



## 14) id Command
The id command is used to display the user ID (UID) and group ID (GID).

Syntax: id

<img width="710" height="139" alt="image" src="https://github.com/user-attachments/assets/d63a405e-4622-494b-8f80-c328e92fe7e3" />


## 15) grep Command
The grep is the most powerful and used filter in a Linux system. The 'grep' stands for "global regular expression print." It is useful for searching the content from a file. Generally, it is used with the pipe.

Syntax: command | grep

<img width="459" height="82" alt="image" src="https://github.com/user-attachments/assets/a8719e40-2025-465a-860a-62e5ed84a81d" />


## 16) tr Command
The tr command is used to translate the file content like from lower case to upper case.

Syntax: command | tr <'old'> <'new'>

<img width="542" height="97" alt="image" src="https://github.com/user-attachments/assets/3536d4e9-42fd-45b8-809e-ae1462038b45" />


## 17) chmod Command
The chmod command is used to change the access mode of a file (i.e., read, write or execute)

Syntax: chmod<file_name>

<img width="606" height="133" alt="image" src="https://github.com/user-attachments/assets/c8563646-3b53-48be-97bf-7d6cc241085a" />


## 18) tar Command
The tar command is used for creating Archieve and extracting the archieve files.

Syntax: tar[options][archieve-file] [file to be archieved] $ tar xvzf file.tar *.c

<img width="459" height="180" alt="image" src="https://github.com/user-attachments/assets/f6ea13ae-00c9-4be6-b205-09c72ec8ce27" />


## 19) chown Command
The chown command is used to change ownership.

Syntax: chown owner_name file_name

<img width="472" height="132" alt="cs19" src="https://github.com/user-attachments/assets/62eedfd2-715a-4da5-b056-4131a132aed5" />

## 20) make Command
The make command is used for building and maintaining group of program.

Syntax: make [-f makefile][options]…….[targets]….

<img width="648" height="82" alt="image" src="https://github.com/user-attachments/assets/482ff4e2-449f-4311-be8b-4ef3339c8d50" />


## 21) ifconfig Command
The ifconfig command is used to configure kernel-resident network interface.

Syntax: ifconfig[options][interface]

<img width="861" height="104" alt="cs21" src="https://github.com/user-attachments/assets/e31638d9-d5da-43dd-b65e-ad271833d602" />


## 22) chmod 777 Command
The chmod 777 command gives read, write and execute permission to the owner, group and public.

Syntax: chmod 777 file_name $chmod -R 777 /path/to/file/or/folder

<img width="606" height="133" alt="image" src="https://github.com/user-attachments/assets/c8563646-3b53-48be-97bf-7d6cc241085a" />

## 23) host Command
The host command is used to display the IP address for a given domain name and vice versa. It performs the DNS lookups for the DNS Query.

Syntax: host or

<img width="615" height="152" alt="image" src="https://github.com/user-attachments/assets/9fc65d8b-3911-4461-9b99-2ed94cc61016" />


## 24) gzip Command
The gzip command is used to truncate the file size. It is a compressing tool. It replaces the original file by the compressed file having '.gz' extension.

Syntax: gzip ..

<img width="646" height="210" alt="image" src="https://github.com/user-attachments/assets/bef8f966-833b-407c-918e-966e27136677" />


## 25) sort Command
The sort command is used to sort files in alphabetical order.

Syntax:sort

<img width="382" height="74" alt="image" src="https://github.com/user-attachments/assets/f1aa5399-86f8-449f-b2df-388b7cb6e271" />


## 26) cal Command
The cal command is used to display the current month's calendar with the current date highlighted.

Syntax: cal

<img width="442" height="232" alt="image" src="https://github.com/user-attachments/assets/0d2d3589-2f72-4d57-b3eb-9e01c0c5e17e" />


## 27) clear Command
Linux clear command is used to clear the terminal screen.

Syntax: clear

<img width="593" height="178" alt="image" src="https://github.com/user-attachments/assets/776d48a1-31fe-4755-8eec-b89cdd43a882" />


## 28) mail Command
The mail command is used to send emails from the command line.

Syntax: mail -s "Subject"

<img width="724" height="64" alt="image" src="https://github.com/user-attachments/assets/7df7c8eb-731d-42de-8c3f-d61df67e8b8f" />



## 29) df Command
The df command is used to display the disk space used in the file system. It displays the output as in the number of used blocks, available blocks, and the mounted directory.

Syntax: df

<img width="744" height="332" alt="image" src="https://github.com/user-attachments/assets/4ebae088-d638-4ac0-baab-c578d7e4ff7b" />


## 30) find Command
The find command is used to find a particular file within a directory.

Syntax: find.-name”*.pdf”

<img width="542" height="250" alt="image" src="https://github.com/user-attachments/assets/8c571e66-c3b1-47d6-b82e-bf3b247be7d6" />


## Result:
Thus, the execution of various Linux commands is executed successfully using Kali Linux.

