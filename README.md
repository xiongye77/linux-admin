# linux-admin

# Boot order of RHEL

![image](https://user-images.githubusercontent.com/36766101/217381477-cb13e487-8d6d-4fe1-b91d-a8cff0768d06.png)


# Analyse system boot time use systemd-analyze blame

![image](https://user-images.githubusercontent.com/36766101/217383089-b3c149be-781e-4848-bfe7-9d3b8c2b2d5b.png)


# Check which services are installed in the local Linux system  use  systemctl list-unit-files --type service and systemctl list-dependencies service-name and  systemctl get-default and systemctl set-default 

![image](https://user-images.githubusercontent.com/36766101/217384049-9dd9784b-0c85-4e24-a91b-2682cb4e3289.png)

![image](https://user-images.githubusercontent.com/36766101/217384085-7410cb9f-9fd5-46a3-84ec-fe1d6be6336b.png)

![image](https://user-images.githubusercontent.com/36766101/217384317-9c967016-c870-4c26-84b9-7bbfb1fe7581.png)

![image](https://user-images.githubusercontent.com/36766101/217384894-be1a9801-f608-4a15-83ab-224ffd081864.png)


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

# Use journalctl to record events on Linux

![image](https://user-images.githubusercontent.com/36766101/209545072-355c15a4-846e-49b9-88c7-e08220b2b642.png)
![image](https://user-images.githubusercontent.com/36766101/209545408-22f74935-5a8b-4749-a781-7b1404f50abb.png)
![image](https://user-images.githubusercontent.com/36766101/209545858-dea52d1a-3d61-430c-a378-22aa3c9ce2b1.png)
![image](https://user-images.githubusercontent.com/36766101/209546565-d639a543-4eef-4eb2-82df-7c413dfaca68.png)

# Tuned profile setting

![image](https://user-images.githubusercontent.com/36766101/217404506-47987c57-6780-43bf-9ae1-169e503d0d2b.png)
![image](https://user-images.githubusercontent.com/36766101/217404747-c222b13e-d1ce-4b81-abe3-959b0fdf09bb.png)



# Amazon Linux 2 NetworkManager
yum install NetworkManager
![image](https://user-images.githubusercontent.com/36766101/226061543-4e58b909-2f3d-4ffc-8f74-80e07cd09a86.png)
![image](https://user-images.githubusercontent.com/36766101/226061676-91d95e76-5973-4595-a3c4-2d1603883d04.png)
![image](https://user-images.githubusercontent.com/36766101/226061789-cb4f9038-ab58-41da-b22d-0bb07aa83ee1.png)
![image](https://user-images.githubusercontent.com/36766101/226062100-3e2cffe7-d08e-4126-898a-f2526fb58f09.png)
![image](https://user-images.githubusercontent.com/36766101/226063451-a55515bd-83ad-4c70-88c3-309b07d235cd.png)
![image](https://user-images.githubusercontent.com/36766101/226065878-57fa9c3d-dc2f-48d0-a5dc-1534b88bdb31.png)
![image](https://user-images.githubusercontent.com/36766101/226067028-f5c5043f-0c8a-4be1-a71c-b690e58d4d76.png)

![image](https://user-images.githubusercontent.com/36766101/226062972-940fa3d6-fa73-4bf3-82b4-25c0e080406a.png)
![image](https://user-images.githubusercontent.com/36766101/226063067-c2f30c17-e794-48d3-be9c-9f748a75fc7c.png)
![image](https://user-images.githubusercontent.com/36766101/226066061-0cc875ae-939f-472f-95bd-87fd949c5efc.png)

