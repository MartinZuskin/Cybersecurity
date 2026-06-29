# **1. Basics of Linux**



Linux is an operating system - like Windows, macOS, iOS or android. Operating system (OS) is a software that manages all the hardware resources of a computer. OS makes communication between software applications and hardware components easier. There are many different Linux distributions (distros) - versions of Linux used based on needs and preferences.



The Linux operating system started with the Unix operating system's release in 1970 by Ken Thompson and Dennis Ritchie. They both worked for AT\&T at that time. The Berkeley Software Distribution (BSD) was released in 1977. The development of BSD was limited due to contain of the Unix code owned by AT\&T.



At first, Linux was a personal project started in 1991 by a Finnish student Linus Torvalds. Linux is available in over 600 distributions. Some of the most popular are Ubuntu, Debian, Fedora, OpenSUSE, elementary, Manjaro, Gentoo Linux, RedHat and Linux Mint.



Linux is generally considered more secure than other operating systems. It is less susceptible to malware than Windows and is frequently updated. Linux is also stable and offers high performance to the end user.



Linux is an open-source project -> the source code can be modified and distributed by anyone. Linux-based operating systems are used on servers, desktops, embedded systems (routers, televisions, video game consoles...). Android OS us based on Linux kernel, and because of this, Linux is the most widely installed OS.



Parrot OS - Linux distribution that focuses on security, privacy, and development.



Linux advocates for building small, single-purpose programs hat perform one task well. These programs can be combined in various ways to accomplish complex operations. Linux follows five core principles:



1\. "Everything is a file" - all system resources (hardware, devices, processes, network connections...) are stored as files. Because of that, they can be read from and written to using the same tools and commands.

2\. "Small, single-purpose programs" - Linux offers many different tools, that can be combined to work together.

3\. "Ability to chain programs together to perform complex tasks" - integration and combination of different tools, enables to solve complex tasks, such as processing or filtering specific data results.

4\. "Avoid captive user interfaces" - Linux is designed mainly for work with shell, giving the user more control over the OS.

5\. "Configuration data stored in a text file" - An example is the /etc/passwd file, which stores all users registered on the system.



Components:

1\. Bootloader - a code that guides the booting process to start the OS. Parrot OS uses the GRUB Bootloader

2\. OS Kernel - the main component of an OS, manages resources for I/O devices at the hardware level.

3\. Daemons - background services, their purpose is to ensure key functions (scheduling, printing...) are working correctly, they load after the booting or logging into the computer.

4\. OS Shell - command language interpreter (command line), interface between the OS and the user. allows user to tell the OS what to do, most common - Bash, Tcsh/Csh, Ksh, Zsh, Fish.

5\. Graphics server - provides a graphical sub-system (server) called "X" or "X-server" that allows graphical programs to run locally or remotely on the X-windowing system.

6\. Window Manager - Graphical User Interface (GUI)

7\. Utilities - Applications or Utilities are programs that perform particular functions for the user or another program.



Linux Architecture:

1\. Hardware - Peripheral devices - RAM, hard drive, CPU...

2\. Kernel - gives each process its own virtual resources and prevents conflicts between different processes.

3\. Shell - a command line interface (CLI), user enters command to execute the kernel's functions.

4\. System Utility - makes OS functionalities available to the user.



File System Hierarchy:

The Linux OS is structured in a tree-like hierarchy and is documented in the Filesystem Hierarchy Standard (FHS). Linux is structured with the following top-level directories:

/bin, /boot, /dev, /etc, /lib, /media, /mnt, /opt, /home, /var, /usr, /tmp, /sys, /proc, /root, /run



1\. "/" - the top-level directory, contains all of the files required to boot the OS before other filesystems are mounted, as well as the files required to boot the other filesystems, after boot, all of the other filesystems are mounted at standard mount points as subdirectories of the root.

2\. "/bin" - contains essential command binaries.

3\. "/boot" - consists of static bootloader, kernel executable, and files required to boot the OS.

4\. "/dev" - contains device files.

5\. "/etc" - local system configuration files, configuration files for installed applications may also be saved here.

6\. "/home" - each user on the system has a subdirectory here for storage.

7\. "/lib" - shared library files that are required for system boot.

8\. "/media" - external removable media devices such as USB drivers are mounted here.

9\. "/mnt" - Temporary mount point for regular filesystems.

10\. "opt" - optional files such as third-party tools can be saved here.

11\. "/root" - the home directory for root user.

12 "/sbin" - executables used for system administration (binary system files)

13\. "/tmp" - used to store temporary files, generally cleared upon system boot and may be deleted at other times without any warning.

14\. "/usr" - executables, libraries, man files...

15\. "/var" - variable data files such as log files, email in-boxes, web application related files, cron files...



# 2\. Linux Distributions



Linux distributions are operating systems based on the Linux kernel. While they all share the same components, architecture and philosophy, each distribution offers its own unique products and services. This ensures the customization of the experience in order to meet diverse needs. Each distribution is different, with its own set of features, packages, and tools. Some popular examples - Ubuntu, Fedora, CentOS, Debian, Red Hat Enterprise Linux.



The most popular choices for desktop and beginners are Ubuntu and Fedora. It is also widely used as a server operating system for its security, stability and reliability, which comes with frequent and regular updates. Cybersecurity specialists often prefer Linux because it is open-sourced. Each Linux distribution may be customized the way we want.



The main differences between Linux distributions are the included packages, the user interface, and the tools available. The most popular distribution for cybersecurity specialists is Kali Linux - it includes a wide range of security-focused tools and packages. Ubuntu is widespread for desktop users, while Debian is popular for servers and embedded systems. Red Hat Enterprise Linux and CentOS are popular for enterprise-level computing.



## Debian



Debian is a widely used and well-respected Linux distribution known for its stability and reliability. The main use of this distribution is for desktop computing, servers, and embedded systems. It uses Advanced Package Tool (apt) package management system to handle software updates and security patches. The package management system automatically downloads and installs security updates as soon as they are available, helping to keep the system secure and up-to-date.



Debian is widely regarded as one of the most flexible and customizable Linux distros. The configuration an setup may seem complex, but it provides excellent control over the system, which can be good for advanced users. The more control we have over a Linux system, the more complex it feels to become.



However, it has had some vulnerabilities, but the development community has quickly released patches and security updates. In addition, Debian has a strong commitment to security and privacy, and the distribution has a well-established security track record.



Debian is a versatile and reliable Linux distribution, widely used for a range of purposes. Its stability, reliability and commitment to security make it an attractive choice for various use cases, including cybersecurity.



# 3\. Shell



A Linux terminal (shell) or command line, provides a text-based I/O interface between the users and the kernel for a computer system. Typical is alco the term "console", but it refers to a screen in text mode rather than window. In the terminal window, commands can be executed to control the system.



## Terminal emulators



Terminal emulation is software that emulates the function of a terminal. It allows the use of text-based programs within a GUI. There are also so called command-line interfaces (CLIs) that run additional terminals in one terminal.



## Shell



The most commonly used shell in Linux is Bourne-Again Shell (BASH), and is part of the GNU project. The shell gives us many more possibilities to interact with programs and processes to get information faster. Besides, many processes can be easily automated with scripts that make manual work much easier.



Besides Bash, there also exist other shells like Tcsh/Csh, Ksh, Zsh, Fish shell and others.

