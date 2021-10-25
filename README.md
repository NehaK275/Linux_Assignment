# Linux_Assignment
### 1.What is a GNU project?
GNU project is a mass collaborative initiative for the development of free software. GNU project was founded by Richard Stallman in 1978 at MIT. The purpose of GNU project was the creation of a free software. The project was started to create a Unix -like operating system created with source code that would be copied, modified and redistributed.

### 2.What is the difference between Unix & Linux?
|Unix | Linux |
|--------------------------------- | -------------------------------- |
| Unix is an operating system that can be only utilized by its copywriter. | Linux is an open-source operating system that is freely accessible to everyone. |
| Supports file system but lesser than Linux. | Supports more file system than Unix.|
| Used in servers, workstation and PCs. | Used everywhere from servers, PCs, smartphones, tablet to mainframe. |
| Some Unix version are SunOS, Solaris, SCO, Unix etc. | Some Linux version are Ubuntu, Debian, GNU, Arch Linux, etc.|

### 3.What do you mean by Integrity check of BIOS? Mention firmware other than BIOS
The system integrity check performed by BIOS is called POST (Power on Self-Test). This is a very brief test on CPU, memory and storage devices to verify that the system is in a boot-able state. Then it will check in the boot priority order to find a boot-able device. It will check in Disk drive, SD card reader, CD/DVD ROM, Hard drive according to the boot priority that is configured.
Firmware other than BIOS is UEFI. It is a successor of BIOS. UEFI is designed to boot the system instead of BIOS. UEFI store all the info in a .efi file. The file is stored in another partition called EFI partition along with the bootloader. It comes with many improvements than BIOS but Linux is still using BIOS.

### 4.What is a UEFI?
UEFI is the short form of Unified Extensible Firmware Interface. In simple words we can say that it is a successor of BIOS. UEFI is designed to boot the system instead of BIOS. UEFI store all the info in a .efi file. The file is stored in another partition called EFI partition along with the bootloader. It comes with many improvements than BIOS but Linux is still using BIOS.

Security benefits of UEFI:

*	Device guard

*	Credential guard

*	Biometric authentication

*	Faster start-up times

*	Faster shutdown times

*	Faster sleep times

*	Faster resuming times

### 5.What is the difference between BIOS & UEFI?
|BIOS | UEFI |
|--------------------------------- | -------------------------------- |
| BIOS only supports2.2 terabyte | Support drive size upto 9 zettabytes |
| Slower as compared to UEFI | Faster boot time |
|Runs in 16bit mode | Runs in 32bit or 64bit mode |
| 1 MB Memory | All system Memory|

### 6.When should you go for Ubuntu & when for other systems?
It is totally depended on our choice that when we go for ubuntu and when for other system. In comparison to Windows, Ubuntu provides a better option for privacy and security. The best advantage of having Ubuntu is that we can acquire the required privacy and additional security without having any third-party solution. Risk of hacking and various other attacks can be minimized by using this distribution.

### 7.List various Linux distributions & their use cases.
Linux distribution is a version of the open-source Linux operating system that is packed with other component such as an installation programs, management tools and additional software.
various Linux distributions are:
* `Ubuntu` It works like MacOS and easy to use.
* `Linux mint` It works like windows and should be use by new corners
* `Debian` It provide stability but not recommended to a new user.
* `Fedora` It is a community-based project by Redhat. It uses dnf package manager.

###  8.What does a systemd. unit (5) means?
A unit configuration file whose name ends in “. service" encodes information about a process controlled and supervised by systemd. systemd.exec(5) define the execution environment the commands are executed in, and in systemd.kill(5), which define the way the processes of the service are terminated, and in systemd.resource-control(5), which configure resource control settings for the processes of the service.

### 9.What are Getty commands and Uname command?
Getty command: the Getty command set and manages terminal lines and ports. This command is run by the init command.

Uname command: the uname command is commonly used to determine the process architecture, the system hostname and the version of the kernel running on the system.

### 10.What is squashfs file system?
squashfs file system is a read only file system that lets us compress whole file systems or single directories. We can write them to other devices/partitioned or to ordinary files and then we can mount them directly (if it is a device) or using a loopback device (if it is a file).

