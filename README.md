# linux-admin


# Troubleshoot Library Dependency Issues on Linux

[root@app ~]# tcpdump -c 5 -i eth0
tcpdump: error while loading shared libraries: libpcap.so.1: cannot open shared object file: No such file or directory


[root@app ~]# ldd $(which tcpdump)
        linux-vdso.so.1 (0x00007ffd0239b000)
        libcrypto.so.1.1 => /lib64/libcrypto.so.1.1 (0x00007f9edfe6b000)
        libpcap.so.1 => not found
        libc.so.6 => /lib64/libc.so.6 (0x00007f9edfaa6000)
        libz.so.1 => /lib64/libz.so.1 (0x00007f9edf88e000)
        libdl.so.2 => /lib64/libdl.so.2 (0x00007f9edf68a000)
        libpthread.so.0 => /lib64/libpthread.so.0 (0x00007f9edf46a000)
        /lib64/ld-linux-x86-64.so.2 (0x00007f9ee07b3000)
