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
