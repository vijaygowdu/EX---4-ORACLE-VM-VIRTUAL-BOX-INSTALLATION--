## Ex.3(A-C) Virtualization: Installation and Configuration of Oracle VirtualBox & Kali Linux, and Execution of Linux Commands


## Aim :
To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.

## 3.a) Installation and Configuration of Oracle VirtualBox
## Aim:
To install and configure Oracle VM VirtualBox.

## Pre-requisites:
Machine with Internet access
Minimum 4 GB RAM
Sufficient storage space
## Steps:
Download Oracle VM VirtualBox:

Visit Oracle VirtualBox Official Site
Download installer for your OS (Windows/macOS/Linux).
Install Oracle VM VirtualBox (Example: Windows):

Launch Installer → Allow Changes → Click Next.
Choose Installation Options → Click Next.
Accept Network Interface Warning → Click Yes.
Click Install.
Finish Installation and Launch VirtualBox.
Configure VirtualBox:

Open VirtualBox.
Click New → Name VM → Select Type (Linux/Windows) and Version.
Allocate:
Minimum 2 GB RAM
Create Virtual Hard Disk (20 GB recommended).
Start Virtual Machine and provide ISO to install OS.
Result:
Thus, Oracle VM VirtualBox was installed successfully.

## 3.b) Installation and Configuration of Kali Linux
## Aim:
To install and configure Kali Linux in Oracle VirtualBox.

## Pre-requisites:
Oracle VM VirtualBox Installed
4 GB RAM and 20 GB Storage Minimum
Kali Linux ISO image
## Steps:
Download Kali Linux ISO:

Visit Kali Linux Official Site
Download 64-bit ISO (Installer version).
Create a New Virtual Machine:

Open VirtualBox → Click New.
Name: "Kali Linux" → Type: Linux → Version: Debian (64-bit).
Allocate Memory:

Minimum 2 GB RAM (recommended 4 GB).
Create Virtual Hard Disk:

Select VDI (VirtualBox Disk Image).
Choose Dynamically allocated.
Set Disk size to 20 GB or more.
Configure ISO Image:

Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali Linux ISO.
Start Installation:

Boot Virtual Machine → Choose Graphical Install.
Set Language, Region, Keyboard.
Configure Network → Set Hostname (e.g., kali).
Set root password.
Disk Partitioning: Use entire disk → All files in one partition.
Install System → Install GRUB Bootloader → Finish Installation.
Login to Kali Linux:

Use root credentials.
(Optional) Install Guest Additions:

Devices → Insert Guest Additions CD Image → Follow steps inside Kali.

## Snapshots:
AWS Account Creation Snapshot

Snapshot 1: Installing Oracle VirtualBox
![440120436-737dafde-fd5d-4266-849a-a12013ce9c5b](https://github.com/user-attachments/assets/c4dc7d5e-2bd2-48d7-85d5-1576256f5a3e)

Snapshot 2: Kali Running in Virtual
![440120616-6b08c65e-e2c0-4f8e-a782-0914a3470759](https://github.com/user-attachments/assets/2b88a9c0-c2ca-4aed-84c4-14dda2bfe217)

## Result:
Thus, Kali Linux guest OS was installed and configured successfully.

## 3.c) Execution of Linux Commands in Kali
## About Linux:
Open-source operating system.
Kernel manages communication between hardware and software.
Commands are case-sensitive.
## Linux Commands:
1. ls Command
The ls command is used to display a list of content of a directory.

## Syntax:
1.ls
![440122167-65cbb685-53e1-4d50-b109-2d3a73e366dc](https://github.com/user-attachments/assets/61f1907d-3d84-4f25-9b68-5998e548375d)

2. pwd Command
The pwd command is used to display the location of the current working directory.

## Syntax:
~~~
pwd
~~~
![440120811-06a87e8c-9f1f-4f33-9c75-d9a5f75c8d60](https://github.com/user-attachments/assets/da801c3c-9b4b-4e79-a575-61d8207cf1dc)

3. mkdir Command
The mkdir command is used to create a new directory under any directory.

## Syntax:
~~~
mkdir <directory_name
~~~
![440120918-1b1790eb-a58c-4bbb-a2b7-ee9ab6051a93](https://github.com/user-attachments/assets/a2449b41-5226-4db2-9c4e-ec00b7093d65)

4. rmdir Command
The rmdir command is used to delete a directory.

## Syntax:
~~~
rmdir <directory_name>
~~~
![440120963-5002fe8b-4414-42d0-8519-3d1f452fbafb](https://github.com/user-attachments/assets/4d9e840f-8a87-49b2-826a-e0e57f50ab7c)

5. cd Command The cd command is used to change the current directory
## Syntax:
~~~
cd <directory_name>
~~~
![440121083-84cead37-3512-4e54-8884-427cb99b15fc](https://github.com/user-attachments/assets/5528b556-0f1b-4147-a3cf-58bf3f25232e)

6. cat Command
The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content ofthe file, copy the content of one file to another file, and more.

## Syntax:
~~~
cat [options] [file_name]
~~~
![440121465-2361932b-99fc-4118-9097-bd9bdce384f0](https://github.com/user-attachments/assets/35335082-1110-47f7-b1ee-e7354509dfd0)
![440121476-4c6d451f-4bfc-48f1-b4cd-0217fef9e06c](https://github.com/user-attachments/assets/c5ee686f-024a-43da-89e7-cd9b881085b5)

7. cp Command
The cp command is used to copy a file or directory.

## Syntax:
~~~
cp [source] [destination]
~~~
![440121533-4e377a91-23d4-4169-a66b-f88af203a60b](https://github.com/user-attachments/assets/380f1b9e-5093-42a0-948e-04c9cbe82386)
![440121580-1edbd41c-31c2-4a94-8e7f-be35155e35e5](https://github.com/user-attachments/assets/898ddd40-a343-4f7a-b905-b0357947d5ec)

8.mv Command
The mv command is used to move a file or a directory form one location to another location.

## Syntax:
~~~
mv [source] [destination]
~~~
![440121624-fd4832ba-1dad-45a7-a213-a5f28ca508db](https://github.com/user-attachments/assets/a204b534-97bb-439c-9097-0607150668be)
![440121653-16138df9-da4a-4070-a936-29f251178773](https://github.com/user-attachments/assets/46882137-530f-440e-9156-ee1a3c002f06)

9. touch Command
Create empty file.

## Syntax:
~~~
touch [filename]
~~~
![440121709-0ee05807-fe42-4579-a1bf-6562904fd7b1](https://github.com/user-attachments/assets/ca943715-c063-4e65-9d89-f3fa03172653)

vi Command
Edit file contents using editor.

## Syntax:
~~~
vi [filename]
~~~
![440121931-77ca13f3-45d7-4da6-88af-cdd2e280f41b](https://github.com/user-attachments/assets/8bd49f85-89d9-432f-b018-ddf5eb20f894)

## Result:
Thus, various Linux commands were executed successfully in Kali Linux virtual machine.
