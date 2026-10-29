# EX---4-ORACLE-VM-VIRTUAL-BOX-INSTALLATION--
### Aim :
To set up a virtualized environment using Oracle VirtualBox, install Kali Linux as a guest OS, and execute fundamental Linux commands.

### 3.a) Installation and Configuration of Oracle VirtualBox
### Aim:
To install and configure Oracle VM VirtualBox.

### Pre-requisites:
Machine with Internet access Minimum 4 GB RAM Sufficient storage space

### Steps:
Download Oracle VM VirtualBox:

Visit Oracle VirtualBox Official Site Download installer for your OS (Windows/macOS/Linux). Install Oracle VM VirtualBox (Example: Windows):

Launch Installer → Allow Changes → Click Next. Choose Installation Options → Click Next. Accept Network Interface Warning → Click Yes. Click Install. Finish Installation and Launch VirtualBox. Configure VirtualBox:

Open VirtualBox. Click New → Name VM → Select Type (Linux/Windows) and Version. Allocate: Minimum 2 GB RAM Create Virtual Hard Disk (20 GB recommended). Start Virtual Machine and provide ISO to install OS. Result: Thus, Oracle VM VirtualBox was installed successfully.

### 3.b) Installation and Configuration of Kali Linux
### Aim:
To install and configure Kali Linux in Oracle VirtualBox.

### Pre-requisites:
Oracle VM VirtualBox Installed 4 GB RAM and 20 GB Storage Minimum Kali Linux ISO image

### Steps:
Download Kali Linux ISO:

Visit Kali Linux Official Site Download 64-bit ISO (Installer version). Create a New Virtual Machine:

Open VirtualBox → Click New. Name: "Kali Linux" → Type: Linux → Version: Debian (64-bit). Allocate Memory:

Minimum 2 GB RAM (recommended 4 GB). Create Virtual Hard Disk:

Select VDI (VirtualBox Disk Image). Choose Dynamically allocated. Set Disk size to 20 GB or more. Configure ISO Image:

Settings → Storage → Controller: IDE → Empty CD → Choose Disk File → Select Kali Linux ISO. Start Installation:

Boot Virtual Machine → Choose Graphical Install. Set Language, Region, Keyboard. Configure Network → Set Hostname (e.g., kali). Set root password. Disk Partitioning: Use entire disk → All files in one partition. Install System → Install GRUB Bootloader → Finish Installation. Login to Kali Linux:

Use root credentials. (Optional) Install Guest Additions:

Devices → Insert Guest Additions CD Image → Follow steps inside Kali.

### Snapshots:
Snapshot 1: Installing Oracle VirtualBox 440120436-737dafde-fd5d-4266-849a-a12013ce9c5b
<img width="1919" height="999" alt="image" src="https://github.com/user-attachments/assets/d04bf4de-2efd-4cc6-80ca-687a81f7f7b0" />

Snapshot 2: Kali Running in Virtual 440120616-6b08c65e-e2c0-4f8e-a782-0914a3470759
<img width="1603" height="974" alt="image" src="https://github.com/user-attachments/assets/4509bc2a-1f35-4ba9-8892-7d402787d607" />

### Result:
Thus, Kali Linux guest OS was installed and configured successfully.

### 3.c) Execution of Linux Commands in Kali
### About Linux:
Open-source operating system. Kernel manages communication between hardware and software. Commands are case-sensitive.

### Linux Commands:
ls Command The ls command is used to display a list of content of a directory.
### Syntax:
```
1.ls
```
pwd Command The pwd command is used to display the location of the current working directory.
Syntax:
```
pwd
```
mkdir Command The mkdir command is used to create a new directory under any directory.
Syntax:
```
mkdir <directory_name
```
rmdir Command The rmdir command is used to delete a directory.
Syntax:
```
rmdir <directory_name>
```
cd Command The cd command is used to change the current directory
Syntax:
```
cd <directory_name>
```
cat Command The cat command is a multi-purpose utility in the Linux system. It can be used to create a file, display content ofthe file, copy the content of one file to another file, and more.
Syntax:
```
cat [options] [file_name]
```
cp Command The cp command is used to copy a file or directory.
Syntax:
```
cp [source] [destination]
```
8.mv Command The mv command is used to move a file or a directory form one location to another location.

Syntax:
```
mv [source] [destination]
```
touch Command Create empty file.
Syntax:
```
touch [filename]
```
vi Command Edit file contents using editor.

Syntax:
```
vi [filename]
```

### OUTPUT:

<img width="1920" height="1003" alt="image" src="https://github.com/user-attachments/assets/8abe90ae-5928-4f45-b09d-15ff9f5e5c14" />
<img width="1920" height="1003" alt="VirtualBox_kali-linux-2026 3-virtualbox-amd64_29_10_2026_13_42_41" src="https://github.com/user-attachments/assets/10fdb431-b1d8-470c-bc46-5d9a5a9733cf" />
<img width="1920" height="1003" alt="VirtualBox_kali-linux-2026 3-virtualbox-amd64_29_10_2026_13_43_09" src="https://github.com/user-attachments/assets/57a46264-8336-41f3-9382-303850945052" />
<img width="1920" height="1003" alt="VirtualBox_kali-linux-2026 3-virtualbox-amd64_29_10_2026_13_43_24" src="https://github.com/user-attachments/assets/8213ed3f-6574-4d8f-b712-4668ab249a60" />
<img width="1920" height="1003" alt="VirtualBox_kali-linux-2026 3-virtualbox-amd64_29_10_2026_13_43_24" src="https://github.com/user-attachments/assets/17e8a62d-a06c-4c8f-af87-b312d5ef58b9" />






### RESULT:
Thus, various Linux commands were executed successfully in Kali Linux virtual machine.
