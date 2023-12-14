# Born2beroot
<h2>This project aims to introduce you to the wonderful world of virtualization. You will create your first machine in VirtualBox (or UTM if you can’t use VirtualBox) under specific instructions. Then, at the end of this project, you will be able to set up your own operating system while implementing strict rules.</h2>

<h3>Theoretical questions</h3>
<h4>Here are the theoretical questions you will be asked during the evaluation:</h4>
1. How does a virtual machine work ? And what its purpose ? </br>
2. Wh did you choose Debian or Rockey ? </br>
3. What's the difference between Debian and Rockey ? </br>
4. If you chose Debian: what's the difference between aptitude, apt and what's APPArmor ? </br>
5. If you chose Rockey: what's SELinux and DNF ? </br>
6. What the advantages/disadvantages of a strong password policy ? What can you say about its implementation ? </br>
7. What's a partition ? And more generally how does LVM (Logical Volume Management) work ? </br>
8. What's sudo ? </br>
9. What's an UFW and what's the value of using it ? </br>
10. What's SSH (Secure Shell) and what's the value of using it ? </br>
11. What is cron ?

<h2> What is virtual machine ? </h2>
- A VM is a virtualized instance of a computer that can perform almost all of the same functions as a computer, including running applications and operating systems. 
Virtual machines run on a physical machine and access computing resources from software called a hypervisor.

<h2> What its purpos ?</h2>
- A virtual machine (VM) is a digital version of a physical computer. 
Virtual machine software can run programs and operating systems, store data, connect to networks, and do other computing functions, and requires maintenance such as updates and system monitoring.

<h2> Wh did you choose Debian ?</h2>
- Because it's easy for beginners and has a large community.

<h2> What's the difference between Debian and Rockey ? </h2>
- The difference between Debian and Rockey is that Debian is easy to use for beginners while Rockey is made for advanced programmers.
Debian uses apt and Aptitude as packaging tools, while Rockey uses dnf and Selinux as security software, while Debian uses AppArmor.

<h2>what's the difference between aptitude, apt and what's APPArmor ?</h2>
- Apt is an advanced packaging tool that is used by the OS to install packages, and it is automatically integrated in the OS, and it have a user interface.  </br>
- Aptitude is the same as apt, but it's not integrated with the OS. We just install it with apt. And aptitude has a graphical user interface. </br>
- AppArmor is a Linux kernel security module that allows the system administrator to restrict programs' capabilities with per-program profiles. Profiles can allow capabilities like network access, raw socket access, and the permission to read, write, or execute files on matching paths.

<h2>What the advantages/disadvantages of a strong password policy ?</h2>
- In theory, the main benefit of password complexity rules is that they enforce the use of unique passwords that are harder to crack.

<h2>What's a partition ? And more generally how does LVM (Logical Volume Management) work ?</h2>
- A partition is a logical division of a hard disk that is treated as a separate unit by operating systems (OSes) and file systems. The OSes and file systems can manage information on each partition as if it were a distinct hard drive. </br>
- How does LVM work : It works by chunking the physical volumes (PVs) into physical extents (PEs). The PEs are mapped onto logical extents (LEs) which are then pooled into volume groups (VGs). These groups are linked together into logical volumes (LVs) that act as virtual disk partitions and that can be managed as such by using LVM. </br>