### 11.What are /dev/loop and /dev/tty?
The `/dev/loop` devices treat files with a filesystem image as if they were block devices. The loop devices are snaps because snap packages are created that way.
These files were containing a filesystem that is mounted to the location. It is an approach that developers use to pack an entire package in a single file, but the operating system access all the files. The approach used here is therefore known as loop mounts.

`/dev/tty` stands for the controlling terminal (if any) for the current process. To find out which tty's are attached to which processes we use the "ps -a" command at the shell prompt (command line).

### 12.What are Linux Signals?
Signals are software interrupts sent to a program to indicate that an important event has occurred. The events can vary from user requests to illegal memory access errors. Some signals, such as the interrupt signal, indicate that a user has asked the program to do something that is not in the usual flow of control.

### 13.What is the purpose of creating and using hidden files.
Hidden files are used for storage of user preferences or for preservation of the state of utilities. They are created frequently by various system or application utilities. Hidden files are helpful in preventing accidental deletion of important data.

### 14.How ext4fs is faster/better?
ext4 file system is faster among all the ext. file system. The ext4 filesystem is also capable of performing faster file system checks than other equivalent journaling filesystems.

### 15.What is swap & swap memory?
`Swap` is a space on a disk that is used when the amount of physical RAM memory is full. When a Linux system runs out of RAM, inactive pages are moved from the RAM to the swap space.

`Swap memory` is the dedicated amount of hard drive that is used whenever RAM runs out of memory. There is a memory management program in Linux that takes care of this process. Whenever RAM is short of memory, the memory management program looks for all those inactive blocks of data present in RAM that have not been used for a long time.

### 16.How to mount a file system?
On Linux operating systems, you can use the mount command to attach (mount) file systems and removable devices such as USB flash drives at a particular mount point in the directory tree. When used without any argument, the mount command will display all currently attached file systems:
 `$mount`
By default, the output will include all file systems including the virtual ones such as cgroup, sysfs, and others. Each line contains information about the device name, the directory to which the device is mounted to, the type of the filesystem and the mount options in the following form:
Device_name on directory type filesystem_type(options)

### 17.Mention a ZFS use case.
ZFS stands for Zettabyte File System. It is a local file system and logical volume manager created to direct and control the placement, storage and retrieval of data.
ZFS is built into the Oracle OS and offers an ample feature set and data services free of cost. ZFS is a free open-source filesystem that can be expanded by adding hard drives to the storage pool.

### 18.How to check the port number of a process?
we can check the port number of a process by using the command netstat -ano -p tcp. we can use "netstat" to check whether a port is available or not. We use the netstat -anp | then find "port number" command to find whether a port is occupied by an another process or not. If it is occupied by another process, it will show the process id of that process.

### 19.What is Unix time sharing (UTS)?
Unix time sharing allows a single system to appear to have a different host and domain name to different process.

### 20.What are control groups?
control group allow to relocate the resources such as CPU time, system memory, network bandwidth.

### 21.What is the difference between sbin & usr/sbin?
 `/sbin` as distinct from /bin, is for system management programs (not normally used by ordinary users) needed before /usr is mounted.
 `/usr/sbin` is a subdirectory of /usr, which is used to store many application programs. Another subdirectory of /usr, /usr/bin, contains programs that are not required for booting or repairing the system. The directory /usr/local/sbin is used for locally installed system administration programs.

### 22.Examples of awk, grep and sed
AWK:It is a utility that enable a programmer to write small but efficient code in the form of statement that define the text pattern.
Example of awk:
 $cat > employee.txt 
ajay manager account 45000
sunil clerk account 25000
varun manager sales 50000
amit manager account 47000
tarun peon sales 15000
deepak clerk sales 23000
sunil peon sales 13000
satvik director purchase 80000 
$ awk '{print}' employee.txt
Output:  
ajay manager account 45000
sunil clerk account 25000
varun manager sales 50000
amit manager account 47000
tarun peon sales 15000
deepak clerk sales 23000
sunil peon sales 13000
satvik director purchase 80000

