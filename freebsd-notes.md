FreeBSD on Virtualbox
=====================


Overview
--------

- This is how I proceeded with the installation of FreeBSD on a virtual machine on Ubuntu.

Installation
------------

- Install virtualbox if you don’t have it yet:
  + `sudo apt-get install virtualbox`

- Go to freebsd.org and download the .iso image of your choice.

- Open virtualbox and click “New” on the upper-left corner.

- Give your virtual machine a sensible name. Under Type, choose BSD, and under Version, choose the
  one which corresponds to the architecture type of your downloaded image file.

- For the Memory Size, the 1024 MB default should suffice unless you require more depending on your
  needs.

- Choose “Create a virtual hard disk now” then click Create.

- Choose VDI (VirtualBox Disk Image) then click Next.

- Choose Dynamically allocated then click Next.

- Choose a name for the virtual hard disk file and for the size, adjust according to your needs,
  then click Create.

- Click on the newly-created virtual machine on the left side then click Start.

- You will be greeted by the FreeBSD Grub menu, wait for 9 seconds then it will proceed to the OS
  installation proper.

- In the next screen, for our purposes, choose Install then press the Enter button.

- Next, unless you require a special keyboard layout, continue with the default keymap.

- Choose a hostname for the machine then press Enter.

- In the next screen, you get to choose on optional system components to install. I suggest leaving
  the default selected values alone unless you require them.

- In the next screen, you will get to choose how to partition your disk and for beginners, choose
  the Auto (UFS) option.

- Next, as we are only using FreeBSD as a virtual machine, choose Entire Disk in the next prompt.

- For the partition scheme, choose MBR.

- In the next screen, check the partitions, choose Finish, then choose Commit to commence the
  installation process on your virtual machine.

- The next screen will prompt you for a new root password.

- Next, you will be prompted to configure a network interface of your choice.

- In the next prompt, choose Yes to configure IPv4.

- If the network provides a DHCP server, choose yes in the next prompt.

- If you require IPv6, choose Yes, otherwise No.

- The next screen will ask you to configure the DNS server of your choice.

- After that, you will now configure the time for your virtual machine based on your region.

- After configuring the time settings, you will now be prompted for services that you want to start
  at bootup.

- Next, you will be prompted for System Hardening options that you would like to enable.

- The installer will now ask you if you want to add users to the system now, choose Yes.

- In the next screen, fill out the username and the fullname. For the rest, you can leave them blank
  and you can just press the Enter button to proceed with the default values. For the “invite user
  to other groups” option, if you need the user to have administrative privileges, enter wheel. You
  will be prompted for a password and after that, it will ask you to review the information you just
  entered previously, and if you’re satisfied, enter yes. Finally, it will ask you if you want to
  add another user if you want to, so choose No to proceed to the final configuration.

- Review the following options, and if you’re set, choose Exit then press Enter. It will then ask
  you if you want to open a shell in the new system to make final modification, choose No. At the
  next screen, choose Reboot then press Enter.

- By this time, we’re now back at the FreeBSD Grub menu. Press the Space button to pause the
  auto-boot timer. To boot into the newly installed system, on the Devices option of VirtualBox, go
  into Optical drives, then remove the disk from the virtual drive then press 1 to boot into the
  installed system.


Configuration
-------------

- It is a good practice to check for system updates after a fresh installation, so run the following as root:
  + `freebsd-update fetch`
  + `freebsd-update install`

- After that, update the package manager and the installed software using the following commands:
  + `pkg update`
  + `pkg upgrade`

- To enable 3d acceleration for the user that will run Xorg, run the following commands:
  + `pw groupmod video -m user || pw groupmod wheel -m user`

- To start Xorg, run the command:
  + `startx`
  
- To exit Xorg, run `exit` on the login terminal.


Usage
-----

- To run your virtual FreeBSD installation, just open up VirtualBox, select the virtual machine
  image, then click Start.
