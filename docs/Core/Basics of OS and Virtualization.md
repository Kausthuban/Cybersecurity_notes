### Operating Systems
Operating system in layman terms, OS is a complex software which allows you to utilize the physical hardware in a easy and user friendly way.

Operating Systems allow the user to interact with the physical hardware via a User Interface which may be Graphical(Graphical User Interface - GUI) or a command line (Command Line Interface - CLI).
This is interaction s enabled by a component called **kernel** which basically bridges the OS commands and the hardware.
There main operating systems commonly in use are - Linux, Macintosh(OS X), Chrome OS  and Windows.

Windows - The common OS for personal use. It is extremely user friendly. It is the most suitable for general purpose and most games are also developed for windows. Everyone who use a system knows it. It is mainly written in C. The source code is closed source.

Mac OS/ OS X - The sleek costly system which has better security compared to windows mainly because of a lot of restrictions on the software installed. It has a good performance and can be used for development too. Transition from windows to Mac requires a bit of practice. The source code is obviously closed source. 

Linux - The most widely used operating system but not an OS many know of. Linux is similar to UNIX. Most web servers run on Linux because of it's efficiency and lightweight. And all the android phone is built on top of a Linux kernel. It is a bit difficult to use, I agree, but it gives you complete control over the entire OS. Linux has different distributions like Ubuntu, Debian , Red Hat, Arch Linux, etc. and these distributions has many sub variants called flavours of linux like Kali linux and Parrot OS for debian, Ubuntu, Lubuntu for Ubuntu, etc. And the code for everything is Open Source, so you can go ahead and create your own distribution or flavour of linux if you're really enthusiastic. 

### What is virtualization
Simply put, virtualization is creating a system within a system that is isolated and acts as an independent system. Think of it as owning two different systems with a single set of hardware.

The technical explanation would be something like : Sharing the hardware resources of the host system(the physical machine) and allocate it to guest system(The virtual system).

The host and guest OS can be totally different. Some common Hypervysors are 
- VirtualBox
- VMWare
- Hyper-v
- KVM
- etc.
The hypervysors are the software which allocate and manage the resources between guest and the Host machines. 

Why use Virtual Machines?
The common reasons for using VMs are listed below
- Isolated environment
- Scalable and can be backed up easily
- High portability and live migration features for servers
- Maximizing resource utilization
- Test applications
- Use and practice various OSs

How to install?
1. To use a virtual machine. First enable the AMD virtualization for AMD devices and intel virtualization for Intel Devices in the BIOS settings
2. Install your Hypervysor (in this example Virtualbox) for your specific OS
3. Run the installer with default settings
4. Go to the website of the OS for installing the image file(disk file which is used to install the OS) [Kali](https://www.kali.org/get-kali/#kali-platforms), [Ubuntu](https://ubuntu.com/download/desktop),[Parrot](https://www.parrotsec.org/download/)
5. Install the ISO image for the OS
6. Create a new Virtual machine in Virtualbox
7. Provide the disk image path as the ISO file 
8. Modify the RAM, CPU and other hardware configurations according to your needs
9. Start the VM
10. Run the installer and follow the steps as such, no need to modify anything unless necessary.
11. Voila! the linux OS is installed
(The procedure for Other OSs depend and a Mac OS can be installed in a windows machine, but the performance is way too bad to use even with high configurations and is not worth it)