GREP: It is used to perform text searches for a defined criteria of word or string. It filters searches a file for a particular pattern of character and display all line that contain that pattern.
Example of grep:
         `Match all lines that start with ‘hello’. E.g.: “hello there”`
              `$ grep “^hello” file1`

SED: It perform lot of function on file like searching, find and replace, insertion and deletion. It is used to perform basic text transformation on an input stream. 
Example of sed:
`Displaying partial text of a file:` 
With sed, we can view only some part of a file rather than seeing whole file. To see some lines of the file, use the following command,
`$ sed -n 22,29p testfile.txt.`

### 23.How many tables are there in iptables?
There are 5 tables in iptables:
* `Filter` It works as the bouncer and determine who gets out and in of our network.

* `Nat` it stands for Network Address Translation. It includes rules of NAT to route packet to the network that cannot be directly accessible. If the source or destination of a packet has to be modified then NAT table will be used.

*	`Mangle` this table is used for adjusting the packet’s IP header properties. It contains following chain Forward, input, output, past-routing, pre-routing.

*	`Raw` this table is used for exempting packets through connection tracking. It contains two chains: pre-routing and output.

* `Security` It is used for managing unique access rule.It contains forward, input and output chains.

### 24.What is prot, opt, in, out, source & destination?
* `prot` The protocol for rule.
* `opt` special options for the specific rule.
*  `in` Name of input interface via which the packet is received.
*  `out` Name of output interface via which the packet will be send.
* `Source` It shows the information of the source of the packet.
* `Destination` It shows the information regarding the destination of the packet to be reached.

### 25.Why rules are added to the top?
Rules are added to the top of the iptables because it will neglect the rules defined below a particular rule which is defined on the top.

### 26.What type of rules we can add to the iptables?
we can add different types of rules, e.g. we can block a specific ip address, allowing ssh from a specific network, allow all incoming ssh, allow  incoming HTTP & HTTPs.

### 27.Can we block a website by its domain name only?
yes, we can block a website by its domain name only but iptables deals with ip addresses only so sometimes these rules doesnot as they should.
we can block a website by its domain name only,for e.g.

`$ sudo iptables -A input -i facebook.com -j drop`
 
### 28.How can we persist rules in iptables?
We can persist rules in iptables by using command

`sudo netfilter-persistent save`

or

`sudo iptables-save > /etc/iptables/rules.v4`

### 29.How can we save rules in iptables?
we can save rules in iptables by using the command 

`sudo netfilter-persistent save`

or

`sudo iptables-save > /etc/iptables/rules.v4`

### 30.What is the difference between ufw & iptables?

| ufw | iptables |
|--------------------------------- | -------------------------------- |
|It is a frontend for iptables and is particularly well-suited for host-based firewall. |Iptables is a frontend tool to talk to the kernel and decides the packets to filter.|
|It provides a framework for managing net filter as well as a command line interface for manipulating the firewall.| Iptables is a tool for managing firewall rule on a Linux machine. |
 
### 31.What are public & private keys?
In `public` key, two keys are used. One key is used for encryption and another key is used for decryption.

In `private` key, same key is used for encryption and decryption.

### 32.How does ssh work?
`ssh` stands for secure shell is a network communication protocol that enables two computers to communicate. Ssh is also used to securely log into the remote operating system.
Ssh work on a client/server model where the ssh client is the system that require remote access and the ssh secure provide it. Therefore, creating a secure channel by the use of secure shell key.

### 33.What is the difference between HTTP & HTTPS.
|HTTP | HTTPS |
|--------------------------------- | -------------------------------- |
| HTTP stands for Hypertext Transfer Protocol. | HTTPS stands for Hypertext Transfer Protocol Secure. |
| It is an application layer protocol for transmitting hypermedia documents.| It is an extension of HTTP. |
| It was designed for communication between web browser and web server.|It is used for server communication over a network.|
| Use port no 80 for communication. |Use port no 443 for communication. |

### 34.What is SSL?
`SSL` stands for Secure Socket Layer. It is a protocol for establishing secure links between networked computer. It is a security protocol that creates an encrypted link between a web server and a web browser.

