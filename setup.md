## Components:
* 2 Raspberry Pi desktop Virtual Machines (2022-07-01-raspios-bullseye-i386.iso)
* Windows 11 Host Device
* Splunk
* VirtualBox

## Raspberry Pi Set-Up
1. Install Raspberry Pi Desktop at https://www.raspberrypi.com/software/operating-systems/#raspberry-pi-desktop
2. Open VirtualBox, create a New machine and set the VM options below
3. Settings>Storage>Controller IDE>Attributes>Optical Drive>Choose a Disk File... and select the iso file
4. Start the Virtual Machine and follow the graphical installation

### VM Settings
* 128 MB Video Memory
* 15 GB Storage
* 4096 MB Base Memory
* 2 CPU

### Graphical Installation
1. Select graphical install
2. Select language
3. Select guided - use entire disk
4. Select the partition disk
5. Select Finish partitioning and write changes to disk
6. Select "yes" to "Write the changes to disks?"
7. Install the GRUB boat loader and select /dev/sda
8. Set-up time, region, and log-in

### Quality of Life 
* General>Advanced>Bidirectional clipboard
* Preferences>Screen Configuration, right-click and choose the desired resolution
