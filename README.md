# linux-admin


# Troubleshoot Library Dependency Issues on Linux

tcpdump -c 5 -i eth0

ldd $(which tcpdump) | grep libpcap


dnf whatprovides */libpcap.so*


dnf reinstall -y libpcap


tcpdump -c 5 -i eth0

![image](https://user-images.githubusercontent.com/36766101/209530201-54493bbd-902f-43ac-ae1b-1a131c386455.png)


# Install NFS utili and Create and Export the File System

on server side
![image](https://user-images.githubusercontent.com/36766101/209531304-1c0a08a6-ff00-42d0-9a75-388c8e9de167.png)
![image](https://user-images.githubusercontent.com/36766101/209532379-99b603b1-70f1-45f7-bf31-d501e970291f.png)

on client side 
![image](https://user-images.githubusercontent.com/36766101/209532824-f0380a89-95e4-4cc7-a9cd-6ef7499aff1d.png)



# Using systemctl to configure process setting
The systemctl utility is used for so many tasks and contains such a large amount of subcommands that it can be slightly intimidating at first for those familiar with individual commands for most management tasks.

We'll get you used to using systemctl to view systemd's environment, settings, view status on services, show and set parameters that affect service function, and understand what happens when you set settings, both from a systemd daemon perspective, as well as drop-in directories and additional configuration add-ins.

![image](https://user-images.githubusercontent.com/36766101/209542794-2fb2920b-64f1-4a68-b3d3-7398821b36a6.png)

![image](https://user-images.githubusercontent.com/36766101/209544030-8399b750-a7b1-47e0-81b9-3f7e7fc4947f.png)

