# linux-admin


# Troubleshoot Library Dependency Issues on Linux

tcpdump -c 5 -i eth0

ldd $(which tcpdump) | grep libpcap


dnf whatprovides */libpcap.so*


dnf reinstall -y libpcap


tcpdump -c 5 -i eth0

![image](https://user-images.githubusercontent.com/36766101/209530201-54493bbd-902f-43ac-ae1b-1a131c386455.png)