### 35.What is the difference between apt update & apt upgrade.
`Apt update` is used to update all the package list.

`Apt upgrade` is used to update all the installed software to the latest version.

### 36.What do repositories contain in a Linux system?
A Linux repository is a storage location from which your system retrieves and installs OS updates and applications. Each repository is a collection of software hosted on a remote server and intended to be used for installing and updating software packages on Linux systems.

### 37.What are the package managers used in Linux?
Package manager is a tool that allow users to install, remove, upgrade, configure and manage software package on an operating system.

In Linux, we have two types of package manager.

`Low level package manager` They are only responsible for installing the application and not the dependencies. e.g. dpkg,rpm

`High level package manager` They resolve the dependencies & meta data searching. e.g.apt

### 38.What does the number represent after the file permissions?
It denotes the number of files contained in that particular directory.

### 39.What is the difference between apt and apt-get?
`Apt` is a command line utility for installing, updating, and removing deb package.

`Apt-get` is a cli package manager tool i.e., widely used on Debian based system. It allows us to install, update and remove package.

### 40.How can I give access to someone to my AWS instance?
Add a new user to the EC2 Linux instance

1.	Connect to your Linux instance using SSH.

2.	Use the add user command to add a new user account to an EC2 instance (replace new_user with the new account name). 

3.	Change the security context to the new_user account so that folders and files you create have the correct permissions:

### 41.What are daemon applications?
A daemon (also known as background processes) is a Linux or UNIX program that runs in the background. Almost all daemons have names that end with the letter "d". A daemon is a service process that runs in the background and supervises the system or provides functionality to other processes.

### 42.What does a “. d" represent after a filename?
"d" stands for directory and such a directory is a collection of configuration files which are often fragments that are included in the main configuration file. 

### 43.What happens when a .pem file gets deleted?
`.pem` file are a type of public key infrastructure file used for key and certificate. They are used to store SSL certificate and their associate private key.When a .pem file gets deleted then we won’t be able to connect to your instance because it requires pem file. But we can gain access again by creating a new instance. We can create a new instance with the same key pair and we can access our AWS instance.

### 44.What information is stored in the /etc/host file?
The `/etc/hosts` file contains the Internet Protocol (IP) host names and addresses for the local host and other hosts in the Internet network. This file is used to resolve a name into an address (that is, to translate a host name into its Internet address).

### 45.What is SCP & what does this command do?
SCP stands for secure copy. It is used to copy file between server in a secure way. It allows the local host and the remote host or between two remote host.

### 46.How port forwarding works?
Port forwarding is an application of network address translation (NAT) that redirects a communication request from one address and port number combination to another while the packets are traversing a network gateway, such as a router or firewall.
It is a mechanism in ssh for tunnelling application port from client machine to a server machine or vice-versa.

`Local port-forwarding` connection from ssh client are forwarded through the ssh server to a destination server.

`Remote port-forwarding` connection from ssh server are forwarded through the ssh client to a destination server.

`ssh -L local_port:destination_server_ip:remote_port ssh_server_hostname`

### 47.How can we connect without IP to AWS instance?
We will add the public IP of master & slave instances with in host file of local system. Then we can connect with the instances using ssh keyword.

`ssh -i "AWS-Key-Jenkins.pem: ubuntu@master`

### 48.What is an ssh agent?
`ssh-agent` is a key manager of SSH.It is a program to hold private keys used for public key authentication. Through use of environment variables the agent can be located and automatically used for authentication when logging in to other machines using ssh(1).

### 49.Create a unit file for any application.

### 50.What is RHEL?
Red Hat Enterprise Linux (RHEL) is a Linux-based operating system from Red Hat designed for businesses. RHEL can work on desktops, on servers, in hypervisors or in the cloud. Red Hat and its community-supported counterpart, Fedora, are among the most widely used Linux distributions in the world.Red Hat Enterprise Linux has multiple variants, with server versions for x86, x86-64, PowerPC, Itanium and IBM System z. It also includes desktop versions for x86 and x86-64. As of November, 2011, the latest variant of RHEL is RHEL 6.
